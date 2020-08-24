# COSC 304 - Introduction to Database Systems<br>Lab 7: Building a Database-enabled Web Site using PHP

**For this assignment, create a directory `Lab7` on `cosc304.ok.ubc.ca` under your home directory in the folder `public_html`.**

## Example 1

Here is the code to show "Hello World!" using PHP:

```
<html>
<head>
<title>Hello World in JSP</title>
</head>
<body>

<?php echo("Hello World!"); ?>

</body>
</html>
```

[Click for a demonstration of the Hello World code](http://cosc304.ok.ubc.ca/rlawrenc/Lab7/HelloWorld.php)

The URL of the PHP file is: `http://cosc304.ok.ubc.ca/rlawrenc/Lab7/HelloWorld.php`

We can modify this code either by being logged in to `cosc304.ok.ubc.ca` and editing it with `nano` or by editing the file on our local machine and transferring it to `cosc304.ok.ubc.ca`.

Try and change the code so that the output looks like this:

# Hello World Again!

<pre>
1
2
3
4
5
</pre>

[Click here for a demonstration of the Hello World Again code](http://cosc304.ok.ubc.ca/rlawrenc/Lab7/HelloWorldAgain.php)

### [Solution - HelloWorldAgain.php](code/HelloWorldAgain.php)

## Example 2

[Example code](code/QueryMySQL.php) to query the workson database and return some answers in a table.  Make sure that the url is `jdbc:mysql://cosc304.ok.ubc.ca/workson` and put in your user id and password. There is also [sample code for SQL Server](code/QuerySQLServer.php).

## Example 3

Modify the sample PHP code for querying WorksOn such that for each department you list its projects and then its employees.  The output should look like <a href="http://cosc304.ok.ubc.ca/rlawrenc/Lab7/WorksOnDeptEmpProj.php">this (click here)</a>.

### [Solution - WorksOnDeptEmpProj.php](code/WorksOnDeptEmpProj.php)


## Example 4

You can pass and receive parameters between PHP pages.  An example is to create an HTML form that collects user input and then passes this information to a PHP file to perform the query and return the answers.

### [Query Form Example](code/sampleForm.html)

### [PHP Code for Performing Query](code/EmpQuery.php)


## Example 5

Create your own query form for the WorksOn database. Your form should have boxes for the Employee name and Project name that accept partial matches (using `LIKE '%queryString%'`).  The PHP file should receive the parameters and create a query that lists all WorksOn records where the employee name and project name are as specified.  Show the count of the # of records at the bottom of the page.  An [example query form and system](http://cosc304.ok.ubc.ca/rlawrenc/Lab7/WorksOnQuery.html) is available.

### [Solution - HTML File](code/WorksOnQuery.html)

### [Solution - EmpProjQuery.php](code/EmpProjQuery.php)

## [Lab 7 Assignment](assign/)
