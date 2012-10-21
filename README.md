LaTeX assignment generator
==========================

A simple shell script to make typing up your assignments easier.

Setup and usage
---------------

1. Clone this repository
2. Change `YOUR_NAME` and `STUDENT_ID` at the top of the pdf file
3. Symlink the pdf file into /usr/bin/pdf or somewhere else that's on your path
4. Create the following directory structure: MATH242/ass1 where MATH242 is the course subject and number (no spaces) and 1 is the assignment number
5. Put the question files in the above directory, as 1.tex, 2.tex, etc. If you skip a number, the script will stop there.
6. Run `pdf` in the MATH242/ass1 directory.

To do
-----

* Better error reporting
* Multi-part questions: 1a.tex, 1b.tex etc
