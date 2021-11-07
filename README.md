# Data_Wrangling_With_Ednet
 Data mining
 -You are just hired as a data analyst (Note1) in the newly formed analytics department of RiiiD,
which is a leading AI startup company specializing in providing learning resources and adaptive
practices to English learners in South Korea. On the first day of your job, you are invited to
attend a meeting with the business operation team in which you are briefed on the company’s
platform and then you are handed over a dataset (‘EdNet’) that was collected from this platform
over the last two years from over 700K users .
-This dataset logged detailed user activities while
they were interacting with systems. Intrigued by the sheer amount of data collected, your
manager is interested in how the analytics department can help to support the company's
missions to reimagine the learner’s experience using AI/ML/data analytics techniques. You are
asked to spend some time to look into the data and prepare a brief to your manager.
Specifically, your manager is looking for answers to the following questions.
1. (25 points) Who are the users? To answer this question, you will need to compile a user
profile table (Table 1) with information about users including
a. Overall practice volume and performance (e.g. # of questions answered, % of
questions answered correctly)
b. Learning activity (e.g. # lectures watched, # explanation read)
c. Add three additional metrics you would like to compute to describe users
Create a few plots to illustrate the information in the tables. Feel free to choose the type
of plots you think is appropriate.
2. (25 points) What are the questions/items? To answer this question, you will need to
compile a question profile table (Table 2) with information including
a. Question ID
b. Question Type
c. Number of times being practiced
d. Number of times answered correctly
Create a few plots to illustrate the information in the tables. Feel free to choose the type
of plots you think is appropriate.
3. (10 points) Design a modified metric of “accuracy” to fairly describe users’ ability by
taking into account the difficulty level as derived from Table 2. Describe the procedure to
compute the metrics. Be sure to be specific so that interns can use your pseudo code to
implement the metrics without much trouble.
BONUS (10 points), implement the proposed metrics and plot a histogram of the metrics


#EdNet dataset contains various features of student actions such as which learning material he have consumed, response, how much time he have spent for solving a given question or reading through expert’s commentary. And EdNet have some properties which is introduced following.

1. Large scale
EdNet is composed of a total of 131,441,538 interactions collected from 784,309 students of Santa since 2017. Each student has generated 441.20 interactions while using Santa on average. EdNet, based on those interactions, makes researchers possible to access to a large-scale real-world ITS data. Moreover, Santa provides a total 13,169 problems and 1,021 lectures tagged with 293 types of skills, and each of them has been consumed 95,294,926 times and 601,805 times, respectively. To the best of our knowledge, this is the largest dataset in education available to the public in terms of the total number of students, interactions, and interaction types.

2. Diversity
EdNet offers the most diverse set of interactions among all existing ITS data. The set of behaviors directly related to learning is also richer than other datasets, as EdNet includes learning activities such as reading explanations and watching lectures not provided by others. Such diversity enables researchers to analyze students from various perspectives. For example, purchasing logs may help to analyze student's engagement for learning. Also, contents information table is provided separately.

3. Hierarchy
EdNet has a hierarchical structure of different data points. To provide various kinds of actions in a consistent and organized manner, EdNet offers the datasets in four different levels each named KT1, KT2, KT3 and KT4. As the level of the dataset increases, the number of actions and types of actions involved also increase. The details and descriptions of each dataset is described below.

4. Multi-platform
In the age where students have access to various devices spanning from personal computers to smartphones and AI speakers, it is inevitable for ITSs to offer the access from multiple platforms. Accordingly, Santa is a multi-platform system available in iOS, Android and Web and EdNet contains data points gathered from both mobile and desktop.This allows the study of AIEd models suited for future multi-platform ITSs, utilizing the data collected from different platforms in a consistent manner.
across all users (or subset of users of your choices).
4. (30 points) Pick a user with a reasonable amount of activity (you will define the
“reasonableness” and specify the selection criteria) and create a dashboard that consists
of a series of plots to tell a story of this user’s activity patterns. For inspiration, you may
look at the user dashboard for fitness tracker such as Fitbit.
5. (10 points) Propose two tasks for your interns to work on. The first task is of
unsupervised/descriptive type and a second one is of supervised/predictive task. Please
provide clear specification of the tasks so that your interns can start to work right away.
You should try to propose tasks that are not attempted in the existing work with this
dataset.
BONUS (10 points): propose a reinforcement learning task
Deliverable:
● A google slide deck summarizing the above findings in the format of plots or tables
(those are not table 1 or table 2, but small tables you decide to use to present
information) or other contents as requested by your manager (such as those pertaining
to question 3,4 or 5). Please label clearly on the slide which question you are answering.
There are no lower/upper limits of the number of slides. Always keep the message
concise and effective and keep your audience in mind. In this case, it is your manager.
Please change the slides permission to editable, we will make comments on your slides.
Two summary tables in csv format, named, table1.csv and table2.csv for user table
(question 1) and item table (question2) respectively
● Please deposit the above items (a slide deck and two csv tables) into your own google
folder you are asked to create (where you put your strategy plan), under this folder,
create a folder named homework1. Please deposit the files there. Please don’t deposit
your finalized product until after the submission deadline.
● Please create a github account and upload codes and optionally other files necessary to
create your portfolio. You may create a github page to present your project, but this is
optional for this homework assignment.
● For submission on blackboard
○ Please upload a pdf version of your slide as your evidence of submission.
○ Please submit a link to your github account
