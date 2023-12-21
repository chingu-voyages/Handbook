# Solo Project Guide

![Team creating project backlog](./assets/SoloProject_coder.jpeg)


## Overview

The goal of the Solo Project is to help you and the Chingu team verify that
you've chosen a Tier that gives you the best chance of success in a Voyage. It
also gives you another app you can add to your portfolio.

When you are done and have submitted your Solo Project our team will 
evaluate your project and provide feedback you can use on both functionality 
as well as your UI/UX.

## Steps to Follow

```mermaid
graph LR
    A[Choose your Tier] --> B{Do you already\nhave a project?}
    B -- Yes --> C[Submit your\nSolo Project]
    B -- No --> D[Create from\nChingu Specs]
    D --> C
    C --> E[Facilitator\ngives feedback]
    E --> F((Signup for\na Voyage))
```
### 1. Choose your Tier 1️⃣-2️⃣-3️⃣

You'll first need to choose a *_tier_* that matches your 
current skill level. There are three tiers and you should select the one that 
best matches your current skill level - beginner (Tier 1), 
intermediate (Tier 2), or experienced (Tier 3). 

<details>
<summary>For Developers</summary>

| Tier | Requirements |
| :--- | :--- |
| Tier 1 - Frontend | Developers are just starting out in Web Development and have a basic understanding of: <br/><br/> - CSS <br/> - HTML <br/> - Any web development language like Javascript, PHP, Python, Ruby, etc.  <br/><br/>No frameworks or backend application servers are used in Tier 1 projects <br/><br/> Your Solo Project **_must implement_** an FE using vanilla HTML, CSS, and a scripting language like Javascript or Python.  |
| Tier 2 - Frontend | Developers should have the following skills & expertise: <br/><br/> - Have a solid foundation using intermediate HTML, CSS, & Any web development language like Javascript, PHP, Python, Ruby, etc.<br/> - Have started learning CSS preprocessors like SASS, LESS, Stylus, or TailwindCSS<br/> - Understand the importance and practice of Responsive Web Design Basics<br/> - Understand the fundamentals of how to use an API to retrieve data from a backend system<br/> - Uses a FE framework like React, Vue, Angular, etc. <br/><br/> Your Solo Project **_must implement_** an FE which written using a framework such as React, Svelte, VueJS, Django, Laravel, etc. |
| Tier 3 - Full Stack | Developers should have the following skills & expertise: <br/> - Intermediate or Advanced HTML/CSS/JavaScript/PHP/Python/Ruby/etc. and experience in a framework/library like React, Vue, Angular, etc.<br/> - Understand how to create and use API's with REST or GraphQL API<br/> - Understand how to create backend servers which implement an API of your own design using packages such as Express <br/> - Your Solo Project **_must implement_** an FE which accesses a BE server that implements an API of your own design. Optionally uses a database such as a NoSQL DBMS like MongoDB or a SQL DBMS like PostgreSQL <br/> - Your backend must include CRUD (if using a database) or POST/READ/UPDATE/DELETE (for APIs)|

</details>

<details>
<summary>For UI/UX Designers</summary>

