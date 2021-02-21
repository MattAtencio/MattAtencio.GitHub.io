## Enhancement Two: Algorithms and Data Structures

**Overview**

The artifact I have chosen to use for my first enhancement, software design and engineering, is a full stack website using the MEAN stack. This application is a travel website for reviewing and booking trips. The site includes a frontend UI, an admin SPA site, a MongoDB Database, and APIs to support data querying, data manipulation and user authentication. I created this project at the end of 2020 for my CS-465 Full Stack Development I course.

I am using this artifact in my ePortfolio to show that I not only understand each individual component, but that I also understand how they all work together. I will be using this single artifact for each enhancement in the class to showcase how each piece fits together in the stack. For the purpose of this enhancement, I will be creating new data models and creating new queries for the APIs to utilize. In my travlr application I created 2 new data models for “Blog Posts” and “Testimonials”. I also added queries for basic GET functionality as well as some more targeted queries such as “most recent” and “return X number of records”. These changes help to improve the artifact by enabling the home page and the “news” page to load data dynamically.

**Reflection**

I originally, was going to also create models for “News Posts” and “Vacation Tips”, but after reviewing the structure of the website and how these were used, I found that these objects and “Blog Posts” all had the same structure. I combined them into 1 object and added a “category” field to identify if the blog posts were news posts or vacation tips. This also leaves me the ability to add new categories in the future. When I was creating the APIs and queries, I was originally going to make individual calls for “get 3 most recent” and “get 5 most recent” blog posts. After thinking this through for a while I decided to just make one API call where you pass the number of records you want as a parameter. This makes it incredibly easy to scale. The API will accept any number you pass it, and you would just need to modify the page from say 3 to 5 if you wanted to display more records.  The biggest challenge I faced was running requesting data form multiple API calls on a page load. Prior to this all my pages only needed one call, so I had to think about how to manage the pages so they would wait for responses before proceeding to next steps.

<br>

**Link to Repository**

[Enhancement Two Repository](https://github.com/MattAtencio/cs465-fullstack/tree/portfolio/Software_Engineering)

<br>

**Porfolio Links**<br>
* [Professional Self-Assessment](https://MattAtencio.github.io/index.html)<br>
* [Refinement Plan & Code Review](https://MattAtencio.github.io/CodeReview.html)<br>
* [Enhancement One](https://MattAtencio.github.io/EnhancementOne.html)<br>
* [Enhancement Two](https://MattAtencio.github.io/EnhancementTwo.html)<br>
* [Enhancement Three](https://MattAtencio.github.io/EnhancementThree.html)


