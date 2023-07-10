<!-- The (first) h1 will be used as the <title> of the HTML page -->

# Zonghan Wu

<!-- The unordered list immediately after the h1 will be formatted on a single
line. It is intended to be used for contact details -->

:family_man_woman_girl:&nbsp;&nbsp;Male, 1991.1.21, Married  
:phone:&nbsp;&nbsp;18616703467  
:email:&nbsp;&nbsp;<a476678244@163.com>  
:house:&nbsp;&nbsp;From Shandong Rizhao, living in Shanghai Pudong  
[Github](https://github.com/476678244)  

Worked as a software engineer for 10 years, 5 years experience in Supply Chain Management Domain, 7 years experience in Big Data Engineering (Batch & Streaming).



## Education

#### <span>Tongji University</span> <span>2009 ~ 2013</span>
- Bachelor`s Degree in Software Engineering

- CET6

  

## Skills

- Scala, Java, Python

- Spark(RDD, Dataframe, Pyspark), Flink, Hadoop, AWS

- Spring, Airflow, Docker, Kafka

  

## Working Experience

#### Afterpay(SQ), ML Feature Engineering Team (Risk Management)

> Big Data Engineer, 2022.1 ~ Current

##### Projects:

- Batch Feature Self-serve Platform: A Self-serve platform for users (BA and DS) to manage batch feature pipelines(airflow dags).

  - I refactored the legacy self-serve tool (by PR review), performance tuning and stability improving to the single node airflow server. 
  - Core contributor on DDF migration(single node Airflow -> Afterpay Airflow Platform) and snowflake migration(Redshift -> Snowflake).
  - I initiated the new batch self serve platform(based on Snowflake & GUI) and leading the project development.

    ***Skills: Pyspark, AWS Glue, Airflow, Redshift, Snowflake, Cassandra, Kubernetes, AWS Cloudwatch, Buildkite***

- Streaming Feature Self-serve Platform: A Self-serve platform for users (BA and DS) to manage streaming feature pipelines(flink jobs).

  - I implemented the Flink SQL & YML file auto generation logic and wrote an S3 DB(data storing in S3 file system) which is friendly to use for aws lambda running env.
  - I wrote a flink job restarting framework which reduced huge manual effort when maintaing large number of flink jobs.

    ***Skills: Flink, S3, AWS Lambda, Cassandra, Kafka, Datadog, Buildkite***

    

#### Coupang(CPNG), SCM Tip&Roq Team (Supply Chain Management)

> Big Data Engineer, 2016.11 ~ 2022.1

##### Projects:

- PO Automation: Core & Fresh.

  - I tuned performance of core daily job, reduced time consuming 30 minutes -> 5m. I tuned performance of fresh daily job, reduced the main time cost data calculator from 10m -> 2m.
  - I refined data input/output method using reflection and annotation to fix the pain point of file unstable read/write function. 
  - I integreted quantile forecast into system and push it to production via A/B testing.

    ***Skills: Spark RDD, Redshift, Spring boot, Airflow, Kafka, Task Engine (A self innovated framework for managing spark job: can view, submit, monitor and kill spark job as a web server instead of oozie UI.)***

- SCM Intelligence Platform: A python written intelligence platform supporting data scientists and engineers to develop scientific models for our ordering system.

  - I worked with another two principle engineers to brainstorm this project and contributed most of the code. 

  - I implemented the first version of long term inbound simulation using DP algorithm. I introduced CPLEX optimizer into using to solve the pain point of low performance. 

  - I am also the bridge between engineering and data science. Once data scientist design a new model, I am able to implement it from engineer perspective.
  
  
    ***Skills: PySpark, Django, Gunicorn, Nginx, Ortools, CPLEX, Docker, pyecharts***

- OOSA and ScrapA (along with OOS Prediction and Scrap Prediction): Decision tree model to analyse and reduce OOS(out of Stock) and Scrap in fresh business. We built data platform for OOS data and Scrap data along with main reason recommended.

  - I worked with former tech lead to design OOSA and independently designed Scrap analysis decision tree though lack of PO role at that time([US 10713622 B1](https://patft.uspto.gov/netacgi/nph-Parser?Sect1=PTO2&Sect2=HITOFF&p=1&u=%2Fnetahtml%2FPTO%2Fsearch-bool.html&r=1&f=G&l=50&co1=AND&d=PTXT&s1=%22Wu%3B+Zonghan%22&OS=%22Wu;+Zonghan%22&RS=%22Wu;+Zonghan%22)).

  - OOS Prediction and Scrap Prediction are my self-innovated projects. Using Convolutional Neural Netowork to predict and prevent OOS/Scrap in advance, aiming to introduce more intelligence functions to solve SCM area problems.

  - Project show on [Fresh Scrap Prediction in Coupang Reveal 2020 developer conference](https://www.youtube.com/watch?v=NcRfDcJ-fzQ&ab_channel=CoupangReveal)

    ***Skills: Redshift, Ooziebiter, Sqoop, PySpark, Tensorflow, Keras***

    


#### Success Factors(SAP), Platform Service team (HR Management)
> Backend Engineer & New Employee Trainer, 2012.7 ~ 2016.9

##### Projects:

- Role Based Permission, Dynamic Group Refreshing, Hana/Oracle Migration Tool, SAP Smart Express
  - I started my career from intern role, working on unit test and improved test coverage to over 95%. 
  - Then I worked with global engineers to implement a role based permission service as a platform to be integrated with different product team(There existed a half and tough year, I was the single shanghai backend engineer facing to three QA members).   
  - I tuned performance of existing dynamic group refreshing logic which is the pain point in business. After that, I worked with tech leader to implement next version of refreshing system([US 20180159952 A1](https://patft.uspto.gov/netacgi/nph-Parser?Sect1=PTO2&Sect2=HITOFF&p=1&u=%2Fnetahtml%2FPTO%2Fsearch-bool.html&r=2&f=G&l=50&co1=AND&d=PTXT&s1=%22Wu%3B+Zonghan%22&OS=%22Wu;+Zonghan%22&RS=%22Wu;+Zonghan%22)). 
  - I learned from Hana Migration tool and developed my own Oracle Migration tool. I maintained a local Database and helped others to establish their test environments. 
  - At part time, I worked with one architect and one UI engineer to implement SAP Express system(tech show in SAP DKOM event) which got SAP Smart Office Prize that year.

​    ***Skills: Jboss, Seam, Oracle, Hana, JProfiler***
