---
layout: project
type: project
image: img/tubereader/logo0.png
title: "TubeReader (WIP)"
date: 2024
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
summary: "An AI-powered SAAS that transforms YouTube videos into customizable, high-quality blog articles with various content options and visibility settings."
---

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
<script src="https://kit.fontawesome.com/5d0479de92.js" crossorigin="anonymous"></script>


<style>
    .carousel-inner {
        overflow: hidden;
    }

    .carousel-inner .carousel-item {
        transition: transform 0.6s ease-in-out;
    }
</style>

<div id="projects-worddough" class="container tab-pane active">
<br>

<!-- <h5 class="work-title"><strong></strong></h5> -->
<div id="tubereader" class="carousel slide" data-bs-ride="carousel">

<!-- Indicators/dots -->
<div class="carousel-indicators">
<button type="button" data-bs-target="#tubereader" data-bs-slide-to="0" class="active"></button>
<button type="button" data-bs-target="#tubereader" data-bs-slide-to="1"></button>
<button type="button" data-bs-target="#tubereader" data-bs-slide-to="2"></button>
</div>

<!-- The slideshow/carousel -->
<div class="carousel-inner rounded-3">
<div class="carousel-item active">
    <img src="/img/tubereader/TubeReader-Explore.png" alt="TubeReader Explore Page" class="d-block" style="width:100%">
</div>
<div class="carousel-item">
    <img src="/img/tubereader/TubeReader-Dashboard.png" alt="TubeReader Dashboard" class="d-block" style="width:100%">
</div>
<div class="carousel-item">
    <img src="/img/tubereader/TubeReader-Generate.png" alt="TubeReader Generate Article" class="d-block" style="width:100%;">
</div>
</div>

<!-- Left and right controls/icons -->
<button class="carousel-control-prev" type="button" data-bs-target="#tubereader" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" style="filter: invert(100%);"></span>
</button>
<button class="carousel-control-next" type="button" data-bs-target="#tubereader" data-bs-slide="next">
    <span class="carousel-control-next-icon" style="filter: invert(100%);"></span>
</button>
</div>
</div>

<br>
<br>

### **Note**: TubeReader's Landing and About page are incomplete and are currently being worked on.  

<br>

###### TubeReader is an AI tool designed to convert YouTube videos into well-structured blog articles. It offers a range of customization options to tailor the generated content to specific needs, making it ideal for developers, creators, and everyday users looking to enhance their content strategy.

<br>

## Key Features

- **Customizable Article Generation**: Choose from multiple options for title, font, tone, theme, length, and language.

- **Article Tone Adjustment**: Select the tone of the generated articles to match your brand or audience.

- **Public, Unlisted, and Private Options**: Control the visibility of generated articles based on your preferences.

- **Batch Uploading**: Soon to be available, allowing for multiple videos to be processed simultaneously.

- **Support for Longer Videos**: Upcoming feature to handle extended video content efficiently.

## APIs Used

- **YouTube Transcript API (Self-Hosted with Heroku & Flask)**: Provides the text transcripts of YouTube videos, which are essential for converting spoken content into written articles. 
  
- **[OpenAI Completions API](https://platform.openai.com/docs/overview)**: Powers the content generation and enhancement of articles using OpenAI's flagship GPT-4o model. It also aids in evaluating the appropriateness of custom article titles to ensure they are suitable for most ages.

- **[YouTube Data V3](https://developers.google.com/youtube/v3)**: Retrieves detailed information about YouTube videos, such as titles, descriptions, and thumbnail images, which aids in accurately representing and summarizing video content.
  
- **[UserCheck API](https://docs.usercheck.com/)**: Checks email addresses to identify and filter out disposable email addresses, ensuring that user registrations are valid.

<br>
<br>

[Dashboard](https://www.tubereader.practicalsoftware.com/dashboard/) (Requires Login) and [Explore](https://www.tubereader.practicalsoftware.com/explore/) pages are dynamically rendered with React using Material UI, Material UI X, and SwiperJS. 

The React applications show an understanding of commonly used React hooks, component composition, and state management. 

Additionally shows knowledge of functional programming in JavaScript.


<br>

### **React Hook Usage:**

- **`useState`**: Manages local state within functional components for various aspects such as pagination (e.g., `pageSize`, `page`), article list (`rows`), row modes (`rowModesModel`), modal visibility (`open`), deletion state (`delRow`), alert messages (`alertOpen`, `alertType`, `alertMessage`), and screen responsiveness (`isMobile`).

- **`useEffect`**: 
  - Fetches initial data (e.g., article counts, language and category lists) when the component mounts.
  - Updates the displayed articles and pagination based on filter criteria and pagination index.
  - Handles resizing and scroll events to adjust the component's layout and behavior.

- **`useRef`**: 
  - Manages references to DOM elements for scrolling and focusing.

#### React Hook Usage Example:
```JSX
const targetRef = [useRef(null), useRef(null)];

useEffect(() => {
    // Iterate through each reference in targetRef
    targetRef.forEach((ref, index) => {
        if (ref.current) {
            // Scroll the referenced element into view smoothly
            ref.current.scrollIntoView({ behavior: 'smooth', block: 'start' });
            // Adjust the scroll position slightly after scrolling into view
            const scrollOffset = index === 0 ? -5 : -8;
            window.scrollBy({ top: scrollOffset, behavior: 'smooth' });
        }
    });
// eslint-disable-next-line react-hooks/exhaustive-deps
}, [index]);


```

<br>

## Live Demo:

To try demo, please contact **justin@practicalsoftware.com** for a trial license key.

## Public GitHub Repo (Dashboard & Explore)

[TubeReader Public Repo](https://github.com/Practical-Software/TubeReader-Public)



