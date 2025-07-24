# Choosing your Techstack

![Team choosing a technical stack](./assets/Team_choosing_techstack.jpeg)

Products and languages in the tech stack are divided into four basic
categories - frontend, backend, database, and DevOps. The components that make
up web applications are also divided between two categories:

- *[Frontend](https://www.notion.so/Glossary-c0b10b9e0c9a4e80a0c3482433fb08a4?pvs=21)-only
  application* - Composed of only frontend products and languages and runs
  exclusively in the user's browser.
- *[Full stack](https://www.notion.so/Glossary-c0b10b9e0c9a4e80a0c3482433fb08a4?pvs=21)* [](https://docs.chingu.io/glossary#fullstack)*application* -
  Composed of at least a frontend and backend, but may optionally include
  database and DevOps components.

The following lists some of the more popular products and languages to provide a
view of how they are categorized. Remember that there are literally thousands of
products Web Developers may choose from in the JavaScript ecosystem.

| Technology              | Frontend | Backend | Database |
| ----------------------- | -------- | ------- | -------- |
| **__BASIC TECH__**      |          |         |          |
| HTML                    | ✓        |         |          |
| CSS                     | ✓        |         |          |
| JavaScript              | ✓        |         |          |
| **__INTERMEDIATE TECH__** |          |         |          |
| Sass                    | ✓        |         |          |
| Apollo Client (GraphQL) | ✓        |         |          |
| NodeJS                  |          | ✓       |          |
| Express, Fastify, etc.  |          | ✓       |          |
| Firebase, MongoDB       |          |         | ✓        |
| React, Vue, Svelte, etc.| ✓        |         |          |
| NextJS                  | ✓        | ✓       |          |
| **__ADVANCED TECH__**   |          |         |          |
| Docker                  | ✓        | ✓       | ✓        |
| Redux                   | ✓        |         |          |
| Apollo Server (GraphQL) |          | ✓       |          |
| PostgreSQL              |          |         | ✓        |

## Front-End Technologies

### HTML-CSS

HTML is a markup language used to format web pages. The browser interprets your
HTML to determine how to format the content that makes up your web pages. CSS is
used with HTML and defines the styling to be applied to the content. As an
example, you would use HTML to specify which content elements are headers versus
body text, and CSS to define that headers are rendered in a 24 point, bold,
black, Sans Serif font.

### Sass

CSS Pre-processors extend CSS functionality by allowing you to declare your CSS
as reusable variables. We highly recommend this for development teams.

Why should you use this? For example, if you want to change the theme color for
your Header, Buttons, Footers, and/or Links, do you really want to go through
all of your stylesheets to manually change that one color?
With [Sass](https://sass-lang.com/), you can set a variable **$theme-color** and
have every developer use it. Changing the theme-color becomes a one-line effort.

### JavaScript

JavaScript is a browser scripting language that makes web pages interactive.

For more information about JavaScript checkout these resources:

- [Mozilla Developer Network (MDN)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Wikipedia - JavaScript History](https://en.wikipedia.org/wiki/JavaScript#History)
- [The Modern Javascript Tutorial](http://javascript.info/)

### jQuery

JavaScript library that allows developers manipulate the DOM. While a lot of
websites may still be running on [jQuery](https://jquery.com/), a lot of the web
development world is leaving it behind and turning to new tools such as React or
Angular. We do **NOT** recommend putting more time into learning jQuery.

### React

[React](https://reactjs.org/) is a JavaScript library created by Facebook for
making reusable user interfaces by adding JavaScript logic into HTML. Flexible
and light-weight.

This is a great next step to learn after HTML/CSS and JavaScript. We highly
recommend learning this as it is very popular in the front end world.

### Redux

[Redux](https://redux.js.org/) is a state management library for React. It has a
lot of initial work involved in setting it up, so we would only recommend it for
larger projects with a complex state. The library itself also abstracts a lot of
the concepts, so it may be difficult for a beginner to understand and
troubleshoot in Redux.

### Angular

[Angular](https://angular.io/) is a TypeScript (JavaScript + Enforced
Types) framework created by Google. It has more overhead than React but as a
result, it has more methods / functions provided, such as form validation and
page routing. If you want to use this, start a project with it -- trying to use
it in an existing project is not going to be easy.

### Apollo Client (GraphQL)

For those interested in making a GraphQL
API, [Apollo Client](https://www.apollographql.com/) is an abstraction layer
designed to help you make GraphQL API calls on the frontend and works with your
main JavaScript library such as React.

### Astro

[Astro](https://astro.build/) is particularly well suited to content-heavy sites
such as blogs and documentation. If your project is just HTML and CSS, Astro is
a great platform to choose. By default, it does all rendering on the server, and
does not send any JavaScript to the client. This produces a very fast site with
a great user experience.

Astro can also host client-side frameworks like React and Vue. You can create
*islands* of reactive content and keep most of the site static. Astro can even
support different frameworks on the same page, e.g. a React component as one
island, and a SolidJS component as another. Astro takes care of bundling the
right Javascript so everything works.

### Other popular technologies include Vue and Ember.

## Back-End Technologies

### Node.js

[Node.js](https://nodejs.org/en/) is an open-source, cross-platform JavaScript
run-time environment that executes JavaScript code outside of a browser.
Essentially, JavaScript for non-browser environments. If you didn't use Node.js
for backend, another option could be Python.

### Express

[Express](https://expressjs.com/) is a web application framework for Node.js for
building APIs. It acts as an intermediary level between your
client-side (user-facing site) and your servers/databases.

For example, if you want to make a RESTful API, you would configure Express to
expose numerous API endpoints from which it can create, read, update, or delete
items from your chosen database.

### Apollo Server (GraphQL)

If you are interested in creating a GraphQL
API, [Apollo Server](https://www.apollographql.com/) is a helpful layer on top
of Express.

## Databases

### PostgreSQL (Relational)

[PostgreSQL](https://www.sisense.com/blog/decide-postgresql-reporting-right/) is
an open
source [relational database](https://www.sisense.com/glossary/relational-database/) that
is much more concerned with standards compliance and extensibility than with
giving you freedom over how you store data. It uses both dynamic and static
schemas and allows you to use it for relational data and normalized form
storage. MongoDB, with its unstructured approach, can’t do that.

Most jobs will probably want relational database knowledge.

### MongoDB (Non-Relational, Document)

[MongoDB](https://www.mongodb.com/) is an open source database. It’s designed to
be agile and scalable, and it uses dynamic schemas so that you can create
records without defining the structure first. It also supports hierarchical
documentation of data.

## Platforms

### Firebase

[Firebase](https://firebase.google.com/) is an app development platform that
helps you build and grow apps and games users love.

Backed by google and trusted by millions of businesses around the world.

### Appwrite

[AppWrite](https://appwrite.io/) is an open source platform that allows you to
add Auth, Databases, Functions, and Storage to you product and build any
application at amy scale, own your data, and use your preferred coding languages
and tools.

trusted by a growing number of developers from the world's leading organizations

## DevOps

### TravisCI

Continuous integration (CI) products such
as [TravisCI](https://travis-ci.org/) integrate with Git to both automate and
validate procedures such as pull requests. This type of automation eliminates
the need for manual processes and improves quality by ensuring that required
steps aren't inadvertently skipped. For example, CI tools can run linters, test
scripts, and halt a PR if any errors are detected.

### Docker

Imagine a full stack project with a client-side (React), back-end (Express), and
database (PostgreSQL). When you are developing in a team, it may be difficult to
get all three items to run exactly the same way for each person. There are
various reasons for this, such as different operating systems, different starter
data in the databases, etc. [Docker](https://www.docker.com/) solves this
problem by wrapping each part in a "container" and lifting it up into the cloud
to give each developer access to the same exact thing.

**A Docker container can be seen as a computer inside your computer**. The cool
thing about this virtual computer is that you can send it to your friends; when
they start this "computer" and run your code, they will get exactly the same
results as you did.

## Deployment Options

Well before you've reached the MVP milestone for your application you'll want
to deploy it to the Internet so your team can perform integration testing and
get everything set up to incrementally deploy what you've completed at the end
of **_every_** sprint.

You can learn more about the options for web hosting in the 
[App Deployment](./appdeployment.md) topic of this Guide.