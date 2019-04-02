---
layout: post
title: Passing the AWS Certified Machine Learning Specialty Exam
tags: [MLS-C01, AWS, Exam, Specialty, ML, DL, AI]
feature-img: assets/img/pexels/action-ai-android-595804.jpg
thumbnail : assets/img/pexels/action-ai-android-595804.jpg
excerpt_separator: <!--more-->
---

I've been put off taking AWS Beta exams ever since the 2016 Security Specialty debacle, so when it came to the **AWS Certified Machine Learning Specialty Exam** *(MLS-C01)*, I decided to wait it out, and I took the 'real' exam the first day it was released.  In this post, I will go through my thoughts on the exam, and how to pass it. <!--more-->

_(* Actually it was the second day, but that sounds less dramatic!)_

## TL;DR
> - Exam should be called: **_The AWS Certified Artificial Intelligence (AI), Machine Learning (ML) and Deep Learning (DL) Specialty Exam_**
- Around 50% of the exam is focused on **pure Machine Learning** or Deep Learning
- While you don’t need a deep understanding of the statistical mathematics and probability behind the subject you need a **good working knowledge** of the key aspects and be able to do some simple maths
- AWS’s flagship ML/DL service - **AWS SageMaker** - is the single most mentioned service in the exam
- Understand how to architect **AWS's AI API services**
- At times there is a decidedly **Big Data** feel
- If you’re comfortable with ML/DL and AWS, **this exam is do-able**
- I am a Training Architect for **[Linux Academy](https://linuxacademy.com)**


## General Thoughts

Let's get this out of the way right up front;  The *AWS Certified Machine Learning Specialty Exam* should actually be called  **The AWS Certified Artificial Intelligence (AI), Machine Learning (ML) and Deep Learning (DL) Specialty Exam**.  Maybe that would have been too long of a title, but it would be more accurate.

Naming aside, this is still unlike any of the other AWS exams...

At the time of writing, each of the other AWS exams focuses on - as you would expect - the AWS services within the subject area of the exam.   This includes the Specialty exams which focus on a deep level of knowledge in their respective areas, Networking, Big Data and, Security but primarily through AWS services and AWS ethos.  

The AWS Certified Machine Learning Specialty Exam is different, as around 50% of the exam is focused on pure Machine Learning or Deep Learning. This means you could gain a reasonable percentage in this exam with no knowledge of AWS at all. _(But you wouldn't pass!)_ 

### Subject Breakdown
(As usual) forget the AWS Exam Guide, here is the breakdown:

Subject             | Percentage
--------------------|---------
ML/DL               | 50%
AWS SageMaker       | 25%
Other AWS Services  | 25%

Let's look into each of these subject areas in more detail:

## Machine Learning / Deep Learning

By far the biggest portion of the exam is dedicated to proving your knowledge of ML and DL.  While you don't need a deep understanding of the statistical mathematics and probability behind the subject you need a good working knowledge of the key aspects and be able to do some simple maths.

You need to have a solid grasp on these concepts:

- Understand the difference between **supervised**, **unsupervised** and **reinforcement** learning.
- Know the purpose behind **training**, **validation** and **testing** data and how its managed.
- Have a general understanding of **hyperparameters** and some of the common ones used by various algorithms.
- Understand **regularisation**, what it does and some ways to achieve it.
- Know about **regression**, and **gradient decent**.

You should know about 'input data':

- Data **Visualisation** using Jupyter notebooks, but also other tools like **AWS QuickSight**.
- Understand **Feature engineering** and when to use what technique.
- Know what to do when data in unbalanced or missing.

You need to know when to use **which model types** (algorithms) - and **what they are**, and some high level **configuration**:

- **Logistical Regression**
- **Linear Regression**
- **Support Vector Machines**
- **Decision Trees / Random Forests**
- **K-means Clustering**
- **K-Nearest Neighbours**

And you need to have a good understanding of **deep learning** models and their uses:

- **Convolutional Neural Networks** (CNN)
- **Recurrent Neural Networks** (RNN)

Many questions focus on how to **measure**, understand and improve the **performance** of ML/DL models.  You might get questions with graphs and charts, and be expected to make calculations.   You should understand:

- **Accuracy**
- **Gini Impurity**
- **Confusion Matrix**
- **F1 Score**
- **Sensitivity / Specificity**
- **Precision**
- **Recall**

All of the above is from the point of view of ML/DL computer science.  There is no AWS knowledge in the above.  That all follows on from here...

## AWS SageMaker

AWS's flagship ML/DL service - **AWS SageMaker** - is the single most mentioned service in the exam.  That should come as no surprise.  

AWS has dropped its 'support' for **AWS ML** which is no longer available to anyone who's not already using it - however, AWS ML still popped up in a couple of answers in this exam.

For the exam you should know:

- What SageMaker **actually is**, and generally speaking how it's architected
- How **Jupyter notebooks** fit into SageMaker and how they are used
- How to access **secure data**
- How to **secure a Jupyter Notebook**
- How you **train** models
- How to **deploy** models
- Know about **Hyperparameter Optimisation** 

It goes without saying that you should have a general knowledge of all the AWS optimized algorithms, including:
- **BlazingText**
- **Image Classification Algorithm**
- **K-Means**
- **K-Nearest Neighbours**
- **Latent Dirichlet Allocation**
- **Linear Learner**
- **Object2Vec**
- **Object Detection**
- **Principal Component Analysis (PCA)**
- **Random Cut Forest (RCF)**
- **Sequence-to-Sequence (seq2seq)**
- **XGBoost**

...as well as knowing how to import your own (or someone else's) custom algorithm from outside SageMaker.

## Other AWS AI Services

After all that heavy ML/DL is can seem like a little light relief to get a question or two about some of AWS's AI services.  But don't get complacent, for each of these you should have a good understanding of its use case, its limitations, and how they should be architected.  Especially make sure you understand how to combine these services together to make complete solutions. (These questions are a lot like 'AWS Architecture' questions.)

- **Rekognition** (Images and Video)
- **Polly**
- **Transcribe**
- **Lex**
- **Translate**
- **Comprehend**

## Other AWS Services

A good general understanding of AWS, to at least associate level, will see you through many of the AWS aspects of the questions you will face.  However there are some services that feature more than others, and at times there is a decidedly Big Data feel.

Make sure you are comfortable and preferably have experience with:

- **S3** including how to secure your data
- **Athena** including performance
- **Kinesis** Firehose and Analytics for moving data around and transforming
- **Elastic Map Reduce (EMR)** including with Spark
- **AWS Glue** 
- **QuickSight** including how it sources data from various other services

## Final Thoughts

So did this exam add anything to the _'which is harder 'pro' or 'specialty'_ debate?  Well from a 10,000-foot view the exam looked like a 'pro' exam:  

- The questions were wordy 
- The answers could be wordy
- The time limit is 3 hours 
- There are 65 questions

But at the end of the day, whether this is harder than a pro exam or not yet again falls to your background:

- **If you're new to ML/DL, this exam is hard.**
- **If you're new to AWS, this exam is hard.**
- **If you're comfortable with ML/DL and AWS, this exam is do-able.**

How to prepare for this exam depends a lot on your background.  There really is no substitute for getting hands-on, especially with AWS SageMaker.  AWS has a number of awesome pre-made example Jupyter notebooks should be seen as 'copy-n-paste' reference guides even for some production developments.  

**Now full disclosure** - I work for [LinuxAcademy.com](https://linuxacademy.com) as a Training Architect; I create courses, training materials and live practical based labs to help people learn all aspects of the AWS cloud.   Keep an eye on the Linux Academy site for courses to help you pass all the AWS exams.