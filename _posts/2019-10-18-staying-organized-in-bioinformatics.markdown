---
layout: post
title:  "Staying Organized as a Bioinformatician"
date:   2019-10-18 16:41:00 -0700
categories: organization bioinformatics 
---

# Tips for staying organized in Bioinformatics
One of my favorite redditors and moderator of r/bioinformatics u/apejefes had this to say:
>**Have a system. Stick to it like crazy glue.**

Staying organized as a Bioinformatician is an incredibly valuable skill, and one that I didn't have at first. During my annual performance review in 2018 both my PI and I decided that it was one of my weaker points and was holding me back from being as productive as I could be. Although I truly believe that the one thing that makes a difference is having **ONE SYSTEM** and **STICKING TO IT LIKE GLUE** is the best way to stay organized, I'm going to list the ways that I organized myself and my projects as someone out there may find it useful.

## 1. **Projects**
I keep my projects meticulously organized for sake of ease. There have been too many times where analysis needs to be repeated and without proper version control there is no way to redo analysis in the exact same way.
My projects have the following directory structure
```bash
.
├── analysis
├── code
├── data
├── docs
├── out
└── README.md
```
The **Analysis** folder is where I keep a Jupyter Notebook that acts as my lab journal. All of my motivations, activities, and small scale analysis/parsing is tracked in there. This directory also holds intermediate files I generate through this process.

**Code** is going to contain any scripts that I need to run (particularly PBS scripts for our cluster) more than once. 

**Data** contains all of my data, simply put. I have two subdirectories, **raw** and **processed** which are exactly as they sound. Raw data files are read only, effectively, and should not be altered (such as FASTQ). Processed data are the outputs from scripts and other things that need to be preserved and dated.

**Docs** contains any relevant literature, as well as manuscript drafts, presentations, posters. Anything that counts as a document that needs to be...well...documented should go here.

**Out** contains figures for manuscripts and any analysis files that can be removed from the analysis folder. This is also a good place to store **timestamped/dated** processed data after analysis is complete. This way I can effectively work on a task for a few days in the **processed** data folder and move things to **out** when I am complete.

## 2. **Tracking Productivity**
I've found the best way to track productivity is a daily log/ task list. I have a repository of markdown format notes that keeps track of everything important at work (meetings, seminars/talks, daily-logs). The daily logs are in the following format:
* What I did during the day
* To-do list with markdown checkboxes

I've found that this reminds me of what I was doing yesterday, how productive I was/how to be more productive the next day, and what next steps I need to take to stay on task.

## 3. **Version Control**
Version control is your **number one friend**. I have gone through a hard drive failure, accidental rm -rf shenanigans, you name it. And every time my ass was saved purely by the fact that I could go to gitlab and review the history and find lost files. **LOSING TIME IN THE FORM OF DATA LOSS IS A MISTAKE YOU ONLY (WANT TO) MAKE ONCE**.