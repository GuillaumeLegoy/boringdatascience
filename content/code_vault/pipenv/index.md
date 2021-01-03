---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "Pipenv"
subtitle: ""
summary: ""
authors: []
tags: [Pipenv]
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



## Install pipenv
------------  
```bash
    python3 -m pip install pipenv # On Linux
    brew install pipenv # On Mac
```      

## Initiate pipenv for a project
------------

```bash
    pipenv
    pipenv --python 3.8 # If you want a specific Python version
```  

## Install dependencies from an existing Pipfile
------------

```bash
    pipenv install
    pipenv install --dev # All dependencies including dev libraries
    pipenv sync # Install the exact version of dependencies, better in production
```    

## Install a library
------------

```bash
    pipenv install pandas
    pipenv install --dev pytest # Only for devevelopment
```   

## Uninstall a library and clean dependencies
------------

```bash
        pipenv uninstall pandas
        pipenv clean # Will clean the Pipfile.lock file of unused dependencies
```   

## Lock and check for issues
------------

```bash
        pipenv lock
        pipenv check
        # Check for security vulnerabilities
```  
