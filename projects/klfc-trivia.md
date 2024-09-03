---
layout: project
type: project
image: img/klfc-trivia/klfclogo.png
title: "Korean Culture Day Trivia"
date: 2024
published: true
labels:
  - Vite
  - React
  - Material UI
summary: "A simple trivia quiz for the Korean Language Flagship Center's Korean Culture Day event that was held in May, 2024."
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
<div id="klfc" class="carousel slide" data-bs-ride="carousel">

<!-- Indicators/dots -->
<div class="carousel-indicators">
<button type="button" data-bs-target="#klfc" data-bs-slide-to="0" class="active"></button>
<button type="button" data-bs-target="#klfc" data-bs-slide-to="1"></button>
<button type="button" data-bs-target="#klfc" data-bs-slide-to="2"></button>
</div>

<!-- The slideshow/carousel -->
<div class="carousel-inner rounded-3">
<div class="carousel-item active">
    <img src="/img/klfc-trivia/Korean-Culture-Day-Quiz-START.png" alt="KLFC Trivia Start" class="d-block" style="width:100%">
</div>
<div class="carousel-item">
    <img src="/img/klfc-trivia/Korean-Culture-Day-Quiz-Question.png" alt="KLFC Trivia Question (NewJeans!)" class="d-block" style="width:100%">
</div>
<div class="carousel-item">
    <img src="/img/klfc-trivia/Korean-Culture-Day-Quiz-Answer.png" alt="KLFC Trivia Answer (Supernova)" class="d-block" style="width:100%;">
</div>
</div>

<!-- Left and right controls/icons -->
<button class="carousel-control-prev" type="button" data-bs-target="#klfc" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" style=""></span>
</button>
<button class="carousel-control-next" type="button" data-bs-target="#klfc" data-bs-slide="next">
    <span class="carousel-control-next-icon" style=""></span>
</button>
</div>
</div>

<br>
<br>


This project is a React-based quiz application that tests users' knowledge of Korean culture. The quiz features multiple questions with options, tracking the user's score and displaying a personalized message based on their performance. The application utilizes Material-UI components for a modern and responsive UI design. 

Key Features:
- **Dynamic Quiz Flow**: The quiz dynamically updates questions and tracks progress through React state management.
- **Immediate Feedback**: Users receive immediate feedback on their answers, enhancing learning and engagement.
- **Custom Animations**: Includes animations for transitions between questions and feedback messages using `Fade` and `Grow` components from Material-UI.

This project demonstrates the use of React hooks, component composition, and state management, along with integration of a UI library for an enhanced user experience.

## [GitHub Repo](https://github.com/Practical-Software/KLFC-Quiz)  
  

## [Live Demo](https://koreanflagship.manoa.hawaii.edu/trivia/)




