---
layout: project
type: project
image: images/constrained-cooking.PNG
title: Constrained Cooking
permalink: projects/simple-circuit-analyzer
# All dates must be YYYY-MM-DD format!
date: 2018-05-04
labels:
  - Javascript
  - Semantic UI
  - Design Patterns
  - Meteor
  - React
summary: A recipe searching app designed for UHM students
---


In ICS314, my group worked on developing an application tailored for students dorming on campus at UHM.  We named our application ["Constrained Cooking"](https://constrainedcooking.github.io/).  This app would allow a user upload, and search for recipes. The app would also allow a vendor to upload their inventory onto the application, and users to search through a vendor's wares.  Profile creation was also included in the app, allowing a user to fill in details about themselves.

My contribution to the project was in the recipe database.  I defined the recipe database, created the "Add Recipe" that entered information into the database, as well as made the foundation for the "View Recipe" page (the formatting was handled by another member).  I also created the vendor database and gave it basic functionality (another member expanded its capabilities).  

In order to create the code for the "Add Recipe" page, I needed to remake a large amount of code from our previous class assignments.  Due to the incompatibility of the database structure and the autoform package (autoform wasn't built to handle arrays well), I had to use a different method to handle creating entries that used states.  By using a state, I was able to handle the arrays and objects and enter them into the database correctly.

<img class="ui image" src="https://constrainedcooking.github.io/images/viewrecipepage.PNG">
