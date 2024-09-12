---
layout: essay
type: essay
title: "Insightful Inqueries"
# All dates must be YYYY-MM-DD format!
date: 2024-09-11
published: true
labels:
  - Stack Overflow
---

## 
Everyone has questions when they are in the middle of programming, whether it's a bug in the code, an internal server error, or a conceptual question. People often turn to platforms like StackOverflow, where millions of tech users go for help. Nonetheless, after scrolling through multiple sections, I realized just how unclear and confusing some questions are, which results in a flurry of downvotes. This is why it is vital to ask smart questions. 

## Why Smart Questions?

According to Rick Moen, "The kind of answers you get to your technical questions depends as much on the way you ask the questions as on the difficulty of developing the answer." In short, straightforward and detailed questions will result in straightforward and detailed answers. However, before asking questions to others, it is important to do some work for yourself. 

### For example...
1. Search for answers on Google (maybe your question is already answered elsewhere)
2. Check the official website's documentation
3. Run some tests or check your code
4. Ask a GenAI AI chatbot (may provide an answer or lead you on the right path)

## What Constitutes a Smart Question?

#### Being Clear and Concise:

- Make sure to get to the point quickly but clearly, with enough detail about the issue or context.

#### Be Detailed:

- Provide as much detail as possible about the problem, including relavent background information such as code examples or versioning.

#### Use Common Etiquette:

- Always use proper grammar practices, punctuation, and capitalization. Don't include code blocks that are too lengthy or too short and uninformative.

## A Smart Question:

##### Here's an example of a smart question from [Stack Overflow](https://stackoverflow.com/questions/40526102/how-do-you-format-a-date-time-in-typescript):

### How do you format a Date/Time in TypeScript?

I have a class Module which is defined as:

```js
export class Module {

    constructor(public id: number, public name: string, public description: string, 
                 public lastUpdated: Date, public owner: string) { }

    getNiceLastUpdatedTime(): String {

        let options: Intl.DateTimeFormatOptions = {
            day: "numeric", month: "numeric", year: "numeric",
            hour: "2-digit", minute: "2-digit"
        };

        return this.lastUpdated.toLocaleDateString("en-GB", options) + " " + this.lastUpdated.toLocaleTimeString("en-GB", options);
    }
}
```

When I call the method with the following code:

```js
let date = new Date(1478708162000); // 09/11/2016 16:16pm (GMT)
let module = new Module(1, "Test", "description", date, "test owner");
console.log(module.getNiceLastUpdatedTime());
```

I end up with the following printed in the console:

```9 November 2016 16:16:02 GMT```


What I want to see is:

```09/11/2015 16:16```

I've had a look at the documentation at: [Mozilla Docs URL](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toLocaleDateString) and I still can't see what I'm doing wrong (I know this is a JavaScript API documentation but I'm pretty sure that's what TypeScript is using under the hood).

<br>

Although not perfect...

What I like about this quewstion is that it provides specific context on the ```Module``` Class and how the user is trying to solve the problem. 

Additionally, I think the "Expected" vs "Actual" answer is important to understanding the problem and what output is wanted. 

Lastly, linking the documentation shows initial research was done, and that the question was not asked without proper research first.


