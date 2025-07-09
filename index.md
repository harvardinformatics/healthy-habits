---
title: "[Workshop] Healthy habits for data science"
description: Multi-day workshop from Harvard FAS Informatics covering best practices for file organization and software management, emphasizing reproducibility.
authors:
    - Adam Freedman
    - Danielle Khost
    - Lei Ma
    - Tim Sackton    
    - Gregg Thomas
author_header: Workshop Developers
---

# Healthy habits for data science

{{ author_row(page) }}

This workshop aims to teach students how to be more effective at working on their projects using reproducible habits. We learn how to organize projects on the local machine as well as the Cannon cluster, how to manage software environments, how to use git and GitHub to track code changes, and how to write and scale scripts on an HPC. 

## Before Class

Hello! While the Healthy Habits workshop is open to students of any computational skill-level, there are several things you'll need to do BEFORE class. 

### 1 . Basic command line knowledge

This workshop assumes you have some basic knowledge of the Linux command line. If you know several simple commands like `ls`, `cd`, `cp`, and `mv` you should be ok. However, we won't be teaching these basics in this course, so if you aren't familiar with them you may find the course difficult to follow. 

### 2. FASRC Account

A majority of this workshop will take place on the [FASRC cluster :octicons-link-external-24:](https://www.rc.fas.harvard.edu/cluster/){:target="_blank"}, so you will need a FASRC account to be able to follow along. If you do not have one, please use the link below to request one. 

[How to: Request FASRC account :octicons-link-external-24:](https://docs.rc.fas.harvard.edu/kb/how-do-i-get-a-research-computing-account/){:target="_blank" .md-button .md-button--primary .centered }

!!! warning "Confirm you can login to the cluster before class!"

    Whether you already have a FAS RC account or are requesting one for the first time, you must confirm that you can login to the cluster with your FAS RC account before class by replying to the e-mail you received with info about the workshop. 

### 3. GitHub account

We'll be using the version control program [git :octicons-link-external-24:](https://git-scm.com/){:target="_blank"} and the hosting platform [GitHub :octicons-link-external-24:](https://github.com){:target="_blank"} for some of the exercises. If you don't have a GitHub account, please use the link below to create one. If you already have an account, please make sure you are able to login before the workshop starts.

[GitHub :octicons-link-external-24:](https://github.com){:target="_blank" .md-button .md-button--primary .centered }

### 4. RStudio (recommended for Day 4)

On the last day, we'll be re-creating a figure in a paper using R and Rstudio. We'll do this locally on your computer (rather than on the cluster), so if you don't have R and RStudio installed, please use the links below to download and install them. 

[Download R and RStudio :octicons-link-external-24:](https://posit.co/download/rstudio-desktop/){:target="_blank" .md-button .md-button--primary .centered }

---

## Workshop content

Workshop content is available below. Loose transcripts of the lectures are available and download the pdfs of the slides (if applicable) to follow along with the lecture. 

### Day 1: Reproducibility, and project organization

Wednesday March 13th, 9:30 am - 12:30 pm, Location: [Northwest Building :octicons-link-external-24:](https://maps.app.goo.gl/1MqNswcVaTYcCx68A){:target="_blank"} room 453 

* Intro to filesystems
* Navigating file systems from the command line
* Best practices for file organization
* Downloading and tansferring data

[Lecture Material :material-arrow-right:](healthy_habits_day1.md){ .md-button } & [Slides :octicons-download-24:](healthy_habits_day1_ppt.pdf){ .md-button }

### BONUS Day 1: Optimizing and customizing your data analysis tools

Thursday March 14th, 9:30 am - 12:30 pm, Location: [Biolabs :octicons-link-external-24:](https://maps.app.goo.gl/mtqAuyd1HwFRLJyZ6){:target="_blank"} room 2062/2064 

* The importance of text editors and why we recommend [VSCode :octicons-link-external-24:](https://code.visualstudio.com/){:target="_blank"}
* Editing files remotely with VSCode
* Transferring files with FTP clients
* Shell profiles
* [Terminal multiplexers :octicons-link-external-24:](https://en.wikipedia.org/wiki/Terminal_multiplexer){:target="_blank"} (e.g. [screen :octicons-link-external-24:](https://www.gnu.org/software/screen/){:target="_blank"}, [tmux :octicons-link-external-24:](https://github.com/tmux/tmux/wiki){:target="_blank"})

**This was a live demonstration and Q&A session, so there are no lecture materials available.**

### Day 2: Installing and Managing Software

Wednesday March 20th, 9:30 am - 12:30 pm, Location: [Northwest Building :octicons-link-external-24:](https://maps.app.goo.gl/1MqNswcVaTYcCx68A){:target="_blank"} room 453 

* Why is installing software so hard: permissions and dependencies
* Concepts of containerization (e.g. [Docker :octicons-link-external-24:](https://www.docker.com/){:target="_blank"}, [singularity :octicons-link-external-24:](https://docs.sylabs.io/guides/3.5/user-guide/index.html){:target="_blank"})
* Package managers (e.g. [pip :octicons-link-external-24:](https://pypi.org/project/pip/){:target="_blank"}, [CRAN :octicons-link-external-24:](https://cran.r-project.org/){:target="_blank"}, [conda :octicons-link-external-24:](https://docs.conda.io/en/latest/){:target="_blank"})
* Creating and managing software environments with [mamba :octicons-link-external-24:](https://mamba.readthedocs.io/en/latest/index.html)

[Lecture Material :material-arrow-right:](healthy_habits_day2.md){ .md-button }

### Day 3: Version control with [git :octicons-link-external-24:](https://git-scm.com/){:target="_blank"} and [GitHub :octicons-link-external-24:](https://github.com/){:target="_blank"}

Thursday March 21st, 9:30 am - 12:30 pm, Location: [Biolabs :octicons-link-external-24:](https://maps.app.goo.gl/mtqAuyd1HwFRLJyZ6){:target="_blank"} room 2062/2064 

* What is version control and why is it important?
* Intro to git and GitHub
* Managing your project history with git
* Collaborating on GitHub

[Lecture Material :material-arrow-right:](healthy_habits_day3.md){ .md-button } & [Slides :octicons-download-24:](healthy_habits_day3_ppt.pdf){ .md-button }

### Day 4: Running scripts on the Cannon cluster

Wednesday March 27th, 9:30 am - 12:30 pm, Location: [Northwest Building :octicons-link-external-24:](https://maps.app.goo.gl/1MqNswcVaTYcCx68A){:target="_blank"} room 453 

* More on reproducibility
* [jupyter notebooks :octicons-link-external-24:](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html){:target="_blank"} and [R Markdown :octicons-link-external-24:](https://rmarkdown.rstudio.com/articles_intro.html){:target="_blank"}
* Scaling up your analyses with the cluster
* Submitting jobs to SLURM

[Lecture Material :material-arrow-right:](healthy_habits_day4.md){ .md-button }

### BONUS Day 2: AI assisted coding and debugging

Thursday March 28th, 9:30 am - 12:30 pm, Location: [Biolabs :octicons-link-external-24:](https://maps.app.goo.gl/mtqAuyd1HwFRLJyZ6){:target="_blank"} room 2062/2064 

* Overview of large language models (LLMs; e.g. [ChatGPT :octicons-link-external-24:](https://openai.com/chatgpt){:target="_blank"}, [GitHub Copilot :octicons-link-external-24:](https://github.com/features/copilot){:target="_blank"})
* Writing tests for your code
* Debugging skills

**This was a live demonstration and Q&A session, so there are no lecture materials available.**

---