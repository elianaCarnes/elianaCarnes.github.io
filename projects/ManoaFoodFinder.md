---
layout: project
type: project
image: img/manoalogo.jpg
title: "Manoa Food Finder"
date: 2025-13-07
published: true
labels:
  - Typescript
  - PostgreSQL
summary: "A typescript based application where students can view what food locations are nearby and vendors can create posts to advertise their location"
---

<img width="800px" src="/img/mffhome-page.png">

The Manoa Food Finder app was designed to help students and faculty find food options near the University of Hawaii campus. Our app allows for users to view real-time vendor postings, hours and nearby locations. By placing all the information in one place we hope to provide an application that allows for users to find locations to eat quickly, within the time period of their breaks between classes. We implemented three different types of accounts, each capable of different actions within the site. These three categories are users, vendors and admins. Users are capable of navigating the site and viewing all the features such as the homepage, map, and vendor postings. Vendors have the same accessibility as users, but they are also capable of making, altering and deleting their posts. Admins are able to delete all vendor posts, edit all vendor posts and view all accounts and listings within the site through the admin page. Through these three types of accounts we allow users to view advertisements from restaurants near them, and find their hours and location easily. 

## My Contributions 
My contributions to the Manoa Food Finder application were primarily building the database and implementing the vendor posts feature. I created and managed the database with PostgreSQL, which ensured that vendors could create and manage their own posts and that any new accounts registered were properly added within the right category. Using Prisma as the ORM to define the VendorPost model, which included fields for location name, hours, address, original poster and the content of the post, we were able to display vendor posts to the postings page. The original poster was saved as a string tied to the vendor's email address, which allowed for vendors to be able to edit and delete their own posts. On the frontend of the vendor post feature, I created a page that displayed all vendor posts, this was made as a react component using Next.js app router. The form itself was made with React Bootstrap for the user interface, and Yup for validation. These features allowed for real-time input and updates. 
I also created a page accessible from the site main navigation bar called community feedback, which was a form that allowed logged in users to submit feedback. It also contained a section of highlighted comments we received during the testing of our application. To achieve this, I created a form that linked each submission to the user's account via NextAuth, ensuring that each post was linked to their original owner for moderation purposes. Submitted data was stored in the PostgreSQL database through Prisma, where it could be reviewed in real time. This way we allow for open feedback on our site, which could be used to improve it in the future. 

## What I learned
Working on the Manoa Food Finder app has taught me a lot about collaboration in a real world development setting. Since the project was a group effort, we heavily relied on communication to ensure each person knew their role. We divided responsibilities based on our strengths, and worked together to ensure our site had a cohesive look throughout. We used issue-driven project  management to break down each task into sections that could each be completed by one developer, which was a way of organizing our project that I had just learned in ICS 314. This method helped me and my team work collaboratively and assign tasks in a more efficient way. 
In the features I implemented, like the postings and community feedback page, I learned a lot about database management and integration from the backend to the frontend. I gained experience with designing database schemas to store vendor posts and community feedback, and real time retrieval. Working on this project helped me work beyond just completing my portion of the work, and instead focus on building features that integrated with the rest of my team. 

<a href="https://github.com/manoa-food-finder" target="_blank">Manoa Food Finder on GitHub</a>
