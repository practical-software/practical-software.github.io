---
layout: essay
type: essay
title: "An Upgraded JavaScript"
# All dates must be YYYY-MM-DD format!
date: 2024-09-03
published: true
labels:
  - JavaScript
  - TypeScript
---

## My Experience with Typescript

As someone with a background in web development, learning Typescript felt quite natural. To put it into words, TypeScript feels like a structured and disciplined twist on JavaScript, primarily because of its static typing and compile-time checking. 


#### For example... 
```typescript
//TS static typing:
function HelloWorld(): JSX.Element {
    return <h1>Hello, World!</h1>;
}

//JS dynamic typing:
function HelloWorld() {
    return <h1>Hello, World!</h1>;
}

```

Although it may feel tedious at first, I am confident that certain aspects of debugging will hopefully become a bit quicker. While learning TypeScript, I was able to brush up on some ES6 concepts, which is always beneficial since I use a lot of arrow functions and spread operators when using React.

#### Example ES6 from my [TubeReader Project](https://www.tubereader.practicalsoftware.com/explore):
```JSX
    const selectLanguageOptions = [
        ...languageList.map(option => (
            <MenuItem key={option} value={option}>
                {option}
            </MenuItem>
        ))
    ];
```

### TypeScript VS Other Object Oriented Languages

Compared to languages like C or C++, which I recently picked up, TypeScript and JavaScript are an absolute relief. TypeScript having automatic memory management and garbage collection is a miracle after dealing with constant memory leaks.

I appreciate the language being more forgiving, which helps especially when programming larger applications. I think TypeScript feels like a middleground between Java's static typing and OOP concepts and JavaScript's flexibility.

## Athletic Software Engineering (WODs)

On a different note, the WODs (Workout of the Day) seem relatively intimidating. Having to program with a timer will be stressful at first, but I am confident in my programming ability to finish the task in a good time.

Hopefully with each one, I can either succeed with relative ease, or miss the mark but learn something new in the process. I think the WODs and overall learning style will be beneficial for technical interviews and during everyday coding.

All in all, even though this new kind of learning feels a little unorthodox, I’m optimistic about it. Not only does it push me out of my comfort zone, but it also seems like good preparation for the high-pressure coding situations with deadlines impending. 

It’s all about adapting, and **embracing the challenge**, despite the hardships.