| Tier   | Requirements |
| :--- | :--- |
| Tier 1 | Skills:<br/>* Basic Design Principles: Understanding of basic design concepts like color theory, typography, layout, and composition.<br/>* User Research: Basic knowledge of conducting user research, creating user personas, and understanding user needs.<br/>* Wireframing and Prototyping: Familiarity with tools to create simple wireframes and prototypes.<br/>* UI/UX Fundamentals: Entry-level understanding of user interface and user experience principles.<br/><br/>Tools:<br/>* Design Software: Familiarity with beginner-friendly design tools like Figma, Adobe XD, or Sketch.<br/>* Prototyping Tools: Basic usage of tools like InVision, Marvel, or Figma for creating simple prototypes.<br/>* User Research Tools: Basic understanding of tools like Google Forms, Typeform for conducting surveys or user interviews. |
| Tier 2 | Skills:<br/>* Advanced Design Principles: Strong grasp of design principles, ability to create visually appealing and functional designs.<br/>* User-Centered Design: Proficiency in creating user personas, conducting in-depth user research, and applying insights to design decisions.<br/>* Information Architecture: Ability to structure information effectively for better user experiences.<br/>* Usability Testing: Understanding and conducting usability testing to gather feedback and iterate designs.<br/><br/>Tools:<br/>* Advanced Design Software: Proficiency in using tools like Figma, Adobe XD, Sketch, or even more advanced tools like Photoshop or Illustrator for design tasks.<br/>* Prototyping and Animation Tools: Ability to create interactive prototypes using advanced features in tools like Figma, Principle, or Adobe After Effects.<br/>* User Testing Tools: Familiarity with tools like UserTesting.com, Maze, or Lookback for conducting user testing and gathering insights. |
| Tier 3 | Skills:<br/>* Expert Design Skills: Mastery of design principles, visual aesthetics, and creativity in problem-solving.<br/>* Advanced User Research: Ability to conduct comprehensive user research, analyze data, and derive actionable insights.<br/>* Design System Creation: Proficiency in developing and maintaining design systems for consistency and scalability.<br/>* Leadership and Collaboration: Ability to lead design projects, collaborate with cross-functional teams, and communicate design rationale effectively.<br/><br/>Tools:<br/>* Advanced Design Software: Mastery of tools like Figma, Sketch, Adobe XD, or other industry-standard software.<br/>* Prototyping and Animation Tools: Advanced usage of prototyping tools like Framer, Principle, or advanced animation features in design software.<br/>* Collaboration Tools: Proficiency in using collaboration tools like Miro, Notion, or Trello for team coordination and project management. |

</details>

<details>
<summary>For Product Owners</summary>

| Tier   | Requirements |
| :--- | :--- |
| Tier 1 | PO's who have studied Agile and Scrum, but who haven't yet had the opportunity to put what they've learned into practice in a team. |
| Tier 2 | PO's who have taken either Product Owner or Scrum Master training and who have applied what they've learned in a team. |
| Tier 3 | PO's who have successfully been certified as either a Product Owner or a Scrum Master from any certification authority. |

</details>

<details>
<summary>For Data Scientists</summary>

| Tier   | Requirements |
| :--- | :--- |
| Tier 1 | Skills:<br/>* Basic understanding of programming (Python, Javascript, etc.)<br/>* Fundamental knowledge of statistics and mathematics<br/>* Ability to clean and preprocess data<br/>* Basic knowledge of data visualization<br/>* Familiarity with basic machine learning concepts<br/>* Understand basic Web Development processes such as git/GitHub, Agile project management, etc.<br/><br/> Tools:<br/>* Programming Languages: Python or Javascrip<br/>* Data Manipulation: Pandas (Python), Pandas.js or Data-Forge (Javascript)<br/>* Data Visualization: Matplotlib, Seaborn (Python), D3 (Javascript)<br/>* IDEs: Jupyter Notebook |
| Tier 2 | Skills:<br/>* Programming for data analysis and manipulation<br/>* Understanding of statistical analysis and hypothesis testing<br/>* Knowledge of data engineering principles<br/>* Understanding of big data technologies and frameworks<br/><br/>Tools:<br/>* Statistical Analysis: NumPy, SciPy (Python), Math.js, NumJS (Javascript)<br/>* Database Query Languages: SQL<br/>* Advanced Visualization: Plotly, Tableau, D3, etc.<br/>* Cloud Platforms: AWS, Azure, Google Cloud Platform, etc. |
| Tier 3 | Skills:<br/>* Understanding of advanced machine learning algorithms and their implementation<br/>* Ability to build and deploy complex models<br/>* Expertise in data engineering and architecture<br/>* Strong problem-solving and analytical skills<br/>* Experience with machine learning algorithms and model evaluation<br/><br/>Tools:<br/>* Machine Learning Libraries: Scikit-learn (Python), TensorFlow.js (Javascript)<br/>* Deep Learning Frameworks: TensorFlow, PyTorch, etc.<br/>* Model Deployment: Flask, Docker, Kubernetes |

</details>

### 2. If you already have a project that matches your tier 👍

If you already have a project that matches the requirements of the tier you've
chosen then go ahead and submit it for evaluation. Your project can be one 
you've completed on your own or as a part of a team. It should meet these 
criteria:
    
