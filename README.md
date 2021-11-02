<!-- The (first) h1 will be used as the <title> of the HTML page -->
# Zonghan Wu

<!-- The unordered list immediately after the h1 will be formatted on a single
line. It is intended to be used for contact details -->

:family_man_woman_girl:&nbsp;&nbsp;Male, 1991.1.21, Married  
:phone:&nbsp;&nbsp;18616703467  
:email:&nbsp;&nbsp;<a476678244@163.com>  
:house:&nbsp;&nbsp;From Shandong Rizhao, living in Shanghai Pudong  
[Github](https://github.com/476678244)  

Senior Backend Engineer in Coupang, core developer in team and focusing on supply chain process optimizing.

## Education

#### <span>Tongji University</span> <span>2009 ~ 2013</span>
- Bachelor`s Degree in Software Engineering
- CET6

## Skills

- Scala, Java, Python
- Spark, Hadoop, AWS
- Spring

## Working Experience

#### Coupang, SCM team(supply chain)
> Senior Software Engineer, 2016.11 ~ Current

##### Projects:

- Core PO Automation. Aiming for 100% po automation for Coupang online retailing business. We use long term inbound simulation(future 35 days) to help tuning ordering strategy.

  - My Role:  I tuned performance of core daily job, then reduced time consuming from 30 minutes to less than 5 minutes.  I refined data input/output method using reflection and annotation to fix the pain point of file unstable read/write function. I implemented the first version of long term inbound simulation using DP algorithm.
  - Skills: Spark RDD, Redshift, Spring boot, Oozie, S3/HDFS, Kafka, Task Engine (A self innovated framework for managing spark job: can view, submit, monitor and kill spark job as a web server instead of oozie UI.)

- Rocket Fresh Ordering Automation. Company level star project, aiming to be the first company in industry to make fresh business profitable.

  - My Role: I tuned performance of fresh daily job, reduced the main time cost data calculator from 10 minutes to less than 2 minutes. I integreted quantile forecast into system and push it to production via A/B testing.
  - Skills: Spark RDD, Redshift, Spring boot, Airflow, S3, Task Engine

- SCM Intelligence Platform. A python written intelligence platform supporting data scientists and engineers to develop scientific models for our ordering system.

  - My Role: I worked with another two principle engineers to brainstorm this project and contributed most of the code. I introduced CPLEX optimizer into using to solve the pain point of low performance. I am also the bridge between engineering and data science. Once data scientist design a new model, I am able to implement it from engineer perspective.
  - Skills: PySpark, Django, Gunicorn, Nginx, Ortools, CPLEX, Docker, pyecharts

- OOSA and ScrapA. Decision tree model to analyse and reduce OOS(out of Stock) and Scrap in fresh business. We built data platform for OOS data and Scrap data along with main reason recommended.

  - My Role: I worked with former tech lead to design OOSA and independently designed Scrap analysis decision tree though lack of PO role at that time. 
  - Skills: Redshift, Spark Dataframe, Ooziebiter, Sqoop

- OOS Prediction and Scrap Prediction. Using Convolutional Neural Netowork to predict and prevent OOS/Scrap in advance.

  - My Role: It is my self-innovated project. I aim to introduce more intelligence functions to solve SCM area problems.
  - Skills: PySpark, Tensorflow, Keras

- SCM Planning Website. A website for operation team to monitor daily ordering jobs and configure ordering strategies.

  - My Role: I self innovated two functions: Data monitoring to detect whether daily ordering result is in problem and tip roq story to track the log of ordering quantity change in the data flow.
  - Skills: Spring Boot, MongoDB

- Light Speed Ordering Automation. Company level strategic project, 15 minutes delivery in downtown areas.

  - My Role: I`m leading this project to make light speed ordering process from manually work to automation currently.
  - Skills: Spark RDD, Redshift, Spring boot, S3, Task Engine

#### Red, WMS team 
> Java Developer, 2016.9 ~ 2016.10
- Projects: Develop Red`s WMS system from scratch.
- Skills: JSP, Spring, Mybatis


#### SAP Success Factors, Platform Service team 
> Software Engineer I -> II & New Employee Trainer, 2012.7 ~ 2016.9
- Projects: Role Based Permission, Dynamic Group Refreshing, Hana/Oracle Migration Tool, SAP Smart Express
- My Role: I started my career from intern role, working on unit test and improved test coverage to over 95%. Then I worked with global engineers to implement a role based permission service as a platform to be integrated with different product team. There existed a half and tough year, I was the single shanghai backend engineer facing to three QA members. I tuned performance of existing dynamic group refreshing logic which is the pain point in business. After that, I worked with tech leader to implement next version of refreshing system. I learned from Hana Migration tool and developed my own Oracle Migration tool. I maintained a local Database and helped others to establish their test environments. At part time, I worked with one architect and one UI engineer to implement SAP Express system which got SAP Smart Office Prize that year. 
- Skills: Jboss, Seam, Oracle, Hana, JProfiler

## Highlights
#### Speech
- Fresh Scrap Prediction in Coupang Reveal 2020 developer conference
- SAP Smart Express in SAP DKOM

#### Patent
- Refreshing Framework, [US 20180159952 A1](https://patft.uspto.gov/netacgi/nph-Parser?Sect1=PTO2&Sect2=HITOFF&p=1&u=%2Fnetahtml%2FPTO%2Fsearch-bool.html&r=2&f=G&l=50&co1=AND&d=PTXT&s1=%22Wu%3B+Zonghan%22&OS=%22Wu;+Zonghan%22&RS=%22Wu;+Zonghan%22)
- Computer-implemented systems and methods for intelligent prediction of out of stock items and proactive reordering, [US 10,713,622 B1](https://patft.uspto.gov/netacgi/nph-Parser?Sect1=PTO2&Sect2=HITOFF&p=1&u=%2Fnetahtml%2FPTO%2Fsearch-bool.html&r=1&f=G&l=50&co1=AND&d=PTXT&s1=%22Wu%3B+Zonghan%22&OS=%22Wu;+Zonghan%22&RS=%22Wu;+Zonghan%22)

