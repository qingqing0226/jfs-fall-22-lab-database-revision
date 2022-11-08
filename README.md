# jfs-fall-22-lab-database-revision
Lab created by jfs-fall-22


Amazalt© - product page innit?
Scenario
Imagine you and your mob doing your daily retro, all of a sudden Omid walks in… Everyone gasps “oh no…”. He starts by saying that today is going to be a very exciting day.
Everyone gasps again “oh no…”. You will have to create your own lab today he utters.
Narrator: That was very exciting!  
You and your teammates start writing a doc in google…  
After reading the scenario, Johan says let’s have a chat. 😉

Initialize with spring.io (either via spring initializr or intelliJ directly)
Should use postgresql
Use data.sql and schema.sql to initialize database  
Host the database on elephant, or optionally using docker
Build a JPA-repo to interact with database
Create endpoints with spring-web
Connect to nextJS frontend

Specification
Must be able to
Add product to database
Get product(s) from database
Delete product from database
Should patch product in database
Should be able to
Commit crud operations from front end (?)
Must initialize database with predetermined data
May contain relational data between product categories
Should use TDD
Should not change table structure after DB is initialized
Mayhaps use docker :(

At the end of the day, you should be able to read and write from a database in SQL and see the result in postman. If you have time, connect it to a front-end application using next.js. Cascading superfun sheets are optional.

How do you initialize? Npm init, innit?





Data for  e-commerce

Product
id: a numerical, auto-generated Primary Key
title: A text field
price: a numerical value
description: a text field
Image: a text field
category_id : foreign key to category table


Category
id: a numerical, auto-generated Primary Key
category: A text field





