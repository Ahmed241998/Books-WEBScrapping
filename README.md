# **Books WEB Scrapping**
## **2nd April 2023**
## **Overview**
Design and create a database for scraping All books for each category using DB Browser for MYSQL from this web site (http://books.toscrape.com/)
## **File Used**
WEBScrapping.ipynb
# **How the program works:**
* Scrap each book name and its Category, Price, Rating.
* Design and create a database for scraped book.
* Some Answers we will answer in our code
    * SQL query to get books that has rate >=3 and has 'Mr' in its name.
    * SQL query to get books that has rate >=3 or price > 20.
    * SQL query to get books that has rate not 3.
    * SQL query to get books that has price between 10 and 40 and has rate 3 or 4 or 1.
    * SQL query to get the top 5 most expensive books.
    * SQL query to get the 3rd 10 books in the books table order first by rate desc and then by price asc.
    * SQL query to add a new category in categories table and add 5 books to this category in books table with title, rate and price.
    * SQL query to update book's rate to 3 that thier price < 20£.
    * SQL query to delete all books that have price > 50£ and has rate <= 2.
    * SQL query to count the number of books that have 'Secret' in thier names and price between 10£ and 25£.
    * SQL query to get the minimum & maximum price for all the books that have rate 5.
    * SQL query to calculate the avg price for all the books that have rate 5.
    * SQL query to sum all book's price that have rate 2 and price between 10 and 40.
    * SQL query to join both books & categories table into one new table containing book_name & category_name & book_rate and book_price.
    * SQL query to calculate how many books each rate has and have price between 20£ and 30£.
    * SQL query to calculate how many books each category has having count > 10.
    * SQL query to get all books with category_name='Music' using subquery.
