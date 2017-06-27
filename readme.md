# Wat do?
Connect to store.sqlite3 it using sqlite3 <filename> and explore the following. (Note: you will want to make a backup copy before running queries that change the database.)

# Deliverables
A fork of this repo containing with answers.md  containing the answers to the following questions and the command(s) you used to find them.
 - for example 1. How many books are in the books table? 200 `SELECT COUNT(*) FROM books;`

# Explorer Mode
  - How many users are there?
  - What are the 5 most expensive items?
  - What's the cheapest book? (Does that change for "category is exactly 'book'" versus "category contains 'book'"?)
  - Who lives at "6439 Zetta Hills, Willmouth, WY"? Do they have another address?
  - Correct Virginie Mitchell's address to "New York, NY, 10108".
  - How much would it cost to buy one of each tool?
  - How many total items did we sell?
  - How much was spent on books?
  - Simulate buying an item by inserting a User for yourself and an Order for that User.

# Adventure Mode
  - What item was ordered most often? Grossed the most money?
  - What user spent the most?
  - What were the top 3 highest grossing categories?
