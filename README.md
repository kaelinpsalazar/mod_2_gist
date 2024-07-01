# B2 Intermission Work

Answer these Check for Understanding questions as you work through the assignments.

## HTML

1. What is HTML?
  - It is the base language to create the structure and layout of most web pages. 

2. What is an HTML element?
  - An element is the contents of this base structure. It contains a start tag, end tag, and the conents within. 

3. What is an HTML attribute?
  - An HTML attribute  is something that provides additional information to an element, and they are also able to be used to link this elements to otherr pages, such as the CSS. 

4. What is the difference between a class and an id? When would you use one vs. the other?
  - A class is used to applying styling to muliple elenemts within the webpage. An ID is generally used to add a unique attribute to a single HTML element. 

5. What HTML would you write to create a form for a new dog with a "name" and an "age"?
  - <form>
  <label for="dog-name">Name:</label>
  <input type="text" id="dog-name" name="dog-name"><br><br>
  <label for="dog-age">Age:</label>
  <input type="number" id="dog-age" name="dog-age"><br><br>
  <input type="submit" value="Submit">
</form>

6. What are semantic tags? When would you use them over a `div`?
  - Semantic tags are elements that clearly describe what the element is used for. Header, nav, footer, title, etc. 

7. Explain what each of the following HTML tags do and when you would use them:
  * `<h1>`, `<h2>`, etc.
    - Heading are pretty self explanitory, they are headers that identify what a section is about. 
  * `<p>`
    - Used for a block of text. 
  * `<body>`
    - This contains the content of the web page. imsges, text, links

  * `<a>` and the `href` attribute
    - These are hyperlinks that will take you to another URL. 

  * `<img>` and the `src` attribute
    - How you imbed an image into your page. 

  * `<div>`
    - Used as a element container within your HTML document

  * `<section>`
    - Another eleent container within your HTML document. 

  * `<ul>`, `<ol>`, and `<li>`
    - What you use to create lists in your HTML page. 

  * `<form>`
    - How you create a user input box. 

  * `<input>`
    - How you create inut contrls like text fields, buttons, etc. 
  
 ## CSS
 
1. What is CSS?
  -CSS, or Cascading Style Sheet, defines how the HTML document is diplayed to the user. 

2. What is a CSS selector? How do you use the ID selector? The class selector?
  - Is how you are able to coorlate what styling you are inputing and which element within the HTML page you are styling. 

3. What are the three ways to include CSS in your HTML documents? What are the pros and cons of each?
  - Inline CSS is easy and simple, but it not meant for big projects. 
   Internal CSSUseful for single page styling, but are not reusable for multiple documents. 
    External CSS Is the best for clean, readable, and reusable code.No cons realy, outside of requireing a linked CSS file. 

4. What is the Box Model? Describe each component of the Box Model.
  - It is a way of thinking about CSS pages. The elements withing the HTML page are sperated into boxes and the CSS page is able to manipulate those boxes so that they interact with each other and are well formated. 

## SQL

### Jumpstart Lab Tutorial

1. What is a database?
  - Databases are the core of web applications. They are how we store, call upon, calculate, and sort our data. 

2. What is SQL?
  - Structured Querey Language, or SQL, is how wer interact with databases. It entails the creation, modification, and deletion of tables or the data within. Even though it is approachable, it is still a programming language. 

3. What is SQLite3?
  - It is a simple database system that doesnt require a server to operate. It stores its data is a plain-text file. 

4. What is a Table?
  - It is a organized structure of information. 

5. What is a primary key?
  - It is a piece of information upon which data organization is based within one particular table. 

6. What is a foreign key?
  - it=s a piece of information upon which data organization is based between multipla tables, or how the data within the two tables are linked. 

7. Explain what each of the following SQL commands do:
  * insert
    - It is a command to add data into tables.

  * select
    - It is a command to find rows in table.

  * where
    - It is a command to look through your dataset for information and allow you to return data that refers to only a small amount of information that you are looking for. 

  * order by
    - It is a command with which you can manipulate the order in which the data within the table is displayed, depending on the criteria you input. 

  * inner join
    - It is a command that combines multiple tables that have a related rows between them. It will return only those rows. 
  
### PG Exercises

1. How can you limit which columns you select from a table?
  - You can limit columns by using the SELECT statement and specifying the column name.

2. How can you limit which rows you select from a table?
 - By using the WHERE statement and adding the conditions required.

3. How can you give a selected column a different name in your output?
  - You can change the name by using AS and then reassigning the collumn with the desired name. 

4. How can you sort your output from a SQL statement?
  - You can sort your output by using ORDERBY

5. What is joining? When do you need to join?
  - It is when you combine two or more rows from multiple tables, that have a commonly shared column. 

6. What is an aggregate function?
  - It is a calculation on a set of values and returns a signle value. So SUM, COUNT, MAX, etc 

7. List three aggregate functions and what they do.
  - SUM calculated the total sum of a column of numerals. AVG calculates the average. Max gives you the highest value in the column. 

8. What does the `group` statement do?
  - It combines rows that have the same values in the specified column. 

9. How does the `group` statement relate to aggregates?
  - I think it just simplifies the data so there is no duplicate output of data when using agregate functions? 

## Rails Tutorial: Task Manager

**Copy and Paste the link to your Task Manager repo here:**
https://github.com/kaelinpsalazar/task_manager
**Copy and Paste the link to your Static Challenge here:**

1. Define CRUD.
  - Create, REead, Update, Delete. These are the basica operations for using data. 

2. Define MVC.
  - Model View Controller. It is the basic way to look at an application and how it is designed. 

3. What three files would you need to create/modify for a Rails application to respond to a `GET` request to `/tasks`, assuming you have a `Task` model.
  -Route Files, Controller files, View Files. 

4. What are params? Where do they come from?
  - infermation sent to a server. The URL queries, HTTP request...ummmm 

5. Check out your routes. Why do we need two routes each for creating a new Task and editing an existing Task?
  - I think it is to make the setup of the application easier to manage? Not sure 