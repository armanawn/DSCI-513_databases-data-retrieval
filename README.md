# DSCI 513: Databases and Data Retrieval

How to retrieve data stored relational and non-relational database systems efficiently and effectively, and overview of how to create and modify database objects.

## License

© 2022 Arman Seyed-Ahmadi

Software licensed under [the MIT License](https://spdx.org/licenses/MIT.html), non-software content licensed under [the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) License](https://creativecommons.org/licenses/by-nc-sa/4.0/). See the [license file](LICENSE.md) for more information.

## Lectures

Find Panopto lecture recordings [here](https://ubc.ca.panopto.com/Panopto/Pages/Sessions/List.aspx?folderID=37c8f2c3-34ce-4712-bff5-aefd017560f4).

| #    | Topic                                                                    |
| :--- | :----------------------------------------------------------------------- |
| 1    | Introduction to databases, the relational model, SQL, basic queries      |
| 2    | Data types, filtering, derived columns and aliases, functions            |
| 3    | Aggregations, grouping, joins                                            |
| 4    | Creating, modifying, and dropping tables and rows, integrity constraints |
| 5    | Transactions, ACID, subqueries, set operations                           |
| 6    | Views, CTEs, window functions, indexing, query optimization              |
| 7    | Semi-structured data, non-relational databases, basic queries in MongoDB |
| 8    | Intro to big data, advanced queries in MongoDB, aggregation pipelines    |

## Lab assignments

There will be one lab assignment per week. We will follow the standard MDS lab deadlines.

## Quizzes

Quizzes will be **open book**, meaning you may consult course materials, online sources, etc. However, communication with other people during the quiz is strictly forbidden. See the MDS quiz instructions [here](https://ubc-mds.github.io/resources_pages/quiz/). For the dates/times of the quizzes, see the [MDS calendar](https://ubc-mds.github.io/calendar/).

## Installation

- The first step to setup the course's Conda environment is to run `conda install -c conda-forge nb_conda_kernels` in your **base** environment, but if you have done so already for another MDS course, skip this step.

- The Conda environment file for the course is [here](dsci513env.yml). To create the environment, run `conda env create -f dsci513env.yml` (you only need to do this once). Finally, select the `dsci513` kernel from within VS Code or JupyterLab.

## Course learning objectives

- Explain and justify the need for storing data in a database
- Describe tables, tuples, and attributes in the relational model
- Construct basic and advanced SQL statements to query relational databases
- Define and manipulate tables and tuples using data definition language
- Understand the usage of integrity constraints in relational databases
- Describe the concept of transactions and concurrency control
- Construct basic and advanced queries in a NoSQL DBMS

## Suggested material

Recommended:

- [Fehily, Chris. SQL: Visual QuickStart Guide, 3rd ed., Peachpit Press, 2008.](https://go.exlibris.link/tWGGwhRf)
- [DeBarros, Anthony. Practical SQL: A Beginner's Guide to Storytelling with Data, 1st ed., No Starch Press, 2018.](https://www.practicalsql.com/)
- [Matthew, Neil and Stones, Richard. Beginning Databases with PostgreSQL: From Novice to Professional, 2nd ed., Apress, 2005.](https://link.springer.com/book/10.1007/978-1-4302-0018-5)
- [Khan Academy's Intro to SQL course](https://www.khanacademy.org/computing/computer-programming/sql)
- [Software Carpentry's SQL tutorials](https://librarycarpentry.org/lc-sql/)
- [PostgreSQL Exercises](https://pgexercises.com/)

More advanced:

- [Ramakrishnan, Raghu and Gehrke, Johannes. Database Management Systems, 3rd ed., McGraw-Hill, 2002.](http://pages.cs.wisc.edu/~dbbook/)
- [Karwin, Bill. SQL Antipatterns: Avoiding the Pitfalls of Database Programming, The Pragmatic Bookshelf, 2010.](https://go.exlibris.link/JWzLR6ZL)
- [Celko, Joe. Joe Celko's SQL for Smarties: Advanced SQL Programming, Morgan Kaufmann, 2010.](https://go.exlibris.link/PGql723M)
