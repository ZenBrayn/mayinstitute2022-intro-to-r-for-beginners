# May Institute 2022 – Introduction to R for Beginners

## ~~ TENTATIVE - INFORMATION AND MATERIALS IN PROGRESS ~~

**Date**: May 13th & 14th, 2022

**Time**: 11:00 AM – 2:15 PM (Eastern Time)

**Location**: Online via Zoom

## Overview

This hands-on workshop will cover essential basics of the [R Programming Language](https://www.r-project.org), focusing on key elements to help new R users start working with data.  The workshop will take place over two days, approximately 3 hrs. each day, and consist of interspersed lectures and hands-on practice sessions.

**Day 1 Topics**

* How to work with RStudio
* How to write and execute R code
* R Coding essentials
  * variables and variable assignment
  * vectors
  * functions
  * conditional expressions
* How to read data files into R
* How to work with Data Frames

**Day 2 Topics**

* Review of Day 1 exercises
* What is tidy data?
* Introduction to the tidyverse
* Introduction to dplyr and data manipulation pipelines
* Wrap-up, questions, and next-steps with learning resources

## Workshop Materials

Workshop materials are available online at: [https://computationalproteomics.khoury.northeastern.edu](https://computationalproteomics.khoury.northeastern.edu)

The same materials are also present in this repository and linked below:

**Day 1**

* [Lecture Slides](https://github.com/ZenBrayn/mayinstitute2022-intro-to-r-for-beginners/blob/main/lecture_slides/mayinstitute2022_intro_to_r_day_1.pdf)
* [Exercises – First Steps with R Coding](https://github.com/ZenBrayn/mayinstitute2022-intro-to-r-for-beginners/blob/main/exercises/day1_first_steps_with_r_exercises.R)
* [Exercises – Working with Data Frames](https://github.com/ZenBrayn/mayinstitute2022-intro-to-r-for-beginners/blob/main/exercises/day1_working_with_dataframes_exercises.R)
* [Exercise Data (.zip)](https://github.com/ZenBrayn/mayinstitute2022-intro-to-r-for-beginners/blob/main/data/exercise_data.zip)

**Day 2**

* [Lecture Slides](https://github.com/ZenBrayn/mayinstitute2022-intro-to-r-for-beginners/blob/main/lecture_slides/mayinstitute2022_intro_to_r_day_2.pdf)
* [Exercises – dplyr Basics](https://github.com/ZenBrayn/mayinstitute2022-intro-to-r-for-beginners/blob/main/exercises/day2_dplyr_basics_exercises.R)
* [Exercise Data (.zip) – Same as Day 1](https://github.com/ZenBrayn/mayinstitute2022-intro-to-r-for-beginners/blob/main/data/exercise_data.zip)

## Pre-workshop Set-up

We will be using [RStudio](https://www.rstudio.com) to practice R coding throughout the workshop.  Please make sure you have a working version of R and RStudio ready for use before the workshop.  There are two main ways you can get set-up:

1. Install R and RStudio on your own computer
2. Use a pre-configured, cloud-based R workspace on RStudio Cloud (requires free registration)

Both options are free, and either or both can be used.  Please see the additional set-up instructions below.

### Installing R and RStudio on your own computer

1. Install R for your platform from: [https://cloud.r-project.org](https://cloud.r-project.org)
2. Install *RStudio Desktop Open Source Edition* from: [https://www.rstudio.com/products/rstudio/download](https://www.rstudio.com/products/rstudio/download/#download)
3. Launch RStudio Desktop and confirm no warning messages or error messages appear.  R must be installed before RStudio, and if R is not installed properly, the application will display an error message.  If this happens, try installing R again and confirm successful installation.
4. Within RStudio
    1. Select *Tools -> Install Packages...*
    2. In the "Packages" text box, type `tidyverse`
    3. Click Install
    4. *Important*: if a message in the R console asks if you want to install packages from source, type 'no' and press return/enter.
    5. Get a cup of tea or coffee while the tidyverse R packages are installed (might take a while)
5. Download the exercise data ([GitHub Link](https://github.com/ZenBrayn/mayinstitute2022-intro-to-r-for-beginners/blob/main/data/exercise_data.zip)), unzip the file and have it available for the workshop.  We will cover what to do with this data during the workshop

### Using RStudio Cloud

1. Register for a free RStudio Cloud account at: [https://rstudio.cloud/](https://rstudio.cloud/)
2. Click the RStudio Cloud workspace link provided in the Workshop Document on [https://computationalproteomics.khoury.northeastern.edu](https://computationalproteomics.khoury.northeastern.edu)
3. Click "Save a Permanent Copy" at the top toolbar; the project is now accessible in "Your Workspace"
4. The necessary exercise files and data are ready to go in the workspace – no additional set-up is required


