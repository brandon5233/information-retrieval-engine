Information Retreival System using TF-IDF Matrix

*****************************************************************
About: 
Reads a corpus of documents and builds a Term_Frequency - Inverted Document Frequency (TF-IDF) Matrix for quick lookup. 

Read a query. Using the TF-IDF Matrix, output a list of documents ordered by decreasing relevance.

******************************************************************
Steps:

PART 1 - building the lookup matrix 
1. Read the corpus of documents and stopword list
2. Remove stopwords and build a list of unique words.
3. Construct the TF-IDF matrix  
4. Output tf, idf, tf-idf matrix, and list of unique words (found in resources folder)

PART 2 - Answering queries
1. Read query 
2. Lookup tf-idf matrix and find relevant documents. 
3. Order documents by relevance scores and display them

*****************************************************************

The application is build using JDK 1.8_151

LAYOUT : 
The root folder called "Assignment" holds the entire project. It contains:
- Part1.java
- Part2.java
-Corpus      <==== fodler
-Query 	     <==== folder
-Resources   <==== folder
-stopword_list.txt


RUNNING INSTRUCTIONS:
-copy corpus files to Assignment1/Corpus folder
-copy query file to Assignment1/ (root folder)
-compile and run Part1.java to create index
-INVERTED INDEX IS OUTPUT AT THE ROOT FOLDER
-All other files (like tf, idf, sqrt sumproduct, etc) are output to the Assignment1/resources folder

**to run, compile and run Part1.java
**then compile and run Part2.java

NOTE : 
when running, Provide full path of the root folder INCLUDING SLASH
e.g. "home/users/desktop/Assignment1/"

where Assignment1 is root folder in which the whole project lies.

Copy the corpus text files into the Assignemnt1/Corpus folder 

**THE PROGRAM SUCCESSFULLY OUTPUTS DOCUMENT SIMILARITY SCORE, DOCUMENT NUMBER AND TITLE FOR EACH QUERRY**