- It must coorespond to the requirements of the tier you've selected
- It should be original work (not copied from someone else, including a tutorial)
- If created as part of a team you should be a major contributor to the project
- It have been developed within the last 12 months, or have a significant number 
of commits made by you within the last year.

### 3. If you don't have a project ready

If you don't have a project you can create one from the 30+ projects we've
provided specifications for.

<details>
<summary>For Product Owners</summary>

| Project Name | Tier 1 | Tier 2 | Tier 3 |
| :--- | :--- | :--- | :--- | 
| Chingu Trivia | [Click here](https://github.com/chingu-voyages/soloproject-tier1-chingu-trivia-po) | [Click here](https://github.com/chingu-voyages/soloproject-tier2-chingu-trivia-po) | [Click here](https://github.com/chingu-voyages/soloproject-tier3-chingu-trivia-po) |

</details>
<br/>

<details>
<summary>For Web Developers, UI/UX Designers, & Data Scientists</summary>
<br>
<b>Note: Some project requirements are outdated, we are in the process of updating them. You are still welcome to use the project ideas but the project will need to meet requirements listed above.</b>

| Project Name | Tier 1 | Tier 2 | Tier 3 |
| :--- | :--- | :--- | :--- | 
| 100DaysofCSS Clone | [Click here](https://github.com/chingu-voyages/soloproject-tier1-100dayscss) | - | - |
| Initab Clone | [Click here](https://github.com/chingu-voyages/soloproject-tier1-initab-clone) | - | - |
| Tickybot Clone | [Click here](https://github.com/chingu-voyages/soloproject-tier1-tickybot-clone) | - | - |
| Website Template | [Click here](https://github.com/chingu-voyages/soloproject-tier1-website-template) | - | - |
| Connect 4 | - | [Click here](https://github.com/chingu-voyages/soloproject-tier2-connect4-game) | - |
| MapBox API | - | [Click here](https://github.com/chingu-voyages/soloproject-tier2-mapbox-api) | - |
| Matching Game | - | [Click here](https://github.com/chingu-voyages/soloproject-tier2-matching-game) | - |
| Bookfinder | - | [Click here](https://github.com/chingu-voyages/soloproject-tier2-bookfinder) | - |
| Bookfinder (React Native) | - | [Click here](https://github.com/chingu-voyages/soloproject-tier2-bookfinder-rn) | - |
| Journal App | - | - | [Click here](https://github.com/chingu-voyages/soloproject-tier3-journal-app) |
| Mars Photos | - | - | [Click here](https://github.com/chingu-voyages/soloproject-tier3-mars-photos) |
| Meteorite Explorer | - | - | [Click here](https://github.com/chingu-voyages/soloproject-tier3-meteorite-explorer) |
| Chingu Trivia | [Click here](https://github.com/chingu-voyages/soloproject-tier1-chingu-trivia) | [Click here](https://github.com/chingu-voyages/soloproject-tier2-chingu-trivia) | [Click here](https://github.com/chingu-voyages/soloproject-tier3-chingu-trivia) |
| Critical Space Strike | [Click here](https://github.com/chingu-voyages/soloproject-tier1-criticalspacestrike) | [Click here](https://github.com/chingu-voyages/soloproject-tier2-criticalspacestrike) | [Click here](https://github.com/chingu-voyages/soloproject-tier3-criticalspacestrike) | 
| eCalendar | [Click here](https://github.com/chingu-voyages/soloproject-tier1-ecalendar) | [Click here](https://github.com/chingu-voyages/soloproject-tier2-ecalendar) | [Click here](https://github.com/chingu-voyages/soloproject-tier3-ecalendar) |
| Favorite Fonts | [Click here](https://github.com/chingu-voyages/soloproject-tier1-favfonts) | [Click here](https://github.com/chingu-voyages/soloproject-tier2-favfonts) | [Click here](https://github.com/chingu-voyages/soloproject-tier3-favfonts) |
| Flutter Blog | [Click here](https://github.com/chingu-voyages/soloproject-tier1-flutter-blogui) | [Click here](https://github.com/chingu-voyages/soloproject-tier2-flutter-blogui) | [Click here](https://github.com/chingu-voyages/soloproject-tier3-flutter-blogui) |
| Game Night | [Click here](https://github.com/chingu-voyages/soloproject-tier1-gamenight) | [Click here](https://github.com/chingu-voyages/soloproject-tier2-gamenight) | [Click here](https://github.com/chingu-voyages/soloproject-tier3-gamenight) |
| Virtual Pet | [Click here](https://github.com/chingu-voyages/soloproject-tier1-virtualpet) | [Click here](https://github.com/chingu-voyages/soloproject-tier2-virtualpet) | [Click here](https://github.com/chingu-voyages/soloproject-tier3-virtualpet) |

</details>
<br/>

One of our Facilitators will evaluate your Solo Project and will DM you in 
Discord with feedback you can use! They will look at both your code as well 
as the running app so you'll get 360-degree feedback.

### 4. Submit a Solo Project Completion Form ✅
    
When you've completed your Solo Project you will need to submit the **[Solo Project Completion Form](https://forms.gle/4qiLptoNdfkfaDVv9)** before you can move on to the Voyage Project.

> You are encouraged to submit this form as soon as your Solo Project is done. There is no need to wait until the submission deadline if you finish earlier.
> 

Once you submit the Solo Project Completion Form your project will be 
evaluated and a member of the Facilitation Team will provide you with 
status in a Discord direct message (DM).

There is no need to resubmit the completion form once you've received 
feedback. If any rework is requested you can open a support ticket 
[here](https://discord.com/channels/330284646283608064/1105911757177888908)
when you are ready for your project to be retested.
    
## Solo Project Requirements & Specifications 🧬
    
If you don't already have a project to submit you can create one from the following list. Simply pick a Solo Project that matches the tier you've chosen and click on the 'X' to see a detailed description, and what is required to complete it.
    
## Solo Project Prerequisites ✍️
    
- Your project should match the requirements of the 
[tier you have chosen](#1-choose-your-tier)
- Project source code must be hosted on GitHub
- Completed project must be deployed on the Internet.
- You'll be asked to provide the URLs for both your GitHub repo and the [deployed application](../../resources/techresources/techstack.md#deployment-options) when you submit the [Solo Project Completion Form](https://forms.gle/4qiLptoNdfkfaDVv9) for your project.

Remember that you are required to produce original work! You should not copy and submit a solo project you did not personally author. For more information refer to our [Community Standards](../../gettingstarted/communitystds.md).
    
## Solo Project Tips ✏️
    
1. It is more important to complete the project than it is to add features since completion is required before you can advance to the Voyage Project.
2. Concentrate on completing the required tasks for your tier and then work on bonus tasks only if time permits. Keep in mind that advancing to the Voyage phase of the Cohort depends on the completion of the required tasks listed in the project repo we've provided.
3. Choose tools you are comfortable and productive with. In the limited time available to complete the Solo Project it's not a good idea to try to use something you don't already know.
4. Unless otherwise noted in the required tasks for you tiers Solo Project the languages, tools, libraries, and frameworks you use are up to you. For example, all of the following approaches are acceptable paths to a successful project:
    - Using any language for web development, not just Javascript
    - Using Vanilla JS instead of a library or framework
    - Using a framework of your choice like React or Vue
    - Using a boilerplate or generator like Create React App (CRA)
    - Using a CSS library or creating your own CSS
5. Your repo should contain a well written [readme](https://medium.com/chingu/keys-to-a-well-written-readme-55c53d34fe6d).
6. Remember that your app should run error-free. There should be no errors in the browser or server console logs.
7. When you submit your project ***you must provide URL's for***: 
    - the publicly accessible repository containing your project (eg. Github).
    - the running version of your project where you have deployed it on an 
    Internet accessible host (eg. Github Pages, Netlify, etc.) so we can evaluate not
    just your code, but also your UI/UX.
8. You may **NOT** use a source code generator (like GitHub Co-Pilot) to 
create any part of your Solo Project.
9. Chingu is all about collaborative learning and supporting each other as
    we level up! Use our Discord channels to get help and advice.
