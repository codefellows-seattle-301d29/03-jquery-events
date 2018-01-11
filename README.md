![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 03: jQuery Events
===

## Code Wars Challenge

Complete [today's Kata](https://www.codewars.com/kata/insert-dashes) and follow the submission instructions from Lab 01.

## Lab 03 Submission Instructions
Follow the submission instructions from Lab 01.

## Resources  
[jQuery cheatsheet](https://oscarotero.com/jquery/)

[Template Literals MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)

## Configuration
_Your repository must include:_

```
03-jquery-with-events
├── .eslintrc.json
├── .gitignore
├── LICENSE
├── README.md
├── index.html
├── scripts
│   ├── article.js
│   ├── articleView.js
│   └── blogArticles.js
├── styles
│   ├── base.css
│   ├── fonts
│   │   ├── icomoon.eot
│   │   ├── icomoon.svg
│   │   ├── icomoon.ttf
│   │   └── icomoon.woff
│   ├── icons.css
│   ├── layout.css
│   └── modules.css
└── vendor
    └── styles
        └── normalize.css
```

## User Stories and Feature Tasks

- Continue styling the app using SMACSS practices. Take a few minutes for code review of your partner's CSS and decide how to incorporate it into your paired lab. You can choose one partner's CSS structure, or you can combine them as you see fit. Seek to optimize and organize your CSS as much as possible!

*As a user, I want to be able to filter my articles so that I can selectively view articles by author or by category.*

- Complete the new requirements for setting `data-<attributes>` in your `toHtml()` method.
- Complete the methods for handling filter events when selecting an option from a drop down menu via Authors and Categories so that only the selected articles are displayed on the screen.

*As a user, I want to be able to preview each article so that I can easily view the results and select the one I want to read further.*

- Add an event to reveal a complete article if the user would like to see more of it beyond the teaser.

*As a user, I want tab-based navigation so that I can easily visit other sections of my site.*

- Complete the method `articleView.handleMainNav()` for implementing tab-based event navigation on the page.

*As a developer, I want my code to be thoughtfully organized, easy to read, and executing efficiently.*

- Review and understand the new JS file, `articleView.js`
- Add any new script tags to your HTML.
- Refactor concatenation using template literals.
- Render the app upon page load.

### Stretch Goal

*As a user, I want to be able to collapse an expanded article to the teaser view so that I can more easily scan over a series of articles.*

- Build in functionality such that a user can click on "Show Less" to collapse a full article into a teaser.

## Documentation
_Your README.md must include:_

```md
# Project Name : jQuery Events 

**Author**: Andrii and Jasper
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 301 class. (i.e. What's your problem domain?) -->

The user of the app what be able specific selection(s) base on the article's title and catagory. 

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->

We first followed the setup instructions for github and our local machiines.
We then read through the original "starter-code" to get an idea of what we are going to be working on. 
We talked about each 'TODO' before starting to code. 

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->

The assignment is to creat new functionalities on a one-page blog app. 
We added options for users to filter for different blog(s) based on the author name and the article category.
Technologies used: jQuery library to (select and manipulate) different functions of the app.

## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples:

Some shallenges:
displaying only the article at the bottom of the page to load (without creating a separate page)
> Getting the manu buttons to work and they stared to work only after we add a call funtions at the very end of the article.js page. 

## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. -->
-->
```
links used:
https://oscarotero.com/jquery/
stackoverflow.com
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Methods_Index
