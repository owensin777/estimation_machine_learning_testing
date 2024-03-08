# Estimation, machine learning and testing

## Description
This course provides the intuition and skills required to design, implement, test and validate a variety of supervised learning models. We cover the basics of statistical learning including modelling with the goal of prediction versus inference, prediction accuracy and model interpretability trade-off, and the bias-variance trade-off. Each section of this course will cover a unique set of methods used for supervised learning on real data sets.

## Learning Outcomes
By the end of the course, students will:
1. Implement and interpret the results from several supervised learning approaches for regression and classification
2. Utilize resampling methods to extract more information from a data set and to choose the best model
3. Perform exploratory data analysis for unsupervised learning
4. Determine what is required for reproducible learning
5. Analyze the uncertainties associated with model results and the ethical consequences of acting on these results
6. Explain the different trade offs and considerations for the statistical methods in their toolkit to both technical and non-technical audiences

## Logistics

### Course Contacts
**Questions can be submitted to the #questions channel on Slack**

* Instructor: **{Name}** {Pronouns}. Emails to the instructor can be sent to {first_name.last_name}@mail.utoronto.ca.
* TA: **{Name}** {Pronouns}. Emails to the instructor can be sent to {first_name.last_name}@mail.utoronto.ca.

### Requirements
* Learners are not expected to have any coding experience, we designed the learning contents for beginners.
* Learners are encouraged to ask questions, and collaborate with others to enhance learning.
* Learners must have a computer and an internet connection to participate in online activities.
* Learners must have VSCode installed with the following extensions: 
    * [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
* Learners must not use generative AI such as ChatGPT to generate code in order to complete assignments. It should be use as a supportive tool to seek out answers to questions you may have.
* We expect learners to have completed the [onboarding repo](https://github.com/UofT-DSI/Onboarding/tree/tech-onboarding-docs).
* Camera is optional although highly encouraged. We understand that not everyone may have the space at home to have the camera on.

### Delivery of Module
The module will run sychronously up three times a week on Zoom. The first three days are used as "lectures" and will last a maximum of 3 hours. During this time, the instructor will introduce the concepts for the week. The last day is used for as optional, asychronous work periods. The work periods will also last for up to 3 hours. During the work period, an instructor or TA will be present on Zoom to assist learners reach the intended learning outcomes.

### How the Instructor will deliver
The instructors will introduce the concepts through a collaborative live coding session usiing the Python notebooks found under `/01-slides`. All instructors will also upload any live coding files to this repository for any learners to revisit under `/live-code`.
 
### Expectations
Learners are encouraged to be active participants while coding and are encouraged to ask questions throughout the module.

## Class Schedule

### Class Topics

| Class | Date                   | Topic                                                                               |  Resources | ISLR2/ISLP Chapter |
|--------|------------------------|-------------------------------------------------------------------------------------|------------| --------|
| 1      | TBD    | Key Concepts of Statistical Analysis <br> Simple linear regression       | [Slides](./01-slides/6.1-Introduction_to_Statistical_Learning_slides.pdf) | 2
| 2      | TBD   | Multiple linear regression, interactions, qualitative predictors <br>                         | [Slides](./01-slides/6.2-linear-regression.pdf) | 3            
| 3      | TBD   | Classification (logistic regression, generative models)                     | [Slides](./01-slides/6.3-classification.pdf) | 4                    
| 4      | TBD     |  Resampling methods (CV, bootstrap) and Linear model selection and regularization         | [Slides1/2](./01-slides/6.4-resampling-methods.pdf), [Slides2/2](./01-slides/6.5-linear-model-selection.pdf)  | 5, 6               
| 5      | TBD      | Review of last session's content                                     | [Slides1/2](./01-slides/6.4-resampling-methods.pdf), [Slides2/2](./01-slides/6.5-linear-model-selection.pdf)  | 5, 6       
| 6      | TBD        | Introduction to unsupervised learning                           | [Slides](./01-slides/6.10-Unsupervised_Learning_slides.pdf) | 12,13                           

## Grading Scheme

Grading is based on three components: 3 assignments, and class participation. The grading scheme is as follows:

| Assessment       | Number |  Individual Weight | Cumulative Weight
|------------------|--------|--------------------|------------------|
| Assignments      | 3      |  25%               | 75%              |
| Participation    | NA     |  NA                | 25%              |

**Assignments**

Assignments will cover key statistical concepts and related code implementation. The assignments are to complete according to the schedule below, for a total of 3 assignments. Assignments will be introduced in class, can be discussed in tutorial, and questions can be ask of the Instructor and/or TA over email. Assignments are due by 11:59PM on the day they are due. Please arrange for extensions *in advance* with the Instructor or the TAs. Assignments should be submitted through the correct Google Forms link found below following the naming convention `firstname_lastname_a#`.

Assignments can be found in the `Assignments` directory, above. We've included an .html file (knitted Markdown file) for easy reading, as well as Jupyter Notebook files, that can be edited for submission. (To download files, click Raw > Save as.)

Note: If the assignment requires some content we end up not covering in class (i.e., we've fallen behind), it will be removed from the assignment / not be graded (you're welcome to submit answers if you like). Any questions that are removed will be determined and clearly indicated in the class before the assignment is due.

**Assignment Due-dates**

| Assessment        | Content         | Due Date                         | Submission Link |
| ------------------| ----------------|----------------------------------| ------------------ |
| Assignment 1      | Classes 1, 2, 3   |  TBD | Your Drive Folder |  
| Assignment 2      | Classes 4, 5   |  TBD     | Your Drive Folder |
| Assignment 3      | Classes 3, 4, 6     |  TBD    | Your Drive Folder |

## Policies
* **Accessibility:** We want to provide an accessible learning environment for all. If there is something we can do to make this course more accessible to you, please let us know.
* **Course communications:** Communications take place over email or on Slack. If communicating over email, please include "DSI-EMT" or similar in the subject line, e.g. "DSI-EMT: stats question"
* **Camera:** Keeping your camera on is optional.
* **Microphone:** Please keep microphones muted unless you need to speak. Please indicate your name before speaking as some Zoom configurations make it hard to tell who is talking!
* **Assessment:** There will be homework which **is not** graded, but highly recommended, and there will be two assignments which **are** graded.

## Resources
Feel free to use the following as resources:

#### Documents
- [Cheatsheet](./05-review_session_material/DSI%20emlt-cheat%20sheet%202.pdf)
- [Cross Validation - Basic Idea and Steps](./05-review_session_material/Cross%20validation%20-%20basic%20idea&steps.pdf)

#### Simple Linear Regression
- [Linear Regression, explained in 2 minutes](https://www.youtube.com/watch?v=CtsRRUddV2s)
- [Linear Regression, Clearly Explained!!!](https://www.youtube.com/watch?v=7ArmBVF2dCs&pp=ygUic2ltcGxlIGxpbmVhciByZWdyZXNzaW9uIHN0YXRxdWVzdA%3D%3D)

#### Multiple linear regression, interactions, qualitative predictors
- [Multiple Regression, Clearly Explained!!!](https://www.youtube.com/watch?v=EkAQAi3a4js&pp=ygUic2ltcGxlIGxpbmVhciByZWdyZXNzaW9uIHN0YXRxdWVzdA%3D%3D)

#### Classification (logistic regression, generative models)
- [Logistic Regression, explained in 3 minutes](https://www.youtube.com/watch?v=EKm0spFxFG4)
- [StatQuest: Logistic Regression](https://www.youtube.com/watch?v=yIYKR4sgzI8&list=PLblh5JKOoLUKxzEP5HA2d-Li7IJkHfXSe)
- [StatQuest: Linear Discriminant Analysis (LDA) clearly explained.](https://www.youtube.com/watch?v=azXCzI57Yfc&pp=ygUNTERBIHN0YXRxdWVzdA%3D%3D)
- [StatQuest: K-nearest neighbors, Clearly Explained](https://www.youtube.com/watch?v=HVXime0nQeI&pp=ygUNa25uIHN0YXRxdWVzdA%3D%3D)
- [Naive Bayes, Clearly Explained!!!](https://www.youtube.com/watch?v=O2L2Uv9pdDA&pp=ygUaYmF5ZXMgY2xhc3NpZmllciBzdGF0cXVlc3Q%3D)

#### Resampling methods (CV, bootstrap) and Linear model selection and regularization
- [Linear Modelling](https://www.youtube.com/watch?v=-inJu1jHqb8)
- [Machine Learning Fundamentals: Cross Validation](https://www.youtube.com/watch?v=fSytzGwwBVw&pp=ygUYdmFsaWRhdGlvbiBzZXQgc3RhdHF1ZXN0)
- [Bootstrapping Main Ideas!!!](https://www.youtube.com/watch?v=Xz0x-8-cgaQ&pp=ygUXYm9vdHN0cmFwcGluZyBzdGF0cXVlc3Q%3D)

#### Tree-based methods
- [Tree-based methods, explained in 8 minutes](https://www.youtube.com/watch?v=sN5ZcJLDMaE)
- [Regularization, explained in 12 minutes](https://www.youtube.com/watch?v=pJ5c_uLeg2A)
- [Decision and Classification Trees, Clearly Explained!!!](https://www.youtube.com/watch?v=_L39rN6gz7Y&pp=ygUXZGVjaXNpb24gdHJlZSBzdGF0cXVlc3Q%3D)
- [Regression Trees, Clearly Explained!!!](https://www.youtube.com/watch?v=g9c66TUylZ4&pp=ygUXZGVjaXNpb24gdHJlZSBzdGF0cXVlc3Q%3D)
- [Boosting](https://www.youtube.com/watch?v=GM3CDQfQ4sw&pp=ygUQdWRhY2l0eSBib29zdGluZw%3D%3D)
- [Statistical Learning: 8.6 Bayesian Additive Regression Trees](https://www.youtube.com/watch?v=xWhPwHZF4c0&pp=ygUUQkFSVCBzdGFuZm9yZCBvbmxpbmU%3D)

#### Support Vector Machines
- [Support Vector Machines Part 1 (of 3): Main Ideas!!!](https://www.youtube.com/watch?v=efR1C6CvhmE&pp=ygUOc3ZtcyBzdGF0cXVlc3Q%3D)

#### Survival Analysis, Principal Components Analysis, Ethics/Inequity/Reproducibility
- [Mini Lecture: Survival Analysis](https://www.youtube.com/watch?v=t6vdjwhauF8&pp=ygUsYmlvc3RhdGlzdGljcyBtaW5pIGxlY3R1cmUgc3Vydml2YWwgYW5hbHlzaXM%3D)

### How to get help
![image](/Steps%20to%20ask%20for%20help.png)

<hr>

## Folder Structure

```markdown
|-- 01-slides
|-- 02-assignments
|-- 03-exercises
|-- 04-homework
|-- 05-review_session_material
|-- 06-instructors
|-- .gitignore
```

* **slides:** Course slides as interactive notebooks (.ipynb files)
* **pdf slides:** Course slides as PDF files
* **live-coding:** Notebooks from class live coding sessions
* **exercises:** Work to be done alongside the lectures
* **homework:** Optional homework to practice concepts covered in class
* **assignments:** Graded assignments
* **review_session_material**: Contains review materials
* **instructors:** Instructions for the Instructor on what to teach
* README: This file!
* .gitignore: Files to exclude from this folder, specified by the instructor


## Acknowledgements
Rohan Alexander supervised the development of this course. The first slides were developed by Simone Collier. Slides have been created and modified by Navona Calarco and Julia Gallucci for Winter 2023. Materials were re-developed from R to Python by Inessa De Angelis in Fall 2023. This course draws extensively on *An Introduction to Statistical Learning with Applications in R* (2nd edition, 2021), by Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani and *An Introduction to Statistical Learning with Applications in Python* (2023) by Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani, and Jonathan Taylor. The structure of the repos were heavily organized and modified by Vishnou Vinayagame and Daniel Razavi in Winter of 2024.
