---
layout: post
title:  "setup jekyll on linux"
date:   2021-11-06 12:26:37 -0300
categories: tutorial
---

Install ruby and its development packages

`sudo apt install ruby ruby-dev`

Install Jekyll

`sudo gem install bundler jekyll`

Create a new jekyll project

`jekyll new PROJECT_NAME`

Start the server

`cd PROJECT_NAME`
`bundle exec jekyll serve --livereload`

Navgate to the page at [http://localhost:4000/](http://localhost:4000/)

happy coding.