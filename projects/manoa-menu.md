---
layout: project
type: project
image: img/manoa-menu/mm-logo.png
title: "Mānoa Menu"
date: 2024
published: true
labels:
  - Next.js
  - React
  - Node.js
  - TypeScript
  - Material UI
  - OpenAI API
  - PostgreSQL
  - Prisma ORM
  - Vercel
summary: "The Manoa Menu project is a web application designed to provide menu translations and item descriptions for international students at the University of Hawaiʻi at Mānoa."
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

<div id="projects-mm" class="container tab-pane active">
<br>

<!-- <h5 class="work-title"><strong></strong></h5> -->
<div id="hawaii-data" class="carousel slide" data-bs-ride="carousel">

<!-- Indicators/dots -->
<div class="carousel-indicators">
<button type="button" data-bs-target="#hawaii-data" data-bs-slide-to="0" class="active"></button>
<button type="button" data-bs-target="#hawaii-data" data-bs-slide-to="1"></button>
<button type="button" data-bs-target="#hawaii-data" data-bs-slide-to="2"></button>
<button type="button" data-bs-target="#hawaii-data" data-bs-slide-to="3"></button>
<button type="button" data-bs-target="#hawaii-data" data-bs-slide-to="4"></button>

</div>

<!-- The slideshow/carousel -->
<div class="carousel-inner rounded-3">
<div class="carousel-item active">
    <img src="/img/manoa-menu/menu-ha-en.png" alt="Manoa Menu HA" class="d-block" style="width:100%">
</div>
<div class="carousel-item">
    <img src="/img/manoa-menu/menu-ha-jp.png" alt="Manoa Menu HA" class="d-block" style="width:100%">
</div>
<div class="carousel-item">
    <img src="/img/manoa-menu/map-hours.png" alt="Manoa Menu Map & Hours" class="d-block" style="width:100%">
</div>
<div class="carousel-item">
    <img src="/img/manoa-menu/menu-cc-en.png" alt="Manoa Menu CC" class="d-block" style="width:100%">
</div>
<div class="carousel-item">
    <img src="/img/manoa-menu/menu-cc-jp.png" alt="Manoa Menu CC" class="d-block" style="width:100%">
</div>
</div>

<!-- Left and right controls/icons -->
<button class="carousel-control-prev" type="button" data-bs-target="#hawaii-data" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" style="filter: invert(100%);"></span>
</button>
<button class="carousel-control-next" type="button" data-bs-target="#hawaii-data" data-bs-slide="next">
    <span class="carousel-control-next-icon" style="filter: invert(100%);"></span>
</button>
</div>
</div>

<br>
<br>

### **Team Homepage**: [https://manoa-menu.github.io/]

<br>

### **Deployed Application**: [Manoa Menu](https://manoa-menu.vercel.app)

<br>

## Overview

The Manoa Menu project is a web application designed to provide menu translations and item descriptions for international students at the University of Hawaiʻi at Mānoa. The application also allows users to view dining menus, find dining locations & hours, manage their favorite items, and get recommendations based on their preferences.

<br>

## Concepts Used/Learned

### Frontend Development
- **React and Next.js**: Utilized for building the user interface and managing the application state.
- **React Bootstrap**: Used for styling and responsive design.
- **TypeScript**: Ensured type safety and improved code quality.
- **Material UI**: Used for some pages for additional UI Components
- **Webscraping**: Essential for scraping menus that lack an API

<br>

### Backend Development
- **Next.js API Routes**: Implemented for server-side logic and data fetching.
- **Prisma ORM**: Used for database interactions with PostgreSQL.
- **OpenAI API**: Integrated for generating menu translations in real time.

<br>

### Testing and Quality Assurance
- **Playwright**: Employed for end-to-end testing.
- **ESLint**: Ensured code quality and consistency.

<br>

### Deployment:

- **Vercel**: Learned key concepts about the Vercel CLI, deployment options, error logs, etc.

## My Role

As a fullstack developer, I was responsible for several key features of the application:

- **Developed the [Menu](https://manoa-menu.vercel.app/menu) page end-to-end**: 
  - Created a responsive and easy-to-read menu interface for multiple languages
  - Used [JS-DOM](https://www.npmjs.com/package/jsdom) to parse the University's website for current accurate menu data (Campus Center)
  - Used [PDF-Parse](https://www.npmjs.com/package/pdf-parse) to extract menu data from the University's online weekly PDF
  - Constructed API menu routes to get and check for newer menu versions
  - Engineered AI prompts for menu translations and descriptions, fetched with the [OpenAI API](https://platform.openai.com/docs/overview) for customizable JSON-structured data returns.
  - 
- **Developed the [Dining Locations and Hours](https://manoa-menu.vercel.app/maps) page**:
  - Implemented a convenient and responsive page to view dining locations and their hours
  - Used the Google Maps API for map embeds
  - Added an 'Get Directions' button for each location, which will directly guide users using their default maps app

<br>

## Teamwork and Leadership

- Coordinated and worked with all developers on tasks and deadlines
- Reviewed code and gave ideas for improvement
- Lead the team's weekly meetings with an overall agenda per meet
