# Plagiarism-detection
Programmed a Java-based application using JavaFX and Java Server Pages to compare documents
and calculate similarity percentages with 95% accuracy.

# Overview of Implementation:
Implemented our project on Plagiarism Detection as a standalone application and as a web application. In the standalone application we make use of various features of Java
including javafx and jdbc. And in the web application we have used jsp and jdbc.
Our project takes in 2 files in the form of documents or in the form of 2 texts entered by the
user. It preprocesses and calculates the similarity and prints the percentage of similarity.

Preprocessing of data:
1. Stopwords and punctuation marks removal: Stop words include pronouns(he, she,
this, that, etc), conjunctions(and, or, but, yet, etc) and prepositions(at, on, in , from,
etc).
2. Ngrams creation: This is the most important pre processing done for comparison of 2
texts. It includes dividing a line of text to grams ( or phrases) of N words. We have
conveniently taken N as 3. We divide the text into grams of 3 and save it in a
database.

MySQL database is used to store the data for both the web-based and standalone
applications. A JDBC driver enables the Java applications to interact with a database.
MySQL Connector is the JDBC driver which has been used for MySQL.