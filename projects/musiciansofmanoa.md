---
layout: project
type: project
image: img/musiciansofmanoa-logo.png
title: "Musicians of Manoa"
date: 2024-12-20
published: true
labels:
  - Next.JS
  - PostgreSQL
  - React
summary: "Musicians of Manoa is a web application that connects UH Manoa students with shared musical interests and compatible abilities, enabling them to create profiles, discover jam sessions, and collaborate musically."
---
<div style="display: flex; justify-content: space-around;">
    <img src="/img/landing-1.png" alt="Landing Page 1">
  </div>
  <div style="display: flex; justify-content: space-around;">
    <img src="/img/landing-2.png" alt="Landing Page 2">
  </div>

## Project Overview
Musicians of Manoa is an application that brings UH Manoa students together and allows students to find other people with similar musical interests and compatible music abilities. In the application, students can log in and create a profile indicating their musical tastes, their musical capabilities, and their musical goals (from occasional, informal jam sessions to performing bands). This application was deveveloped using **Next.Js**, **React**, **Prisma**, and **PostgreSQL** for a UI-friendly and reactive interface, and was primarily coded in **Typescript** and most of the UI was designed with **CSS**. Musicians of Manoa was deployed using **Vercel**, and the live version is available <a href="https://musicians-of-manoa.vercel.app/">here.</a>

## My Contributions
I worked on a team of five people to complete this project. Each of us had a specific role in building this website. My main contributions were in building the Jam Information Page, Jam Search Page, and Attending Jams Page, as well as implementing their functionalities. 

Our project timeline spanned four weeks, and every week, our team completed specific milestones. For <a href="https://github.com/orgs/musicians-of-manoa/projects/1">Milestone 1</a>, I focused on building the Jam Information Page. This page allows users to add Jam Information about an upcoming jam musical session they would like to share for other users on the website to view. This form connected to a PostgreSQL database so all the inputted data could be stored and displayed onto a card in the Jam Search Page.

<div style="display: flex; justify-content: space-around;">
    <img src="/img/jam-information.png" alt="Jam Information Page">
  </div>

Next, during <a href="https://github.com/orgs/musicians-of-manoa/projects/3">Milestone 2</a>, I focused on building the Jam Search Page. This page displays all of the current posted jam sessions hosted by other users. Each user can choose to attend this jam by clicking on the “Attend Jam” button, which saves all the jam information pertinent to the specific jam session and redirects the user to the Attending Jams Page.

<div style="display: flex; justify-content: space-around;">
    <img src="/img/search-jams.png" alt="Jam Search Page">
  </div>

Finally during <a href="https://github.com/orgs/musicians-of-manoa/projects/3">Milestone 5</a>, I focused on building the Attending Jams Page. This page contains all of the jam sessions the current logged-in user has saved. The user can also delete this Jam session if they decide to not attend or if it's a past jam session.

<div style="display: flex; justify-content: space-around;">
    <img src="/img/attending-jams.png" alt="Attending Jams Page">
  </div>

## Project Takeaways
This project was my first time developing a full-stack web application, and I learned a lot of valuable insights into building a website from the ground up. I enhanced my skills in database integration and refined my proficiency in React, CSS, and TypeScript. This experience deepened my understanding of how back-end and front-end components interact and highlighted the importance of designing intuitive and purposeful user experiences.

To access the project’s Github Organization Page, please visit this <a href="https://musicians-of-manoa.github.io/">link.</a>