# Youth-Can_Project-MartinaMilosheva-FE21

## Table of Contents 
1. [Instructions of installation](#installation)
2. [Description](#brief)(#description)
3. [Usage](#usage)

## Instructions on how to install the project locally
To get started with this project, follow these steps:
1. Clone the repository with this command in VS Code Terminal, or another program that you use for writing code.
git clone https://git.brainster.co/Martina.Milosheva-FE21/youth-can_martinamilosheva-fe21.git .
2. Open the project in your browser.

## Brief of the project
This project is a landing page for the Youth Can association, developed for marketing and promotional purposes. Built using SASS combined with Bootstrap, the page is structured for both responsiveness and visual appeal. The Hero Banner at the top features an engaging image with a prominent title and a call-to-action button that links to their Instagram page. Below, the About Us section provides a detailed overview of the organization's goals, while visually impactful cards highlight the association's mission and vision.

Further down, the Testimonials section, designed with Bootstrap, showcases feedback from youth participants who have been part of various association-led projects. The second half of the page introduces the team behind the organization and highlights their past activities.

At the very bottom of the page, there is a footer that offers important information such as the association's working hours, location, and a contact form where users can reach out or express interest in joining. The form is validated with JavaScript to ensure that all fields are properly filled out. If the form is incomplete or incorrect, an error message will appear, and submission will be blocked until the issue is resolved. This ensures that users submit accurate information, making the page both interactive and user-friendly.This project serves as both an informative and interactive web presence for the Youth Can association.

## Description of the structure of the project
This project is structured using SASS to ensure a clean, maintainable, and scalable codebase. The SASS folder is organized into three main subfolders: Abstracts, Components, and Core.

Abstracts: This folder contains the foundational building blocks of the project:
    _mixins.scss: Here, I’ve written reusable code for patterns that occur multiple times across the project. By using mixins and extends, I avoid repetition and make the codebase more DRY (Don't Repeat Yourself), keeping it concise and efficient.

    _variables.scss: This file holds variables for common design elements like colors, font-sizes, spacing (margins and padding), and more. The use of variables makes it easy to update styles across the entire project by changing a single value in one place, ensuring consistency and simplifying future modifications.

Components: The Components folder contains code for individual sections of the page, written in a modular way. Each section of the website (such as the hero banner, about us, testimonials, etc.) is organized in its own file, making it easy to locate and modify specific components when necessary. This structure ensures that the code for each section is self-contained and straightforward to manage.

Core: The Core folder holds the base styles that apply globally across the entire page. This includes common elements such as headings, paragraphs, and basic CSS resets to ensure a consistent starting point for all pages. The core styles set up a clean and consistent design foundation for the project, allowing for easy customization and expansion.

This structured SASS approach helps keep the project organized, scalable, and easy to maintain, making future updates or changes more efficient.

## Usage of the project
To use this project, simply clone the repository and open the HTML file in your browser. The landing page is fully responsive and optimized for desktop, tablet, and mobile views. You can customize the content, such as the text in the "About Us" section, the testimonials, and the team information, by editing the respective sections in the HTML file. The page also includes links to social media, like the association’s Instagram page, which can be modified if needed. For further customization, you can edit the SASS and Bootstrap files to adjust the design and layout to your preferences.