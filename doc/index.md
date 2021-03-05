#### Jimmy Jimenez
#### 03/04/2021  
#### Database Foundations
<p align="center">  ### Week 7: User Defined Functions 

### Introduction
In this document I will be discussing when to use SQL User Defined Funcitons (UDF) and explain the differences between Scalar, Inline, and Multi-Statement Functions. 

### When to use a SQL User Defined Function (UDF)
A SQL UDF can be used when you would like to pass a parameter (fig.1) to return a value or perform
complex calculations. The function can be saved in the database and be called upon when needed as 
opposed to having to create the task when needed. (external source: https://www.tutorialgateway.org/user-defined-functions-in-sql/, 2021)

### Differences between Scalar, Inline, and Multi-Statement Functions
The difference between a Scalar function and an Inline function is that a Scalar funciton returns a single value and an Inline 
Function returns a table data type. 
What makes a Multi-Statement funciton different is that the table structure can be defined by the user. The user specifies the structure of the return table by declaring a table variable. (external source: https://database.guide/difference-between-multi-statement-table-valued-functions-inline-table-valued-functions-in-sql-server/, 2021)

## Summary
In summary, User Defined Functions can save someone time by being saved to the database and called on later for use when needed. User Defined Functions can be created to accomplish simple to complex queries. 
