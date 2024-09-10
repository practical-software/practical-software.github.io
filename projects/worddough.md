---
layout: project
type: project
image: img/worddough/worddoughlogo3.png
title: "Word Dough"
date: 2023
published: true
labels:
  - Javascript
  - PHP
  - MySQL
  - Bootstrap 5
  - JQuery
summary: "A remake of the famous New York Times game Wordle."
---


<img class="img-fluid" src="../img/worddough/Word-Dough-Home.png">

## About:

Word Dough is a revamp of the popular New York Times game "Wordle," designed to elevate the competitive experience with additional features. This custom version incorporates a login and registration system, allowing players to track their progress and compete against each other through a dynamic leaderboard.

Throughout the development of Word Dough, I worked independently, which required me to build my problem-solving and project management skills.

Since this was my first full-stack application, I was able to learn the intricacies of PHP, MySQL, and MySQLi. I also learned the importance of API integrations and a secure user authentication system.

### Example MySQL Query from [Leaderboard Page](https://www.practicalsoftware.com/worddough/leaderboard.html):

```php
$leaderboardSQL = "
    SELECT JSON_OBJECT(
        'display_name', `displayname`,
        'avg_guesses', ROUND(AVG(`num_guesses`), 2),
        'win_percentage', ROUND(AVG(is_win) * 100, 2)
    ) AS json_data
    FROM game_reports
    GROUP BY `displayname`
    ORDER BY ROUND(AVG(`num_guesses`), 2) ASC
    LIMIT 15;
";

// Execute query
$query = mysqli_query($conn, $sqlString);

if ($query) {
    $jsonArray = array();
    // Fetch results as associative array and check for errors
    while ($row = mysqli_fetch_assoc($query)) {
        if ($row && isset($row['json_data'])) {
            $jsonArray[] = $row['json_data']; // Add each JSON object to the array
        } else {
            error_log("Missing 'json_data' in query result row");
            echo "Error: Unexpected data format.";
            exit;
        }
    }
    // Output the array as a JSON string
    echo json_encode($jsonArray);
} else {
    // Log and output the SQL error if the query fails
    error_log("Query error: " . mysqli_error($conn));
    echo "Error executing query.";
}

```


## Key Features:

- **Login and Registration System**: Allows players to create accounts, log in, and track their progress.

- **Leaderboard**: Enables players to view and compare their scores with others.

- **User Authentication**: Manages user sessions and account authorization through client-side cookies.


## APIs Used:

- [Merriam-Webster Dictionary API](https://dictionaryapi.com/): Validates user-inputted words to ensure they are legitimate, maintaining the quality of gameplay.

- [OpenAI Moderation API](https://platform.openai.com/docs/guides/moderation): Monitors and filters usernames to ensure a respectful and appropriate gaming environment.




## [Play Now!](https://practicalsoftware.com/worddough/index.html)
