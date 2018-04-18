# MSBD5003 Project Proposal
## The Movie Database Rating Prediction and Recommendation System


### Group 23 Members:

------
* HE Jingting				ID:20470859
* PAN Zetao				ID:20459001
* ZHANG Zheng				ID:20476580
* ZHOU Xiaoyang			ID:20476736

------

## **Description of the task**

In our wide project, we plan to dispose the large scale of data from TMDb by several spark technologies. Our data of movies can be generally divided into two parts, the specific infomation of different movies, and the users' rating record on some of these movies. 

By analyzing the different features of all movies in TMDb, we can extract the main attributes of these movies and make some clustering. For the data of users, we plan to analyze the difference of rating for the same movie between the users and link them with the movie data to find out the movie preference for each user. 

Based on these data, we can easily predict a user's rating on a new movie. Also, we can build a recommendation system to recommend the movie to these users based on their preference. 

If everything goes smoothly as we can ever expect, we may try to get some different data from IMDB, which obviously contains more infomation of movies to improve our model. 

## **Description of the data sets**

The Movies Dataset

For These files contain metadata for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts and vote averages. The dataset also has files containing 26 million ratings from over 270,000 users for all 45,000 movies. Ratings are on a scale of 1-5 and have been obtained from the official GroupLens website.

## **Technologies**

Here are some technologies may be used in our project.

*RDD*

A Resilient Distributed Dataset (RDD), the basic abstraction in Spark. Represents an immutable, partitioned collection of elements that can be operated on in parallel. This class contains the basic operations available on all RDDs, such as map, filter, and persist.

*Spark SQL*

Spark SQL is a Spark module for structured data processing. Unlike the basic Spark RDD API, the interfaces provided by Spark SQL provide Spark with more information about the structure of both the data and the computation being performed.

*Spark Streaming*

Spark Streaming is an extension of the core Spark API that enables scalable, high-throughput, fault-tolerant stream processing of live data streams.

*MLLib*

MLlib is Apache Spark's scalable machine learning library.

*Azure App Service*

Quickly build, deploy, and scale enterprise-grade web, mobile, and API apps running on any platform. Meet rigorous performance, scalability, security and compliance requirements while using a fully-managed platform to perform infrastructure maintenance.