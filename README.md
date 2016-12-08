
#podcastpedia-batch

##Batch jobs for Podcastpedia.org, using currently Spring Batch with Spring Boot and Java Configuration
* http://www.codingpedia.org/ama/spring-batch-tutorial-with-spring-boot-and-java-configuration/

##Spring Batch Tutorial with Spring Boot and Java Configuration

I’ve been working on migrating some batch jobs for Podcastpedia.org to Spring Batch. Before, these jobs were developed in my own kind of way, and I thought it was high time to use a more “standardized” approach. Because I had never used Spring with java configuration before, I thought this were a good opportunity to learn about it, by configuring the Spring Batch jobs in java. And since I am all into trying new things with Spring, why not also throw Spring Boot into the boat…

##Contents

### 1. What I’ll build
### 2. What you’ll need
### 3. Set up the project
#### 3.1. Maven build file
#### 3.2. Project directory structure
### 4. Create a batch Job configuration
### 5. Spring Batch processing units
#### 5.1. Readers
##### 5.1.1. FlatFileItemReader
###### 5.1.1.1. LineMapper
###### 5.1.1.2. FieldSetMapper
#### 5.2. JdbcCursorItemReader
##### 5.2.1. RowMapper
#### 5.3. Writers
#### 5.4. Processors
### 6. Execute the batch application
#### 6.1. Running the application on dev and prod environments

##Summary
##Resources
##[Source Code – GitHub](https://github.com/PodcastpediaOrg/podcastpedia-batch)
##Web
##Note:
* Before you begin with this tutorial I recommend you read first Spring’s Getting started – [Creating a Batch Service](http://spring.io/guides/gs/batch-processing/), because  the structure and the code presented here builds on that original.
