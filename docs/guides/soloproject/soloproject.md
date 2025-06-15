# Solo Project

![Team creating project backlog](./assets/SoloProject_coder.jpeg)

## Overview

The Solo Project helps you and the Chingu team verify that the Tier you have
chosen matches your current skill level, so you will be ready for your first
Voyage.

Once you have submitted your Solo Project, our team will evaluate it and provide
helpful feedback, highlighting what you did well and areas for improvement.

## Steps to Follow

```mermaid
graph TB
    A((<a href='https://github.com/chingu-voyages/Handbook/blob/main/docs/guides/soloproject/soloproject.md#1-choose-your-tier-1%EF%B8%8F%E2%83%A3-2%EF%B8%8F%E2%83%A3-3%EF%B8%8F%E2%83%A3'>Choose your Tier</a>)) --> B{What is your role?}
    B -- Scrum Master --> G
    B -- Product Owner, Developer,</br>UI/UX Designer,</br>Data Scientist --> F{Do you have a project?}
    F -- Yes --> G(Submit your <a href='https://forms.gle/D3Nu1VvfH3FDFBRr6'></br>Solo Project form</a>)
    F -- No --> H(Create new Solo Project <a href='https://github.com/chingu-voyages/Handbook/blob/main/docs/guides/soloproject/soloproject.md#2-submit-a-project-'></br>matching your tier</a>)
    H --> G
    G --> J(Evaluator DMs feedback</br>in Discord)
    J --> K{Accepted?};
    K -- Yes --> L(Submit <a href='https://forms.gle/dFaNuYWAjARd99qo8' target='_blank'>Voyage Signup form</a>);
    K -- No --> M(Make requested changes);
    M --> N(<a href='https://discord.com/channels/330284646283608064/1193342042080817323' target='_blank'>Open a ticket</a></br>to notify Evaluator);
    N --> J;

    L --> Z([End]);
```

### 1. Choose your Tier 1️⃣-2️⃣-3️⃣

You'll first need to choose a **tier** that matches your current skill level
for your preferred role. There are three tiers - beginner (Tier 1),
intermediate (Tier 2), or experienced (Tier 3).

[Developer (Web) tiers](./topics/tier_developer.md)</br>
[Developer (Python) tiers](./topics/tier_developer_python.md)</br>
[UI/UX Designer tiers](./topics/tier_uiuxdesigner.md)</br>
[Product Owner tiers](./topics/tier_productowner.md)</br>
[Scrum Master tiers](./topics/tier_scrummaster.md)</br>

### 2. Submit a project 👍

Next, submit a project that matches the requirements of your role and tier.

It **must** meet these criteria:

