# Data Analysis using Apache Pig

Basics of Apache Pig and making an analysis using Pig 

![image](https://user-images.githubusercontent.com/42489236/171363833-78df2eb2-3dd8-409c-9286-1b4ccaff50c8.png)

For installation :
https://www.geeksforgeeks.org/how-to-install-apache-pig-in-linux/

There are 3 types of Apache Pig usage: 

Interactive Mode (Grunt shell) − You can run Apache Pig in interactive mode using the Grunt shell. In this shell, you can enter the Pig Latin statements and get the output (using Dump operator).

Batch Mode (Script) − You can run Apache Pig in Batch mode by writing the Pig Latin script in a single file with .pig extension.

Embedded Mode (UDF) − Apache Pig provides the provision of defining our own functions (User Defined Functions) in programming languages such as Java, and using them in our script.

In this tutorial I have used batch mode and made the development using Batch Mode so I write codes on Pig Latin. I used Docker as a Hadoop environment. In my previous repo I created hadoop environment that have 1 namenode and 3 datanode on docker(https://github.com/yunusulucay/docker-hadoop-spark). I installed Pig on this system. 

Implementation: 

In terminal to run the pig script -> pig -x mapreduce hdfs:///user/root/sample_script.pig

sample_script.pig file is a basic Pig Latin script file. In this file the followings implement respectively:
- Read the csv file in hadoop file system.
- Order data by age feature.
- Select only specified features.
- Show results or save the results. (After storing process run the described codes on terminal to merge.)

References:

https://www.tutorialspoint.com/apache_pig/index.htm

https://data-flair.training/blogs/hadoop-pig-tutorial/
