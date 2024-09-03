---
layout: project
type: project
image: img/tubereader/tubereader.png
title: "Word Dough"
date: 2023
published: true
labels:
  - React
  - PHP
  - Flask
  - MySQL
  - Material UI
  - OpenAI
  - Bootstrap 5
  - JQuery
summary: "A remake of the famous New York Times game Wordle."
---

# TubeReader (WIP)

TubeReader is a sophisticated tool designed to convert YouTube videos into well-structured blog articles. It offers a range of customization options to tailor the generated content to specific needs, making it ideal for developers, creators, and everyday users looking to enhance their content strategy.

## Key Features

- **Customizable Article Generation**: Choose from multiple options for title, font, theme, length, and language.

- **Article Tone Adjustment**: Select the tone of the generated articles to match your brand or audience.

- **Public, Unlisted, and Private Options**: Control the visibility of generated articles based on your preferences.

- **Batch Uploading**: Soon to be available, allowing for multiple videos to be processed simultaneously.

- **Support for Longer Videos**: Upcoming feature to handle extended video content efficiently.

## APIs Used

- **YouTube Transcript API (Self-Hosted)**: Provides the text transcripts of YouTube videos, which are essential for converting spoken content into written articles. By hosting it ourselves, we ensure better control and integration within our platform.
  
- **[OpenAI Completions API](https://platform.openai.com/docs/overview)**: Powers the content generation and enhancement of articles using OpenAI's flagship GPT-4o model. It also aids in evaluating the appropriateness of custom article titles to ensure they are suitable for most ages.

- **[YouTube Data V3](https://developers.google.com/youtube/v3)**: Retrieves detailed information about YouTube videos, such as titles, descriptions, and thumbnail images, which aids in accurately representing and summarizing video content.
  
- **[UserCheck API](https://docs.usercheck.com/)**: Checks email addresses to identify and filter out disposable email addresses, ensuring that user registrations are valid.




