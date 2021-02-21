## Enhancement Three: Databases

**Overview**

The artifact I have chosen to use for my third enhancement, software design and engineering, is a full stack website using the MEAN stack. This application is a travel website for reviewing and booking trips. The site includes a frontend UI, an admin SPA site, a MongoDB Database, and APIs to support data querying, data manipulation and user authentication. I created this project at the end of 2020 for my CS-465 Full Stack Development I course.

I am using this artifact in my ePortfolio to show that I not only understand each individual component, but that I also understand how they all work together. I will be using this single artifact for each enhancement in the class to showcase how each piece fits together in the stack. For the purpose of this enhancement, I will be creating new database tables to support the new data models and apis created in my last enhancement. These changes help to improve the artifact by creating more “object” data that can be called and loaded dynamically without code changes.

**Reflection**

I originally, was going to also create models for “News Posts” and “Vacation Tips”, but after reviewing the structure of the website and how these were used, I found that these objects and “Blog Posts” all had the same structure. I combined them into 1 object and added a “category” field to the objects in the database to tell if the blog posts were news posts or vacation tips. This also leaves me the ability to add new categories in the future. This was a major benefit of using a NoSQL database. This change was straight forward, so no challenges. I did look into adding some stored procedures(scripts) to the database but found it easier to add this functionality to the APIs instead.

<br>

**Link to Repository**

[Travlr Project Repository](https://github.com/MattAtencio/cs465-fullstack/tree/portfolio/Software_Engineering)

<br>

**Porfolio Links**<br>
* [Professional Self-Assessment](https://MattAtencio.github.io/index.html)<br>
* [Refinement Plan & Code Review](https://MattAtencio.github.io/CodeReview.html)<br>
* [Enhancement One](https://MattAtencio.github.io/EnhancementOne.html)<br>
* [Enhancement Two](https://MattAtencio.github.io/EnhancementTwo.html)<br>
* [Enhancement Three](https://MattAtencio.github.io/EnhancementThree.html)

