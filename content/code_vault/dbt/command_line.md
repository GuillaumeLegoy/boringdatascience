---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "dbt - Command Line"
subtitle: ""
summary: ""
authors: []
tags: [dbt]
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

Link to dbt command reference: https://docs.getdbt.com/docs/running-a-dbt-project/command-line-interface/

## Run every model
------------  
```bash
dbt run --profile-dir=<profile_location> --target=target_name
```

## Run specific models model1 and model2
------------  
```bash
dbt run --profile-dir=<profile_location> --target=target_name --models model1 model2
```

## Exclude models model1 and model2
------------  
```bash
dbt run --profile-dir=<profile_location> --target=target_name --exclude model1 model2
```

## Run tests
------------  
```bash
dbt test --profile-dir=<profile_location> --target=target_name
```

## Install dependencies
------------  
```bash
dbt deps
```