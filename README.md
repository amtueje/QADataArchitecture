# QADataArchitecture

This is a repository for the Data Architecture course, part of the QA Data Engineering bootcamp. It contains the practical labs that we worked through, my own interpretations of those labs, some of my coding in SQL and Python, as well as reflections and learning from the course. At the time of writing this **readme** is incomplete, but  will be updating it over the coming weeks as I review the material from the module.

## About the Module
Data Architecture was a four-day module completed, part of the data specialism section of the QA Data Engineering boocamp.
The module took us from the conceptual process of data architecture and moved us through thinking about and implementing the whole data life cycle; data mapping, ETL and ETL tools, creating schemas, building databases, and then interrogating them and producing visualsations.

It has been the most important module of the course (so far) because:
* It gets to the heart of how data engineers need to conceptualise their workflow
* It brought together a number of the other modules that we had studied so far (Python, Visualisation, SQL, Git) into real world scenarios.


## Module Reflection
As part of our module submission, we were asked to describe three important problems associated with data collection and processing:

### 1. Missing Data
Missing data (including missging rows, as well as rows that are present but missing data) present a major problem to data engineers, 

### 2. Incorrect calculations
Formulas and functions that have are incorrect may not be spotted in the ETL process and may give errors (in which case they can be traced and corrected) or may not - in which case they just give incorrect outputs that can become compounded further along the data chain. 

### 3. Incorrect Data Types
We may not know, although we can make good guesses, as to what the correct data types should be, but they can create errors that add time to the ETL process. A float and an integer are both numbers, but when we begin performing calculations, it is vital that our data is of the correct *type* so that it can output the values we need and expect.

### Other problems
One challenge that data engineers face is that the data they architect will have different end users with varying requirements. 

#### Data architects
May be more interested in the *availability* of the data, when and how can they access it.
#### Data analysts
It is the *quality* of the data that impresses data analysts most.
#### Data scientists
Will be primarily concerned with the *cleanliness and completeness* of the data, as well as any outliers and anomalies.

There are also many other problems associated with data collection that might be invisible to the data engineer, but that manifest in challenges in the processing of data, such as a lack of training in data collecting procedures; if employees are not sufficiently trained in how to collect data that is robust, the result will be data that is of an inferior quality.

## Self Reflection - What Did I Learn?
This course has provided me with a detailed overview of what data architecture is from a conceptual idea of how we think about data storage, the systems and processes we can employ to store, transform and then use data, as well as how the different tools that we use to perform these tasks work together (or sometimes, don't work together)

## Data design
Yes, data is a collection of facts, but good data design is so much more than that. We must think about what and who the data is for, how it will be accessed, when, and, perhaps most importantly, what *types* of data are we collecting and storing. One needs to understand the difference between a data warehouse and a data lake, why one might want one over the other (or the two in tandem). 
We need to understand these concepts in order to eventually extract the best information, queries and visualisations from our data.

## Tools and Methodologies
I wa pleased that the module integrated understanding of a number of the tools that we have used to this point (Python, Power BI, SQL), as well as extended and deepening that knowledge with use of Python libraries (Pandas and NumPy), designing our own schema using SQL, and creating visualisations (again, in Python, but using matplotlib).
I have also improved my knowledge of the important differences between a SQL and noSQL database and the applications the various applications and tools that can be used to handle both.

## Practical Work
The hands-on labs, building databases in SQL and Python and then interrogating them with Pandas were amazingly useful in showing how the different tools work together. I have used the built-in Python Requests library for some web scraping, but using pandas for interrogating databases was new to me, but I soon got the hang of it. One thing I still don't quite understand is when I would use Python and when SQL. For most things, you can use either one. 

The practical work for this module is the collection of labs, presented as Google Colab notebooks.