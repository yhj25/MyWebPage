---
title: "Representative Activities"
date: "2026-11-01T08:00:00"
tags: ["Representative Activities"]
title-images: 
ending-images: 
author: "yunhj25"
draft: false
---
<!-- introduction -->
Activity Name: Firebase-based Mini-Todo App Development and GitHub Actions Automated Deployment Practice/
Date of Practice: October 2026
/Status: Completed  
<!--more-->
<!-- rest of the content -->
-Purpose of Activities /
The goal was to securely create, read, update, and delete (CRUD) users' to-do items by integrating with Firebase Firestore and Auth, and to build a GitHub Actions pipeline that completes the continuous integration and deployment (CI/CD) environment by automatically deploying when the main branch is pushed.

-Role and scope of contribution/
Individual Practice Project (100% self-directed)  
Role: Implement frontend components, integrate with the Firebase SDK, build GitHub Actions workflows, and resolve permission issues

-Process of Practice and Reason for Selection /
Reason for choosing the tech stack: We adopted Firebase, a Serverless BaaS, to quickly establish user authentication and database integration without building a separate backend server.
Development process: Set up the React/Vite project environment and integrated the Firebase instance. Applied data isolation by designing Firestore's per-user structure (/users/UID/todos/TODO_ID). I created a github/workflows/pages.yml file to configure automatic build and deployment to GitHub.

-Results
Distribution site URL: [https://yhj25.github.io/mini-todo/]
GitHub 저장소: [https://github.com/yhj25/mini-todo]/
Result Description: We completed a web app that allows real-time management of individual to-do lists after signing up or logging in, and verified that deployment is automatically reflected upon commit pushes to the main branch.

-Learning Outcomes and Directions for Improvement /
What I learned (limitations): Solving the Node.js package and installation conflict (Error 1603) and Git credential issue in the Windows environment firsthand improved my overall understanding of the development and deployment environment.
Resolved the push rejection issue caused by insufficient workflow scope permissions when creating a GitHub Personal Access Token (PAT), and clearly learned the CI/CD permission hierarchy/
Improvement direction: I would like to refine the Firestore Security Rules permission settings and expand the feature to integrate the AI Translation API to refine and translate created task items in multiple languages