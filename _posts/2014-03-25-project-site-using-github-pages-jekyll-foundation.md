---
title: Project website goes live using Github Pages
author: planemad
layout: post
---

After some deliberation on wether to have a wordpress blog, we decided to stick with pushing all our code and documentation to one place for easier management and simplicity - [Github Pages](http://pages.github.com/). For those not aware, Github can host and serve a static website using the [jekyll](http://jekyllrb.com/) static blog engine. 

It requires a bit of documentation reading to understand how the different pieces work together, but for the terminally brave, this is but a minor skirmish. Here is the list of resources used to get our site running from scratch in a few hours:

* [Github Pages](http://pages.github.com/) to turn your repo into a freely hosted website
* Understand the basics of [Jekyll](http://jekyllrb.com/docs/home/) folder structure and concepts such as templates, layouts and includes
* Get familiar with the [Markdown Syntax](http://daringfireball.net/projects/markdown/basics) and how [Liquid Templates](http://docs.shopify.com/themes/liquid-basics) works.
* Read this great tutorial by [Andrew Munsell](https://www.andrewmunsell.com/tutorials/jekyll-by-example/tutorial) with step by step instructions on putting a jekyll site together
* [jekyll-bootstrap](https://github.com/plusjade/jekyll-bootstrap) for pieces of reusable code, especially if you want to use [bootstrap](http://getbootstrap.com/getting-started/) css framework
* Alternatively check out [Foundation](http://foundation.zurb.com/docs/) which is the framework we have used due to cleaner class names and documentation 
* We also added [Disqus](http://disqus.com/websites/) for managing user comments on the posts
* Protip: [Bower](http://bower.io/) for frontend dependency management

## [View the website](http://planemad.github.io/wikimaps-atlas/)
