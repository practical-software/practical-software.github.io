---
layout: essay
type: essay
title: "Final Project Idea 2"
# All dates must be YYYY-MM-DD format!
date: 2024-11-06
published: true
labels:
  - Software Engineering
  - Nextjs
  - Node.JS
---

# Project: CC Menu Translation
Idea by: Adam Graham, Eric Kim, Justin Sumiye, Brendan Kuwabara, Christian Iha

## Overview
*The problem:* International UHM students who are not fluent in English may struggle to read the Campus Center 
cafeteria menu, especially since they offer many local and western dishes that are not self-explanatory. Simply 
using Google Translate on each week's menu is tedious and often inaccurate.

*(Project will translate to Japanese since most international students are from Japan)*

*The solution:* The web application will automatically translate the cafeteria menu from English to Japanese, ensuring accurate and clear understanding for international students. It will also provide additional descriptions for menu items that are culturally unfamiliar, offering a more user-friendly experience. Students can easily access the translated menu without needing to log in, while those who log in can save favorite items and track if those items appear on the current week's menu.

## Approach
* **Frontend (Next.js):**
  * User-friendly menu and dashboard page
  * Clear presentation of translated menus.
  * Simple web scrape of pdf menu ([PDF-Parse](https://www.npmjs.com/package/pdf-parse) or [PDF2JSON](https://www.npmjs.com/package/pdf2json))
* **Backend (Prisma ORM & PostgreSQL):**
  * PostgreSQL database for user information and favorite menu items
  * OpenAI calls to help describe the menu items

## Use Case Ideas
* **No Login Required:** Students can view the translated menu without needing to login.
* **Descriptive Menus:** The menu will provide descriptions for menu items that are not self explanatory.

## Beyond the basics
* **Favorite Items (Login Req.):** Add favorite menu items that can be edited in dashboard page
* **Favorite Menu Check (Login Req.):** At a glance view if favorite menu items are on this weeks menu 
* **Popular Items:** View a table of popular menu items sorted by number of favorites (desc. order)

