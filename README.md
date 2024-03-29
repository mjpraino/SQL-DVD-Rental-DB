# SQL-DVD-Rental-DB
SQL Queries for a DVD rental DB as well as vizualizations for Udacity Programming for Data Science.

<h2>Introduction</h2>
<p>In this project, you will query the Sakila DVD Rental database. The Sakila Database holds information about a company that rents movie DVDs. For this project, you will be querying the database to gain an understanding of the customer base, such as what the patterns in movie watching are across different customer groups, how they compare on payment earnings, and how the stores compare in their performance. To assist you in the queries ahead, the schema for the DVD Rental database is provided below.</p>

<h2> Local Environment Setup </h2>

<p> <strong>What is PostgreSQL?</strong>

PostgreSQL is an object-relational database management system. Object-relational databases use a hybrid approach to databases.

In object databases, information is stored as objects, much like object-oriented programming.
In relational databases, information is stored in tables with relationships between tables defined by primary and foreign keys.

Importantly, PostgreSQL allows the use of advanced functions (such as Window Functions), and even development and use of custom functions written in different programming languages. Here is a link to better understand what is meant by an object-relational database, and how it differs from a relational database.
https://en.wikipedia.org/wiki/Object-relational_database

<strong>Ready to proceed with PostgreSQL? Follow along!</strong>

<strong>Step 1. Downloading PostgreSQL</strong>

First, you will need to install PostgreSQL on your local machine. The instructions below provide detailed description of the steps you need to take.

<strong>Installing PostgreSQL for Windows:</strong>

http://www.postgresqltutorial.com/install-postgresql/

<strong>Installing PostgreSQL for Mac OS:</strong>

https://www.postgresql.org/download/macosx/

Friendly reminder! Please write down the database superuser (postgres) password as you will need it to create the Sakila database once you have installed the PostgreSQL server.
Step 2. Downloading Sakila database
Once PostgreSQL server is installed, you will need to download the Movie database from this page: PostgreSQL Sample Database

Scroll down and click on the orange "Download DVD Rental Sample Database" button.

This will download a zipped file, and you will need to extract the dvdrental.tar file.

<strong>Step 3. Loading database</strong>

The next step is to load the DVD Rental database into your PostgreSQL server on your machine. We recommend using the PgAdmin tool. You will find the instructions to do so on the following link: Load PostgreSQL Sample Database.

The instructions are down ⅓ on this page under the header “Load the DVD Rental database using pgAdmin tool” .

The screenshot below shows the blue arrow pointing to the header.

Now follow the instructions all the way through the header titled "Verify the loaded sample database."

Once you have followed the instructions through the end of "Verify the loaded sample database.", you have now loaded the dvdrental sample database into your local PostgreSQL database server.

<strong>Step 4. Connecting back to the PostgreSQL server:</strong>

Relaunch PgAdmin III and click on the PostgreSQL server within the Object browser. The screenshot below shows the red arrow pointing to PostgreSQL server. Click it and enter your superuser (postgres) password.

<strong>Step 5. Connecting to the DVD rental database:</strong>

Next click on the plus sign next to Databases to access the DVD rental database. The screenshot below shows the red arrow pointing to Databases.

<strong>Step 6. Choose the DVD Rental database</strong>

Choose the `dvdrental` database under Databases. The red arrow in the screenshot is pointing towards the dvdrental database.

You should now be linked to the DVD rental database.

Awesome!!

<strong>Step 7. Running Queries on your dvdrental database</strong>

Ready to run some queries?? Click on the SQL icon with a magnifying glass (see the screenshot below with the red square on the icon).
