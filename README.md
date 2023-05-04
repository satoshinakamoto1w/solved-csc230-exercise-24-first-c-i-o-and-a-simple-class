Download Link: https://assignmentchef.com/product/solved-csc230-exercise-24-first-c-i-o-and-a-simple-class
<br>
First C++ : I/O and a simple class

You’ll find a source file, total.cpp and an input file, numbers.txt on the course homepage.

The main function in this program is empty. Add code to main to open the numbers.txt input file. Read in all the numbers, add them up and print out a total as illustrated below. Use a C++ ifstream to read the input, and use cout to print out the total, the average, the max and the min at the end.

The totals, count of values read, max, and min so far are data members of a class Stats. Your program will initialize these values in the constructor for this class, will call a member function fupdate(number) for each number read in, and member functions ftotal(), fcount(), faverage() (returns a float), fmin(), and fmax() to access the values of the private data members. The programs outputs a message when all numbers are read.

When you’re done, you should be able to run your program as follows. Copy the file you want to test with to numbers.txt, then

$ ./totalTotal: 511, count: 9, average: 56.7778, min: 8, max: 106

Or, if numbers.txt is empty,$ ./totalNo numbers in input file

Submit a copy of your completed total.cpp file using the exercise_24 assignment on Moodle.