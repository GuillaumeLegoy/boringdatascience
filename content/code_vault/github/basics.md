---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "Github - Basics"
subtitle: ""
summary: ""
authors: []
tags: [Github]
categories: []
date: 2020-02-18T16:05:00+01:00
lastmod: 2020-02-19T00:05:00+01:00
featured: false
draft: false
blackfriday:
  extensions: "hardLineBreak"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---



## Clone a repository from Github
------------  
```bash
git clone https://github.com/USER_NAME/REPO_NAME.git
```

## Initiate a repository in an existing project and push it to an empty Github remote repository
------------

```bash
git init

git add .

git commit -m "Initial commit of local project."

git remote add origin https://github.com/USER_NAME/REPO_NAME.git

git push origin master
```

## Basic git workflow
------------

```bash
git init

git add <file_name>

git commit -m "What I changed."

git push origin <branch_Im_working_on>
```
