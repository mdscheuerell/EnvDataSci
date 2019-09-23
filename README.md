# Introduction to Environmental Data Science

## Course overview

Science is about the discovery and sharing of information, but much of the process is often shrouded in mystery. The seemingly endless competition for limited research funding has led to the notions that "knowledge is power" and that data must be protected. These situations tend to slow scientific discovery by hindering larger synthesis efforts and the exploration of new ideas or methodologies. In addition, we are witnessing increasing examples where scientists are unable to successfully reproduce previous findings, bringing into question the integrity of the results.

Fortunately, however, we also find ourselves in the midst of an expanding community of developers and practioners of the tools and skills necessary for easier and more transparent design, analysis, and reporting of scientific studies. These advancements have also supported better documentation, management, and access to data, which has facilitated new and often remote collaborations. This relatively new field of "Data Science" is broadly defined, but generally combines elements of data literacy, computer programming, statistics, and graphic design. A data scientist is generally expected to identify relevant questions, gather data from multiple sources, organize it, extract meaningful information, and communicate the results.

This course will provide an overview of some data science tools and best practices that can be used to create transparent and reproducible workflows when working with environmental data. Students will learn how to translate raw data from field and lab studies into databases and "tidy" digital formats, which can then be used for plotting, statistical analyses, etc. Students will learn how to track the history of file changes (version control), collaborate online with others, and generate "recipes" for re-creating one's work. Although failure and frustration in science are common, the open science community tries hard to be welcoming and helpful. Thus, students will also learn how and where to ask for help when attempting something new (*e.g.*, How do I create X from Y?), debugging or fixing code (*e.g.*, What does this error message mean?), etc.

**Please note**: Although statistical analysis and plotting are very important in data science, this course will *not* focus on those aspects because there are others in the School of Aquatic and Fishery Sciences that do. Those include:

* FISH 454 - Ecological Modeling

* FISH 458 - Modeling and Estimation in Conservation and Resource Management

* FISH 546 - Bioinformatics for Environmental Sciences

* FISH 554 - Beautiful Graphics in R

* FISH 559 - Numerical Computing for the Natural Resources

* FISH 560 - Applied Multivariate Statistics for Ecologists


## Learning objectives

By the end of the quarter, students should be able to:

* Use **Git** to commit changes to files, recover old versions, push/pull changes to remote repositories, and manage merge conflicts

* Use **GitHub** to create repositories, manage projects, open/comment/close issues, and submit pull requests

* Import and clean a messy data file using a variety of packages::functions in **R**

* Properly describe and document data using **Ecological Metadata Language**

* Create and access a relational database with **PostgreSQL** and **R**

* Use unit tests in **R** to evaluate code functionality

* Create a reproducible example to use in a quest for help

* Create a package in **R** and document its contents

* Use **R Markdown** to combine text, equations, code, tables, and figures into reports, websites, and presentations

* Create dynamic html reports with **Shiny**

## Instructor

