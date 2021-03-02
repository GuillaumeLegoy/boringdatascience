---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Data Science is Dead, Long live Data Science!'
subtitle: ''
summary: ''
authors: []
tags: []
categories: [Python]
date: 2021-03-02T00:00:00+01:00
lastmod:
featured: false
draft: false
text-align: justify
# Featured image

# To use, add an image named `featured.jpg/png` to your page's folder.

# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.

image:
caption: ''
focal_point: ''
preview_only: false
# Projects (optional).

# Associate this post with one or more of your projects.

# Simply enter your project's folder or file name without extension.

# E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.

# Otherwise, set `projects = []`.

## projects: []
---

<div style="text-align: justify">    
  
  
## Data Scientists Don't Exist

Before we start I want to highlight this is my opinion only and it's based on my anecdotal experience so far in the field so YMMV. The inspiration for this post (with a very clickbaity title) comes from a series of discussions on social media talking about data scientist roles and what they represent, like [this reddit post asking for interviewers to stop with Leetcode questions](https://www.reddit.com/r/datascience/comments/lkn4rl/please_stop_asking_data_scientists_about_leetcode/). The answers are even better than the post itself and highlight in my opinion a profound misunderstanding of what data scientists are, which I thought we already figured out in 2021, but here we are.

**Data science isn't a role, it's a spectrum of roles**. It ranges from data engineers on one extreme to pure deep learning researchers on the other with BI and data analyst somewhere in the middle (no I'm not going to insert a Venn diagram). Add to the mix new roles like [analytics engineer](https://blog.getdbt.com/what-is-an-analytics-engineer/) and you've given your HR manager a headache when it's time to write down the specifications for your new data scientist position. However most companies, people, or students still operate under the assumption that data science consists of building fancy machine learning models and are therefore very dissapointed when they realize their job is the absolute opposite of doing machine learning. [This hilarious post by Kenny Ning](https://kleandata.substack.com/p/data-science-is-different) perfectly summarizes the issue. Now don't get me wrong a few brilliant individuals at Google, StitchFix, Nvidia or any cool computer vision startup actually get to work on building fancy models all day like their life is one never ending Kaggle competition made of glittery clean data, but for mortals like (probably) you and me this will almost never be the case. Data scientists are like unicorns, they don't exist or if they do they are a handful of mythical creatures that you won't be able to afford anyway.

The consequences of this are dire. Companies hire expensive data scientists who end up sitting in a corner doing nothing, data science bootcamp graduates discover during their first job that Excel isn't only for schmucks and that they have to (gasp) use SQL and in the end turnover is high, money is wasted, and nobody trust the data anymore.

## The Future of Data Science is Bright

Now a glimmer of hope: this situation is actually quite simple to fix (famous last words). The abundance of new amazing technologies allowing us to manipulate data and build robust ETL pipeline means there has never been a better time to be working in the field. However it's time to break down data science into its clear subfields and stop misguiding candidates, execs and students alike on what they can expect from working with data.

First if you are a company identify your needs. Do you already have a stable data infrastructure, robust pipelines, devops engineers and data analysts? Then maybe you are ready for a machine learning researcher. Is your data available but you have no idea if it's clean or exploitable? It's time to hire an analytics engineer. You have no pipeline and no available data anywhere yet? A data engineer and a devops engineer can work wonders at this stage.

Secondly **communicate** what you need to the recruiting team. This isn't the job of your HR manager to spit out a vague data scientist job description with 25 buzzwords and how you really need a "Python ninja" or a "deep learning wizard" (seriously don't do that). Then when people apply make sure you give them a rundown of the current situation and what their job will actually look like. If they are going to be spinning up S3 buckets and write SQL all day it's fine, but don't lie to them by affirming they gonna get to read and implement research papers.

Finally if you are on the other side as a recent data science graduate or equivalent and you are looking to get into the field, make sure you understand the above distinction and ask the right questions during interviews. This will lessen the probability that you end up in a role you actually hate. Also don't be afraid to explore the boring side of data science (see what I did here?...no?...ok): basic software engineering best practice like version control, testing your code, basic cloud services, data structures, etc. are not that hard to get started with but can give you an edge and who knows maybe you'll realize data engineering is actually great.

Happy coding!

</div>
