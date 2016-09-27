#Simple Database
This is the code implementation of [3th chapter of pratical common lisp](http://www.gigamonkeys.com/book/practical-a-simple-database.html) book.
If you want to learn Common Lisp here is the
[link](http://www.gigamonkeys.com/book/) to the book.

#Running the scripts

To execute the script you will need to install Lisp in your machine, so for
those who use Debian just execute this command on your terminal:
>`sudo apt-get install sbcl`

After you have installed Lisp in your machine open the terminal and use `sbcl`
to start using a interactive shell for lisp.

To Load the scripts just use the macro `(load "simple_db.lisp")`.

The avaliable functions are:
* add-cds -> Add new cds to the lisp
* dump-db -> print the list of cds human readable
* save-db pathname -> Save the list into the file, where pathname is an argument
  of the function.
* load-db pathname -> Load the list saved in the file.



