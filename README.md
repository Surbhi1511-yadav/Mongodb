# Mongodb

## NoSQL: ##
* NoSQL means Not Only SQL.
* It is a database used to manage unstructured data, where in the data is not stored in the tabular relations like relational database.
* It doesn't use tables for storing data.
* As compared to other days, we store more and more data.
* Used to store big data and real-time web applications.

Relational Database failed in solving some of the complex modern problems. Some of them are :
* Continuous change of nature of data.
  * Structured
  * Unstructured
  * Semi-structured
  * Polymorphic data

* Data Intergrity : Applications serve various users at different geo-locations in different time zones and they have to be up and run all the time to maintain the data intergrity.

* Cloud Computing : Applications are beoming distrubted and many moving towards cloud computing.

**Note : --> NoSQL is designed to overcome the problem faced in Relational Database and to also overcome Performance, Scalability, Data Modelling and Distrubtion limitations.**

### Structured Data ###
* Usually text files
* With defined column tiles and Data in rows.
* These Data can be visualized in the form of charts.
* Can be processed using data mining tools.

### Unstructured Data ###
* Unstrutured Data consists of E-mails, Video file, image file, Pdfs etc.
* These Files have nothing in common.
* Structured Information can be extracted from the unstructured data but this can be time consuming.

## NO SQL DATABASE TYPES ###
1. **Document Database:** In this the key is paired with the complex data structure called as document.
Example :  MongoDB

2. **Graph Stores:** In this type of database the networked data is stored. In which we can relate the database with the existing data.

3. **Key-Value Stores:**These are the simples NOSQL database. In this data is stored with a key to identify it. In some Key-Value database we can save the type of data along with it .
Example: Redis

4. **Wide-Column Stores:**Used to store large sets of data.
Example: Cassandra, Hbase etc.

## Difference Between SQL AN NoSQL ##
**SQL:**
* Primarily called Relational Database.
* Table-based database
* Vertically Scalable
* Example: Oracle, MS-SQL etc

**NoSQL:**
* Primilarly called non-relational or distrubted database
* Document based, Key-Value pairsand graph Databases.
* Horizontally scalable
* Example: MongoDB, Cassandra, etc.