- It must match the requirements of the
[tier you have chosen](#1-choose-your-tier-1%EF%B8%8F⃣-2%EF%B8%8F⃣-3%EF%B8%8F⃣)
- It should be original work (not copied from someone else, including tutorials
or AI-generated code)
- If created as part of a team you should be a major contributor to the project
- It must have been created within the last 12 months, or be one you've
significantly enhanced within the last year.

Remember it must be your original work! You should not copy and submit a
project you did not personally author. For more information refer to our
[Community Standards](../../gettingstarted/communitystds.md).

#### What you will need to submit

```mermaid
graph TB
    A{I am a Developer?};
    A -- Yes --> B(<a href='https://github.com/chingu-voyages/Handbook/blob/main/docs/guides/soloproject/soloproject.md#if-you-are-a-developer'>URL's for GitHub repo &</br>deployed application</a>);
    A -- No --> C{I am a Product Owner};
    C -- Yes --> D(<a href='https://github.com/chingu-voyages/Handbook/blob/main/docs/guides/soloproject/soloproject.md#if-you-are-a-product-owner'>Complete quiz in Solo Project</br>form & URL of sample</br>Product Backlog</a>);
    C -- No --> E{I am a Scrum Master};
    E -- Yes --> F(<a href='https://github.com/chingu-voyages/Handbook/blob/main/docs/guides/soloproject/soloproject.md#if-you-are-a-scrum-master'>Complete quiz in</br>Solo Project form</a>);
    E -- No --> G{I am a UI/UX Designer};
    G -- Yes --> H(<a href='https://github.com/chingu-voyages/Handbook/blob/main/docs/guides/soloproject/soloproject.md#if-you-are-a-uiux-designer'>URL for a website design);
    G -- No --> I(Chingu doesn't support</br>your preferred role);
    B --> Z([End]);
    D --> Z;
    F --> Z;
    H --> Z;
    I --> Z;
```

### If you are a Developer

You will need to provide the URLs for:

1. a **public GitHub repo** containing the source code.
2. the [deployed application](../../resources/techresources/techstack.md#deployment-options)
accessible through the Internet. Please include a test account and password if
a signin is required.

You can use the [Solo Project Completion Form](https://forms.gle/VCpN1K6j341Vz1dq6)
to submit your project.

### If you are a Product Owner

Product Owner projects include:

1. a short quiz in the submission form. The minimum passing score for the quiz
is 80%. If you don't pass you will be able to update your answers
for the questions you missed.
2. the URL of a **public website** containing a sample product backlog you have
created. This may be in the service of your choice. For example, GitHub
Projects, Trello, Miro, ClickUp, Jira, or any similar tool.

You can find the quiz in the [Solo Project Completion Form](https://forms.gle/VCpN1K6j341Vz1dq6).

Your sample product backlog doesn't need to be complicated, but it should
demonstrate that you understand how to visually organize the project using
Epics, User Stories, and Tasks. It is a plus if you include dependencies between
product backlog items, acceptance criteria, edge cases, and test criteria.

If you don't already have a project you can create a backlog using
[this project specification](https://github.com/chingu-voyages/soloproject-tier3-chingu-trivia-po).

### If you are a Scrum Master

If you are a Scrum Master the Solo Project submission form includes
a short quiz. This is a combination of multiple-choice and long-form
questions.

The minimum passing score for the quiz is 80%. If you don't pass you will be
able to update your answers for the questions you missed.

You can find the quiz in the [Solo Project Completion Form](https://forms.gle/VCpN1K6j341Vz1dq6).

### If you are a UI/UX Designer

As a UI/UX Designer you need to provide the URL of a **public website**
containing a design you have created.

This may be hosted on Figma, AdobeXD, or in any other prototyping tool. It may
include a more formal study including things like personas and stakeholder
goals, in addition to wireframes.

You can use the [Solo Project Completion Form](https://forms.gle/VCpN1K6j341Vz1dq6)
to submit your project.

### 3. Submit a Solo Project Completion Form ✅

You will need to submit your project using the
**[Solo Project Completion Form](https://forms.gle/bwPYEaco5a3KhMqU6)**. This
must be completed before your first Voyage.

> You are encouraged to submit this form as soon as your Solo Project is done.
There is no need to wait until the submission deadline if you finish earlier.
>

After submitting the Solo Project Completion Form we will evaluate it and
provide feedback in a Discord direct message (DM) within
***4 business*** days. This could take longer based on the number of
Chingus submitting projects at the same time.

Since we DM feedback to you in Discord it's important that you enable DM's so
you will be able to see it. Make sure that in your Discord `Settings -> Content &
Social -> Social Permissions` you've enabled DM's from other server members.

![Discord DM Setting](./assets/Discord_DM_Settings.png)


There is no need to resubmit the completion form once you've received
feedback. The feedback we DM to you will contain information on what to do next.

## Solo Project Tips ✏️

1. Completing a project that meets the requirements of your tier and role is
more important than submitting a complex project.
2. Choose tools you are comfortable and productive with. In the limited time
available to complete the Solo Project it's not a good idea to try to use
something you don't already know.
3. The languages, tools, libraries, and frameworks you use are up to you. For
example, all of the following approaches are acceptable paths to a successful
project:
    - Using any language for web development, not just Javascript
    - Using a framework of your choice like React or Vue
    - Using a boilerplate or generator like Vite
    - Using a CSS library or creating your own CSS
4. Your repo should contain a well-written [readme](https://medium.com/chingu/keys-to-a-well-written-readme-55c53d34fe6d).
5. Your app should run error-free. There should be no errors in
the browser or server console logs.
6. When you submit your project **you must provide URL's as defined above**
7. You may **NOT** use a source code generator or AI tool (like GitHub Co-Pilot)
for any part of your Solo Project.
8. Chingu is all about collaborative learning and supporting each other as
we level up! Use our Discord channels to get help and advice from other Chingu's.
