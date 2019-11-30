# Homework_1

## 1 Problem description

The core idea of this project is to obtain Dianping app data and extract valuable information through data mining methods and draw some valuable conclusions about shops and users.

**research direction**

1. Draw a food map of Shenzhen based on the comments, likes, views, and ratings of each store in the public review. The map mainly contains information: the distribution of food types in each region, the distribution of high praise stores in each region, the distribution of people in each region, and so on. The presentation method can be combined with various forms such as heat map, bar chart, and pie chart.
2. Follow-up exploration: Based on the information mined from the public comments, combined with other dimensional data, we can create a model to predicts Shenzhen's house prices. We can train the model by crawling the data of intermediary houses such as Lianjia website as the dependent variable.

**data properties **

According to the knowledge we learned in this class, big data has 3V characteristics (volume, velocity, variety). Next, we will explain from these three aspects why Dianping data can be regarded as big data.

- volume: Currently, there are over one million authorized restaurants and over 200 million users in Dianping. The average comments an active users contributes to this app are more than 10 per day. So the amount of data created by the users in Dianping is of big volume.
- velocity: The MAU of Dianping app has exceeded 50 million. Each user will create content or access the app multiple times in a day. The data growth rate is of the data in Dianping is very fast.
- variety: There are various type of data in Dianping such as digital data (likes, comments), text data (comments, user information), media files (small videos, audio), etc.

## 2 Data dimension

The Dianping app contains multi-dimensional data. Here, we mainly focus on shops' data.

**Shop dimension **

Basic information: shop name, area (city, area, street), shop type

Evaluation: rating (comprehensive rating, taste, environment, service), number of reviews, number of likes, per capita consumption

Dishes: Recommended dishes, recommended prices, recommended dishes likes

Comments: Popular terms, comment time, comment details

## 3 Database type

In this project, we will use both relational and non-relational databases.

**Relational Database**

Basic information table: used to store the basic information of the store, such as store name, region, and store type. Most of this information is structured data. Once the store is created, it will basically not be changed, and it is suitable to be stored in a relational database.

Store evaluation form: It is used to store data such as store ratings, likes, and reviews. Such data changes over time and needs to be updated daily.

**Non-Relational Database **

User evaluation table: Considering that user evaluations are mostly text and video data, which are unstructured data. It is not easy to store them in a relational database, so they are stored in a non-relational database. The NLP algorithm can then be docked to extract the user's evaluation characteristics of the store.

**Time Series Database **

Time series database is a kind of non-relational database, which can process time series data efficiently.

However, considering that the data we crawled is static data, there is no time series data, so the time series database will not be used in this project.

## 4 Workflow

![屏幕快照 2019-11-30 下午11.35.39](/Users/Answer/Desktop/屏幕快照 2019-11-30 下午11.35.39.png)

## 5 Project Difficulties

1. Data availability. At present, many websites have set up anti-crawling mechanisms, and it is not known whether they will eventually get enough data.
