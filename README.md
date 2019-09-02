# ForrestSeeWebApp

`ForrestSeeWebApp` is a website built on top of a free Bootstrap Jekyll theme for blogging, collections, resources, reviews websites.

This documentation is written by command line terminal users including `Windows`, `Linux` and `Mac` for a purpose of adding a new blog to the website. The process is processed by `Git`- a general package for version control especially in open-source.

Original link can be seen here https://bootstrapstarter.com/bootstrap-templates/template-mediumish-bootstrap-jekyll/

### How to use this website

0. Make sure that you are added to repo as a contributor. Shoot an email to xlab.contact@gmail.com to let us know you, and then you can proceede the next step

1. Download or `git clone https://github.com/XLabSF/ForrestSeeWebApp`

2. `cd ForrestSeeWebApp`

3. Start by adding your `.md` files in `_posts` directory.

4. `git add <filename>` or `git add -p` for a modification.

5. `git commit -m "<note for a git>"`

6. `git push origina master` Note: Pay attention! Be careful for any update on a `master` branch - anything updated here will be shown immediately on the website.

### Some useful structures

YAML front matter
featured post - featured:true
exclude featured post from “All stories” loop to avoid duplicated posts - hidden:true
post image - image: assets/images/mypic.jpg
external post image - image: "https://externalwebsite.com/image4.jpg"
page comments - comments:true
meta description (optional) - description: "this is my meta description"
#### YAML Post Example:
```md
---
layout: post
title:  "We all wait for summer"
author: john
categories: [ Jekyll, tutorial ]
image: assets/images/5.jpg
description: "Something about this post here"
---
```
#### YAML Page Example

```md
---
layout: page
title: Mediumish Template for Jekyll
comments: true
---
```


#### Table of Contents

Add toc:true on your post YAML.
```md
---
layout: post
title:  "Education must also train one for quick, resolute and effective thinking."
author: john
categories: [ Jekyll, tutorial ]
image: assets/images/3.jpg
beforetoc: "Markdown editor is a very powerful thing. In this article I'm going to show you what you can actually do with it, some tricks and tips while editing your post."
toc: true
---
```
