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


<script>
    .carousel-inner {
        overflow: hidden;
    }

    .carousel-inner .carousel-item {
        transition: transform 0.6s ease-in-out;
    }
</script>

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
<span class="carousel-control-prev-icon"></span>
</button>
<button class="carousel-control-next" type="button" data-bs-target="#tubereader" data-bs-slide="next">
<span class="carousel-control-next-icon"></span>
</button>
</div>
</div>

TubeReader is an AI tool designed to convert YouTube videos into well-structured blog articles. It offers a range of customization options to tailor the generated content to specific needs, making it ideal for developers, creators, and everyday users looking to enhance their content strategy.

## Key Features

- **Customizable Article Generation**: Choose from multiple options for title, font, tone, theme, length, and language.

- **Article Tone Adjustment**: Select the tone of the generated articles to match your brand or audience.

- **Public, Unlisted, and Private Options**: Control the visibility of generated articles based on your preferences.

- **Batch Uploading**: Soon to be available, allowing for multiple videos to be processed simultaneously.

- **Support for Longer Videos**: Upcoming feature to handle extended video content efficiently.

## APIs Used

- **YouTube Transcript API (Self-Hosted)**: Provides the text transcripts of YouTube videos, which are essential for converting spoken content into written articles. By hosting it ourselves, we ensure better control and integration within our platform.
  
- **[OpenAI Completions API](https://platform.openai.com/docs/overview)**: Powers the content generation and enhancement of articles using OpenAI's flagship GPT-4o model. It also aids in evaluating the appropriateness of custom article titles to ensure they are suitable for most ages.

- **[YouTube Data V3](https://developers.google.com/youtube/v3)**: Retrieves detailed information about YouTube videos, such as titles, descriptions, and thumbnail images, which aids in accurately representing and summarizing video content.
  
- **[UserCheck API](https://docs.usercheck.com/)**: Checks email addresses to identify and filter out disposable email addresses, ensuring that user registrations are valid.




