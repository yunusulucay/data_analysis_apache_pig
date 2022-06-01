# Data Analysis using Apache Pig

Basics of Apache Pig and making an analysis using Pig 

For installation :
https://www.geeksforgeeks.org/how-to-install-apache-pig-in-linux/

There are 3 types of Apache Pig usage: 

Interactive Mode (Grunt shell) − You can run Apache Pig in interactive mode using the Grunt shell. In this shell, you can enter the Pig Latin statements and get the output (using Dump operator).

Batch Mode (Script) − You can run Apache Pig in Batch mode by writing the Pig Latin script in a single file with .pig extension.

Embedded Mode (UDF) − Apache Pig provides the provision of defining our own functions (User Defined Functions) in programming languages such as Java, and using them in our script.

In this tutorial I have used batch mode and made the development using Batch Mode. I used Docker as a Hadoop environment. In my previous repo I created hadoop environment that have 1 namenode and 3 datanode on docker(https://github.com/yunusulucay/docker-hadoop-spark). I installed Pig on this system. 


