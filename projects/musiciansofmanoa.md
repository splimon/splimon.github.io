---
layout: project
type: project
image: img/musiciansofmanoa-logo.png
title: "Musicians of Manoa"
date: 2024-12-20
published: true
labels:
  - Web Development
  - Next.JS
  - PostgreSQL
  - React
  - Prisma
summary: "Musicians of Manoa is a web application that connects UH Manoa students with shared musical interests and compatible abilities, enabling them to create profiles, discover jam sessions, and collaborate musically."
---
<div style="display: flex; justify-content: space-around; margin: 0 0 0 10px;">
    <img width="800px" src="/img/landing.png" alt="Landing Page">
  </div>
  <p style="display: flex; justify-content: space-around;><em>The landing page of the 'Musicians of Manoa' web application.</em></p>

## Project Overview
Musicians of Manoa is an application that brings UH Manoa students together and allows students to find other people with similar musical interests and compatible music abilities. In the application, students can log in and create a profile indicating their musical tastes, their musical capabilities, and their musical goals (from occasional, informal jam sessions to performing bands). The application was developed using **Next.js**, **React**, **Prisma**, and **PostgreSQL**, with a focus on creating a user-friendly and dynamic interface. It was primarily coded in **TypeScript**, and the UI was styled using **CSS**. Musicians of Manoa was deployed using **Vercel**, and the live version is available <a href="https://musicians-of-manoa.vercel.app/">here.</a>

## My Contributions
I worked on a team of five people to complete this project. Each of us had a specific role in building this website. My main contributions were in building the Jam Information Page, Jam Search Page, and Attending Jams Page, as well as implementing their functionalities. 

Our project timeline spanned four weeks, and every week, our team completed specific milestones. For <a href="https://github.com/orgs/musicians-of-manoa/projects/1">Milestone 1</a>, I focused on building the Jam Information Page. This page allows users to add Jam Information about an upcoming jam musical session they would like to share for other users on the website to view. This form connected to a PostgreSQL database so all the inputted data could be stored and displayed onto a card in the Jam Search Page.

<div style="display: flex; justify-content: space-around; margin: 5px 0;">
    <img width="800px" src="/img/jam-information.png" alt="Jam Information Page">
  </div>

Next, during <a href="https://github.com/orgs/musicians-of-manoa/projects/3">Milestone 2</a>, I focused on building the Jam Search Page. This page displays all of the current posted jam sessions hosted by other users. Each user can choose to attend this jam by clicking on the “Attend Jam” button, which saves all the jam information pertinent to the specific jam session and redirects the user to the Attending Jams Page.

<br />
<div style="display: flex; justify-content: space-around; margin: 5px 0;">
    <img width="800px" src="/img/search-jams.png" alt="Jam Search Page">
  </div>
<br />

Finally during <a href="https://github.com/orgs/musicians-of-manoa/projects/5">Milestone 3</a>, I focused on building the Attending Jams Page. This page contains all of the jam sessions the current logged-in user has saved. The user can also delete this Jam session if they decide to not attend or if it's a past jam session.

<br />
<div style="display: flex; justify-content: space-around; margin: 5px 0;">
    <img width="800px" src="/img/attending-jams.png" alt="Attending Jams Page">
  </div>
<br />
## Project Takeaways
This project was my first time developing a full-stack web application, and I learned a lot of valuable insights into building a website from the ground up. I enhanced my skills in database integration and refined my proficiency in React, CSS, and TypeScript. This experience deepened my understanding of how back-end and front-end components interact and highlighted the importance of designing intuitive and purposeful user experiences.

To access the project’s Github Organization Page, please visit this <a href="https://musicians-of-manoa.github.io/">link.</a>
