---
layout: post
title:  "Reflection"
date:   2015-11-16 00:11:00
categories: blog post
---

##Questions:

* What do you think of pre-compiling your CSS?

I think pre-compiling your CSS is useful for bigger projects where there is changes happening in the CSS-code from time to time. It is also useful when there is a need to divide the styling code in many files. Smaller projects for personal use with low complexity I get the feeling that it is more tools than you need with pre-compiling your CSS.

  **Compare to regular CSS**

  Pre-compiling your CSS introduces more programming features like variables, inbuilt arithmetic operations and "functions/methods"  etc. Another feature is that it gives possibilities to put together one CSS file from several pre-compiled files.

  **Which techniques did you use?**

  I used variables so that a CSS modification could be made from just one spot and affect different areas of the website. The code were also put in different scss-files to be pre-compiled into one "main.css" file.

  **Pros and cons?**

  **Pros:**

  Variables, change the value of a variable in it applies to all areas where the variable has been used.
  Create one CSS file by pre-compiling many files into one file.
  Decreases use of redundant code.
  Better organized code with nested levels.
  Reusable "functions/methods".

  **Cons:**

  Another syntax, requires more competence from the programmer.
  Gets harder to track the source of bugs or any unwanted code after being pre-compiled from several files to one CSS-file.


* What do you think of static site generators?

I think static site generators are good for setting up a fast, efficient and a reliable websites. Since it is a static website there are not much to hack, no database with user data and so on. Disadvantages of static websites is that it is not much user interaction and no real-time content unless you involve a third-party service.

  **What type of projects are they suitable for?**

Static site generators are suitable for projects where you don't need a database. Also good for a project where you need a fast website where the amount of users could vary a lot.

* What is robots.txt and how have you configure it for your site?

Robots.txt is a text file that give instructions for programs that go through the Web automatically. The text file can tell programs what content they are allowed to access and where it is and so on. There can be different purposes for the programs like indexing a site or finding emails and more. I configured it to not hide anything for any program that is going through my website.

* What is humans.txt and how have you configure it for your site?

Humans.txt is a text file for human users of the website so they will be able to access metadata about the site. This text file can for instance show the creator of website, location, tools used to create the site and more. I choose to include info about the name of the creator, location, last updated, contact info and software used to build the website.

* How did you implements comments to blog posts

I used third-party service Disqus and the universal embeded code they provided. I put the code in the index.html file of my website just under the blog post area. I also added the line "comments: true" in the YAML front matter of the index.html file in order to allow comments on that page.

* What is Open Graph and how do you make use of it?

Open Graph is a way objectify things on the Web so it can be shared on social media. I made use of Open Graph on my website so a user could share any of the git pages that my website contains.


