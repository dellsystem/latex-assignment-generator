LaTeX assignment generator
==========================

A simple shell script to make typing up your assignments easier.

Requirements
------------

* LaTeX with a bunch of extra packages installed (remove unnecessary ones in pdf_resources/header.tex)
* Python 2.7+
* Not Windows

Setup and usage
---------------

1. Clone this repository
2. Change `YOUR_NAME` and `STUDENT_ID` at the top of the pdf file. If you want to automatically copy the PDF file somewhere else, edit `PUBLIC_DIR` as well (see the instructions in the file).
3. Set up an alias to the `pdf` script. There are better ways of getting this to work but that's how I'm doing it right now.
4. Create the following directory structure: MATH242/ass1 where MATH242 is the course subject and number (no spaces) and 1 is the assignment number
5. Put the question files in the above directory, as 1.tex, 2.tex, etc. If you skip a number, the script will stop there.
6. Run `pdf` in the MATH242/ass1 directory.

To do
-----

* Better error reporting (`subprocess.Popen`)
* Multi-part questions: 1a.tex, 1b.tex etc
