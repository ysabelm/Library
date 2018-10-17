# Library

In this library, a user can borrow books, DVDs and CDs.
A Book has properties like: a title and pages.
A CD: a title and a length. 
A DVD: a kind, a title, a 3D mention and length. 
There are 4 kinds of movies: horror, fun, action, musical.  

The Library must have only these methods :  
ArrayList putBooks(ArrayList books);     
ArrayList putDvds(ArrayList dvds);     
ArrayList putCDs(ArrayList cds);     
boolean isOpen(int hour);

The Library can store a lot of books and cds but only 3 DVDs. That means if there are already 3 DVDs and the user wants to give more, the library doesn't accept these dvds. 

Also, if the library has 1 DVD like DVD dvd = new DVD("dvd", 120, Movie.HORROR, false) and if the user gives the same DVD, the library won't accept it.

It's open between 1pm and 7pm.

Implement library and create unit test.