[**Mark Scheuerell**](https://fish.uw.edu/faculty/mark-scheuerell/), Associate Professor  
School of Aquatic & Fishery Sciences

Office: Rm 220A Fishery Sciences

Email: [scheuerl@uw.edu](mailto:scheuerl@uw.edu)

## Credits

This course is {X} credits.

## Meeting times

MWF at {time} in Rm {room number} Fishery Sciences
  
Office hours by appointment.

## Pre-requisites

Students should have a working knowledge of the [**R**](https://www.r-project.org/) computing software, such as that provided in FISH 552/553. 

## Technology

Class materials (slides, code) will be available electronically via the [course website](address here).  

### Hardware

This course will revolve around hands-on computing exercises that demonstrate the topics of interest. Therefore, students are strongly recommended to bring their own laptop to class, although students are certainly free to work with one another. **For students without access to a personal laptop**: it is possible to check out UW laptops for an entire quarter (see the [Student Services office](https://education.uw.edu/admissions/office-of-student-services) for details).

### Software

All of the software we will be using is platform independent, meaning students are free to use macOS, Linux, or Windows operating systems. In addition to a web browser, students will need to have the following software installed on their computer.

#### Git

We will be using [**Git**](https://git-scm.com/downloads), a free and open source version control system for tracking changes to our files. 

#### R & R Studio

We will be using the free [**R**](https://www.r-project.org/) software and the desktop version of the [**R Studio**](https://www.rstudio.com/products/rstudio-desktop/) integrated development environment (IDE).  We will also be using various packages not contained in the base installation of **R**, but we will wait and install them at the necessary time.

#### GitHub

Students will be required to have a user account on [**GitHub**](https://github.com/), which we will be using for file hosting, project management, and some communications. If you do not already have an account, you can sign up for a free one [here](https://github.com/join?source=header-home).

## Teaching methodology

**Lectures**: What format will be used? Will students be required to complete readings or online quizzes before the class meets? How will lecture sessions be conducted (eg lectures, problem solving, group work, computing, use of classroom response systems, worksheets)?

**Labs**: What are the broad goals for the labs (eg interpretation, application, analysis)? How are the labs structured? Does each lab session stand alone, does the work involve field research, will the students conduct independent research projects? What will students need to do to prepare for the labs? What will students submit for evaluation?

## Evaluation

Students will be evaluated on their knowledge of course content via individual homework assignments (80%) and a final project (20%). Homework will be assigned on each Friday of weeks 1-8 and will be due by 11:59 PM one week later on the following Friday (weeks 2-9). The final project will be due by 11:59 PM on Monday, March 16. The instructor will evaluate and return student assignments within one week of their due date. No credit will be given for late assignments. Students should discuss any potential schedule conflicts with the instructor during the first week of class.

## Communication

This course will involve a *lot* of communication between and among students and the instructor. Short questions should be addressed to me via email; I will respond to your message within 48 hours. Detailed questions should be addressed to me in person--either after class or during a scheduled meeting. As the course progresses, we will also use some online tools for larger discussions and comments.

## Access & accommodations

All students deserve access to the full range of learning experiences, and the University of Washington is committed to creating inclusive and accessible learning environments consistent with federal and state laws. 

### Disabilities

If you have already established accommodations with Disability Resources for Students (DRS), please communicate your approved accommodations to me at your earliest convenience so we can discuss your needs in this course. If you have not yet established services through DRS, but have a temporary health condition or permanent disability that requires accommodations (*e.g.*, mental health, learning, vision, hearing, physical impacts), you are welcome to contact DRS at 206-543-8924 or via [email](mailto:uwdrs@uw.edu) or their [website](https://depts.washington.edu/uwdrs/). DRS offers resources and coordinates reasonable accommodations for students with disabilities and/or temporary health conditions.  Reasonable accommodations are established through an interactive process between you, your instructor(s) and DRS.

### Religious observances

Students who expect to miss class or assignments as a consequence of their religious observance will be provided with a reasonable accomodation to fulfill their academic responsibilities. Absence from class for religious reasons does not relieve students from responsibility for the course work required during the period of absence. It is the responsibility of the student to provide the instructor with advance notice of the dates of religious holidays on which they will be absent. Students who are absent will be offered an opportunity to make up the work, without penalty, within a reasonable time, as long as the student has made prior arrangements.

## Academic integrity

Faculty and students at the University of Washington are expected to maintain the highest standards of academic conduct, professional honesty, and personal integrity (see the [University of Washington Student Conduct Code](https://www.washington.edu/cssc/for-students/academic-misconduct/)). Plagiarism, cheating, and other academic misconduct are serious violations of the Student Conduct Code. The whole basis for this course is the notion of "open science": creating a *transparent* and *reproducible* description of your workflow. Thus, I have no reason to believe that anyone will violate the Student Conduct Code, but *I will have no choice* but to refer any suspected violation(s) to the College of the Environment for a Student Conduct Process hearing. Students who have been guilty of a violation will receive zero points for the assignment in question.

## Classroom conduct

I am dedicated to providing a welcoming and supportive environment for all people, regardless of background or identity. Any form of language or behavior used to exclude, intimidate, or cause discomfort will not be tolerated. This applies to all course participants (instructor, students, guests). In order to foster a positive and professional learning environment, I encourage the following kinds of behaviors:

* Use welcoming and inclusive language

* Be respectful of different viewpoints and experiences

* Gracefully accept constructive criticism

* Show courtesy and respect towards others

**Please note**: If you believe you have been a victim of an alleged violation of the Student Conduct Code or you are aware of an alleged violation of the Student Conduct Code, you have the right to [report it to the University](https://www.washington.edu/cssc/for-students-2/).

## Safety

If you feel unsafe or at-risk in any way while taking any course, contact SafeCampus, 206-685-7233 anytime--no matter where you work or study--to anonymously discuss safety and well-being concerns for yourself or others. SafeCampus can provide individualized support, discuss short- and long-term solutions, and connect you with additional resources when requested.  For a broader range of resources and assistance see the Husky Health & Well-Being website.

## Schedule

| Week | Topic |
| :--: | :---- |
|   1  | Success through failure <br> Using GitHub for projects <br> Markdown in GitHub <br> How to ask for help |
|   2  | Version control with Git <br> Using R Studio with Git and GitHub|
|   3  | Importing and cleaning data I |
|   4  | Importing and cleaning data II <br> Ecological metadata |
|   5  | Principles of database design <br> Creating databases with PostgreSQL |
|   6  | Intro to R Markdown <br> Creating pdf reports |
|   7  | Creating websites with R Markdown <br> Creating presentations with R Markdown |
|   8  | Creating R packages <br> Unit tests <br> Package documentation |
|   9  | Using Shiny to create Dynamic reports |
|  10  | Presentations of final projects |
