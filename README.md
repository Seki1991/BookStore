# BookStore
BookStore is a simple program written completely in Python. 
Main purpose of this program is to easily organise user's book library.

It allows commands:

  1."View all" - enables user to see all books in database;
  
  2."Search entry" - enables user to search in existing database;
  
  3."Add entry" - enables user to add new book to existing database;
  
  4."Update selected" - enables user to make changes in existing database;
  
  5."Delete selected" - enables user to delete entries in existing database;
  
  6."Close" - for closing program.
  
![BookStore image](https://user-images.githubusercontent.com/104382311/165520620-dd117cf1-e11e-4daa-936a-a61a3f5f1037.png)

## Installation guide

This program uses Python with modules sqlite3 and tkinter. Ensure you have them installed before continuing.

`$ git clone https://github.com/Seki1991/BookStore`

`$ cd BookStore`

`$ python frontend.py`

Note that if you want to run this program without using python, you can build BookStore.exe file with Pyinstaller by inserting code:

`$ pyinstaller --onefile frontend.pu`
