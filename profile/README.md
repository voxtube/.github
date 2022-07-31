## TABLE OF CONTENTS
- [1. Introduction](#1-introduction)
- [2. What is VoxTube](#2-what-is-voxtube)
- [3. Why VoxTube](#3-why-voxtube)
- [4. VoxTube Features](#4-voxtube-features)
- [5. VoxTube Features In Progress](#5-voxtube-features-in-progress)
- [6. Links](#6-links)
- [7. Tech Stack](#7-tech-stack)
- [8. Tech Stack](#8-infrastructure)
- [9. CMS](#9-cms)
- [10. References](#10-references)
- [11. Conclusion](#11-conclusion)

## **`1. Introduction`**
VoxTube is 'a' video streaming platform, developed by Ahmad Muhammad for the planet Scale Hackathon, VoxTube is video streaming platform made for content creators to reach their target audience.

VoxTube backend was built with Nestjs and typescript whereas the streaming module is written in golang, the assets(videos, images and others) are being stored in cloudinary.

Most of us already know that nodejs runs on a single thread node, and it can't handle intensive/heavy cpu workload/activities as it will impact the server resource and memory, the effect might not be notice especially in local host where you are the only user but in production where it might get thousands of requests per second,  because of that go lang was used for handling the pictures and videos upload / live-streaming (in progress)

## **`2. What is VoxTube`**
VoxTube is a video streaming platform made for content creators.

## **`3. Why VoxTube`**
Thousands of content creators on the internet don't have the chance to reach their targeted number of audience due to competition by popular content creators in the internet.

Due to that factor, New content creators find it difficult to be noticed by their audience since they are not known and not popular. Most of these content creators usually give up and quit along the way.

VoxTube makes it possible for new content creators to be noticed, and reach their audience by boosting creators' contents on the platform ensuring it reaches larger number of audience even if you are a newbie creator.

VoxTube is not just for content creators but also for Movie Makers, Tutorials, Comedy Skits, Fun Facts, Entertainment and more.

## **`4. VoxTube Features`**
VoxTube is made up of the following features:

![voxtube.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1659274208974/ewShu4VyH.png)
- User
  - Authentication
  - Watch Videos

  - Studio
    ![Screenshot from 2022-07-31 14-24-10.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1659274391241/8ewNPQPRW.png)

    The studio section let a user create a channel and manage them.

    - Create a new channel
    - Manage Channel
    - Delete Channel
    - Upload videos to a channel
    - Create a serie(collection) and upload to it.
    - Published/unpublished contents
  - Channels

![channels list.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1659274674327/lCvnF-HiU.png)
- Series

- Admin
  ![voxtube-menu.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1659273773337/DP9ZrPBC4.png)

  > ```Provided your role is Admin the dashboard button will appear above as seen in the above url, else the dashboard button does not show, if you want to see the admin dashboard and explore it you can comment below with your username let me make your account admin/mod.```
  - Dashboard(basic statistics)

![dashb.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1659276597587/7jaJiq7wh.png)
- View Users
- Change Role [Super, Admin, Mod, User]
- Ban/suspend user
- Lists of Channels
- View Reported Contents

## **`5. VoxTube Features In Progress`**
Due to the limited time frame for the hackathon, some features are not fully implemented or are in progress, some of them are:
- Live Streaming
- Series/Collection
- Buy Videos(A content creator can decide a resource/content is free, so the user will have to pay to unlock/access that resource to support the creator)
- Donate to a creator

## **`6. Links`**
- [VoxTube URL](https://voxtube.netlify.app)
> Note: you cant explore the admin section if you are not an admin/mod, you can comment below with your user name so that i can make you admin/mod to explore the section.
- [VoxTube Api Docs URL](https://voxtube.herokuapp.com/docs)
- [Github Repositories URL](https://github.com/voxtube)
- [Api Docs Url](https://voxtube.herokuapp.com/docs)

## **`7. Tech Stack`**

- [Planet Scale](https://planetscale.com/)

  Is a database for developers, scalers, creators, optimists, builders, and enterprises. It's a MySQL-compatible serverless database platform.


- [Prisma](https://prisma.com/)

  Prisma is an ORM that helps app developers build faster and make fewer errors. Combined with its Data Platform developers gain reliability and visibility when working with databases.


- [Typescript](https://www.typescriptlang.org/)

  TypeScript is a strongly typed programming language that builds on JavaScript, giving you better tooling at any scale.


- [Golang](https://golang.org/)

  Go (also called Golang or Go language) is an open source programming language used for general purpose. Go was developed by Google engineers to create dependable and efficient software.


- [Nestjs](https://nestjs.org/)

  A progressive Node.js framework for building efficient, reliable and scalable server-side applications.


- [Vuejs](https://vuejs.org/)

  Vue.js is an open-source model–view–viewmodel front end JavaScript framework for building user interfaces and single-page applications.


- [Nuxtjs](https://nuxtjs.org/)

  Nuxt.js is a free and open source JavaScript library based on Vue.js, Node.js, Webpack and Babel.js. Nuxt is inspired by Next.js, which is a framework of similar purpose, based on React.js. The framework is advertised as a "Meta-framework for universal applications".


- [Vuetify](https://vuetifyjs.com/en/)

  Vuetify is a Vue UI Library with beautifully handcrafted Material Components. No design skills required — everything you need to create amazing applications is at your fingertips.

## **`8. Infrastructure`**
- [Cloudinary](https://cloudinary.com)

  Cloudinary is a SaaS technology company, It enables users to upload, store, manage, manipulate, and deliver images and video for websites and apps.


- [Heroku](https://heroku.com)

  The VoxTube Server is hosted on heroku


- [Netlify](https://netlify.com)

  The VoxTube client(front end) is hosted in netlify

## **`9. CMS`**
I will also use this opportunity to discus CMS.
#### What is a CMS (Content Management System) ?:

A content management system, often abbreviated as CMS, is software that helps users create, manage, and modify content on a website without the need for specialized technical knowledge.

In simpler language, a content management system is a tool that helps you build a website without needing to write all the code from scratch (or even know how to code at all).

Instead of building your own system for creating web pages, storing images, and other functions, the content management system handles all that basic infrastructure stuff for you so that you can focus on more forward-facing parts of your website.

Beyond websites, you can also find content management systems for other functions – like document management.

Example of CMS such as Wordpress, Strapi, hashnode, medium, VoxTube and lot more.

[Read more on CMS](https://kinsta.com/knowledgebase/content-management-system)

## **`10. References`**
- CMS: https://kinsta.com/knowledgebase/content-management-system/

## **`11. Conclusion`**
Thanks to [PlanetScale](https://planetscale.com) and [HashNode](https://townhall.hashnode.com/planetscale-hackathon) for organising this great hackathon.