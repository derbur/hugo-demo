---
title: "Static Site Frameworks: Hugo, Jekyll or Gatsby?"
date: 2020-11-29T23:38:55-05:00
slug: "post"
description: "Which of the static site platforms will rule them all?"
keywords: [ "first", "jekyll", "hugo", "gatsby" ]
draft: false
tags: [ "first", "hugo", "jekyll", "gatsby" ]
math: false
toc: true
---
Bloggin' 😎 

## Categories
Ease of Creation  
Theming  
Hosting  
Updates

## Hugo
Hugo was my first attempt of the list of static sites. This was due to it claiming to be fast and easy to work with, (with Jekyll being a close second - or even an easier platform).
### Setup
The initial setup of Hugo is simple.

  1. Install Hugo: `brew install hugo`
  2. Create a new site: `hugo new site hugo-test`
  3. Move to the site's directory: `cd hugo-test`
  4. Run the site locally with drafts enabled: `hugo server -D`

Now we have a Hugo site up and running! 🚀

### Theming
For the Hugo blog I chose the [Codex theme](https://github.com/jakewies/hugo-theme-codex).
To add the theme to the site we just add the submodule to the `/themes` directory.

Add Codex theme: `git submodule add https://github.com/jakewies/hugo-theme-codex.git themes/hugo-theme-codex`

To create/modify the homepage, we add a file called `_index.md` to the `/content` directory:
```
---
heading: "Hi, I'm Derrick"
subheading: "This is a place where I put things"
---
```
