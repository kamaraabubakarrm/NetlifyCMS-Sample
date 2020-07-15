---
title: "Module 3: Jamstack"
description: "Lets take a look at the Jamstack. It allow us to build fast,
reliable and secure websites. It consists of 3 attributes: 1. JavaScripts 2.
API's 3. Markup. During this module we will mainly look into the 3rd attribute by using a static site generator" 
date: 2020-06-10T17:24:23+02:00
duration: 1 week
draft: false
---

# Module 3: Jamstack
description: "Lets take a look at the Jamstack. It allow us to build fast,
reliable and secure websites. It consists of 3 attributes: 1. JavaScripts 2.
API's 3. Markup. During this module we will mainly look into the 3rd attribute by using a static site generator" 

As the Jamstack is getting more and more popular, [a big amount of static site generators become avaiable](https://www.staticgen.com/). Popular ones are Jekyll, Next.js, Hugo and Gatsby. During this module we will work with Hugo. [Hugo](https://gohugo.io/) is famous for its speed and flexibility.

For this module we ask you to make some modifications to an existing website
project that is build using Hugo. Learning resources and the coach are available
to help you with the assignment.

## Expected outcomes
By working on this module we expect the students to learn the following:

1. To understand the basic concepts of a static site generator and how this can
   help to build and maintain a website.
2. Learn to build a website using Hugo
3. Reinforce existing html and css skills

## Requirements
To work on this module you will need a working Hugo installation. [instructions
can be found here](https://gohugo.io/getting-started/installing/).

## Methodoligy
During this assignment we will work in a team of 4. We ask you to make a fork of
this repository and implement the userstories specified bellow. In the case that
one of the userstories is unclear, please ask your coach for clarification.

We recommend you to use an issue tracking tool to keep track of your user
stories. It is up to you to decide wich one you use. 

We will have daily meetings at 10am to have a short daily standup. Otherwise you
may organize your team as you wish.

## Assignment 
In [this repository](https://github.com/Makeni-hub/learn-hugo) you find the
basis of a Hugo project. Our goal is to continue working on this page and to
build it into a website thats shows Information about the Makeni Hub Project. 

What we will build is:

1. An homepage that shows basic information about the project.
2. A page that lists all of the modules for the project
3. A detail page where you can see more information for each of the modules
4. A List page where you can see all of the people that are involved in the
   project.
5. A detail page where you can see more information about a specific person
6. If we have time left we could build a showcase page where we can showcase the
   different projects we have worked on.

The following usecases are a more technical explanation of what needs to be
done.

## User stories

- update the file layout/_default/baseof.html to include all of the boilerplate
  code that is required for each html page (for example: doctype, head tag, meta
  tags, body tag

- create a heading partial, that inserts a navigation bar into every site.

    - This heading should contain a Logo (or website title) and Links to the
      Homepage, Modules List and Students List

- create a footer partial that is inserted in the bottom of every page

- create css styling for the website this may be a simple styling but you should
  use the mobile first principle and it should be functional on all screen
  sizes between 350px and 1920px with.
  - We advise that you start with a design that looks good for small screens and
    only afterwards start designing for bigger screen layouts

- create content (.md) files for the modules we have made so far (Git, Css +
  Html and Project) You don't have to write anything new, you can use the
  existing markdown files on github

- update the list template to display all the modules in a nice way

- create a new archetype 'participant'. This archetype should include the
  variables: Name, Specialization, Photo and Description

- create an content file for each of you, that give a short description. This
  can be something like: https://github.com/Makeni-hub/project-information/blob/master/docs/robin-altena.md

- create a template file that displays the list of students in a nice way

- create a template file that displays a single student in a nice way

- Host the website on Netlify, or a similar service


## Learning resources

- [Example project written in Hugo](https://github.com/Makeni-hub/landingpage) -
  [hosted here](https://happy-kilby-97e5f7.netlify.app/)
- [Hugo official documentation](https://gohugo.io/documentation/)
- [Introduction to Hugo (tutorial)](https://www.mikedane.com/static-site-generators/hugo/)
- [Modern Web Development on the Jamstack (free book)](https://www.netlify.com/pdf/oreilly-modern-web-development-on-the-jamstack.pdf) - this book is not specifically about Hugo but explains the Jamstack very well
- [Hugo in Action (book, free review)](https://www.manning.com/books/hugo-in-action)
