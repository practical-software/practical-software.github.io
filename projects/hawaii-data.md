---
layout: project
type: project
image: img/hawaii-data/HOD.jpg
title: "Hawaii Open Data Explorer"
date: 2024
published: true
labels:
  - Next.js
  - React
  - Node.js
  - TypeScript
  - shadcn/ui
  - Radix UI
  - Tailwind
  - OpenAI
  - Express
summary: "A Next.js web application designed to simplify and enhance the discovery and analysis of publicly accessible data in Hawaii."
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
<div id="hawaii-data" class="carousel slide" data-bs-ride="carousel">

<!-- Indicators/dots -->
<div class="carousel-indicators">
<button type="button" data-bs-target="#hawaii-data" data-bs-slide-to="0" class="active"></button>
<button type="button" data-bs-target="#hawaii-data" data-bs-slide-to="1"></button>
<button type="button" data-bs-target="#hawaii-data" data-bs-slide-to="3"></button>
<button type="button" data-bs-target="#hawaii-data" data-bs-slide-to="4"></button>
<button type="button" data-bs-target="#hawaii-data" data-bs-slide-to="5"></button>

</div>

<!-- The slideshow/carousel -->
<div class="carousel-inner rounded-3">
<div class="carousel-item active">
    <img src="/img/hawaii-data/OOL-Main.png" alt="Hawaii Open Data Main Page" class="d-block" style="width:100%">
</div>
<div class="carousel-item">
    <img src="/img/hawaii-data/OOL-Info.png" alt="Hawaii Open Data Dataset Info" class="d-block" style="width:100%">
</div>
<div class="carousel-item">
    <img src="/img/hawaii-data/OOL-Table.png" alt="Hawaii Open Data Dataset Table" class="d-block" style="width:100%;">
</div>
<div class="carousel-item">
    <img src="/img/hawaii-data/OOL-Graph.png" alt="Hawaii Open Data Dataset Graph" class="d-block" style="width:100%;">
</div>
<div class="carousel-item">
    <img src="/img/hawaii-data/OOL-Chat.png" alt="Hawaii Open Data AI Chat" class="d-block" style="width:100%;">
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

### **Note**: This project was a finalist in the 2024 Hawaii Annual Code Challenge. 

#### Deployed Application: [Hawaii Open Data Explorer](https://ool-frontend.vercel.app)

## Overview

The Hawaii Open Data Explorer is a comprehensive tool for exploring datasets provided by various government agencies in Hawaii. The application allows users to search, filter, and visualize data in an intuitive and user-friendly manner.

## Concepts Used/Learned

### Frontend Development
- **React and Next.js**: Utilized for building the user interface and managing the application state.
- **TypeScript**: Ensured type safety and improved code quality.
- **Tailwind CSS**: Applied for styling the components and creating a responsive design.
- **Shadcn/ui**: Used for building responsive and clean user interfaces
- **Axios**: Employed for making HTTP requests to the backend API.

### Backend Development
- **OpenAI API**: Integrated for generating dataset suggestions and answering user queries.
- ***Next.js* Environment Variables**: Managed sensitive information using `.env` files.

## My Role

As a frontend developer, I was responsible for several key features of the application:

- **Recent Datasets**: Implemented functionality to track and display recently accessed datasets.
- **Graph Downloading**: Enabled users to download visualized graphs as images.
- **Card Design**: Designed dataset cards to display essential information such as title, description, and tags.
- **Dataset Bookmarking**: Added bookmarking feature to datasets using the browser's local storage.
- **Sorting and Filtering**: Developed sorting and filtering mechanisms to help users find relevant datasets.
- **Info Tab**: Created an information tab to provide detailed insights about selected datasets.
- **Search for Datasets**: Implemented a search feature to allow users to find datasets quickly.
- **Help & Tips**: Added a help button and several tooltips to guide users through the application.

## Teamwork and Learning

This was my first group coding project, and I learned a lot about working in a team. I gained experience in:

- **Collaboration**: Working closely with team members to achieve common goals.
- **Version Control**: Using GitHub for version control, including branching, pull requests, and merge conflicts.
- **Code Reviews**: Participating in code reviews to ensure code quality and consistency.
- **Communication**: Effectively communicating with team members to resolve issues and share progress.

I was initially unfamiliar with some GitHub concepts, but through this project, I became more comfortable with using GitHub for collaboration and version control.

## Conclusion

The Hawaii Open Data Explorer project was a valuable learning experience that allowed me to develop my skills in frontend development, teamwork, and using GitHub for version control. I am proud of the features I implemented and the contributions I made to the project.