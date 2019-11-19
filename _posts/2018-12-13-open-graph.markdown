---
layout: post
title:  "Blog post with answers for examination 1"
date:   2018-12-13 19:26:00 +0100
categories: jekyll update
comments: true
---


### What do you think of pre-compiling your CSS?
I think that it is good. Right now i personally doesn't like it, but that is because i'm not used to it. But i can understand the functionality of it and would like to lear more about it.

#### Compare to regular CSS
It helps you extend the regular CSS-language with usable parts. It is less CSS to maintain, you can use variables, and it's better organized.

#### Which techniques did you use?
For the most parts with the styling I changed the variable for what I wanted to change more globally on the website. For example to have the header and footer the same style everywhere on the website and not change it for each blog post.

#### Pros and cons?

**Pros:**  
Nested syntax  
Easy to change multiple CSS-styles at once  
Can use calculations  
Ability to define variables

**Cons:**  
It's more difficult to debug your code  
It's more complex than regular CSS, you have to handle more tools

### What do you think of static site generators?
At the moment i'm not a big fan of them. They feel more complex to understand what you're getting into instead of writing you own code, at least as a rookie web developer. 

#### What type of projects are they suitable for?
Since it takes source files to generate a static website they are suitable for example blogs.

### What is robots.txt and how have you configure it for your site?
Robots.txt informs the web robot about what parts of your website that should not be processed or scanned, it is a standard to communicate with web crawlers and other web robots.

It is configured so that no bots can enter the site.

### What is humans.txt and how have you configure it for your site?
Humans.txt is a text file that contains information about the people who have contributed to building the website.

I configured it by putting it in the root file, that means that you only need to type in "/humans.txt" when you are in the home page.

### How did you implements comments to blog posts?
First i had to make an account on Disqus to get the Universal Code to use on my site, since they don't have specifically for Jekyll. I then added the code in posts.html under _layouts so I can add the comment box on all the blog posts I make.

### What is Open Graph and how do you make use of it?

Open Graph protocol gives the link you share on social media sites a "preview" of what the context is.
For example the title of the site and a picture that is on the site.

You as a developer can deside what this preview should provide with meta-tags.
Like what picture you think is most important. The most important to use it title, type, url, and image.