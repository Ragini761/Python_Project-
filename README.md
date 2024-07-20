# Python_Project-
Library Management System 
# About Library Management Systems:
Library Management Systems are used to manage information about contents in a library. They are used to manage information relating to books, their names, codes, author names, whether they have been issued or not and if so, who has issued them and what their card’s ID is; a library management system is used to store and manage all this information.
The objective of this is to create a GUI based Library Management System. To build this, you will need intermediate understanding of the SQLite API and its commands, intermediate understanding of Tkinterlibrary, Ttk module’s Treeview, and basic understanding of messagebox module.
# Python Library Management Project Prerequisites:
To build this project, we will need the following Python libraries:

1. Tkinter – To create the GUI
a. messagebox – To display boxes showing information or error or asking yes or no.
b. Ttk.Treeview – To display all the information in the GUI window.
c. simpledialog – To use pre-defined simple dialog boxes provided by  Tkinter.

2. Mysql – To connect to the  database and perform operations in it.
3.Command line(python used)
4.interface->python->PymySQLConnector
5.DATA STORE->MySQL->System req.P-IV&Above 1GB RAM Window-7&above python -3.6 & above Mysql 5.6& Above
# Table in backend(ER-DIAGRAMA)
1.BOOK
BOOK_ID INT(PRE KEY)
BNAME   VARCAR
AUTHOR  VARCHAR
COPPIES FLOAT
PRICE   INT
REM_COPIES INT

2.ISSUE
ISSUE_ID    INT(PRE KEY)
ISSUE_DATE  DATE
MEMBER_ID    INT(FOR KEY)
BOOK_ID      INT(FOR KEY)
COPIES         INT

3.MEMBER
MEM_ID       INT(PRE KEY)
MNAME        VARCHAR
MADD         VARCHAR
PHONE         CHAR(10)


4.RETURN
RETURN_ID    INT(PRE KEY)
RETURN_DATE  DATE
MEMBER_ID    INT(FOR KEY)
BOOK_ID      INT(FOR KEY)
COPIES         INT

# FUNCTIONALITIES:
Book details
    1.add new book
    2.edit book details
    3.delete a book
    4.search a book
Member details
    1.add new member 
    2.edit member details
    3.delete a member
    4.search a member
Transaction
    1.issue a book
    2.return a book
Reports
    1.Book details
    2.Member details
    3.issue details
    4.Best reading
    5.Book(CHART)
