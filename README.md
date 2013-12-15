Coded for mobme codejam

Question:
Write a number generator that keeps printing out 10 digit numbers, one in each line. Write a second program called filter that takes the output of this number generator and filters it based on its first digit: if the first digit starts with 0, write it to a file named 0.txt, if the first digit is 1, write it to a file named 1.txt, and so on. Write a third program that when run keeps a watch on these files and prints out the count of numbers in these files every second.

1) generator.py when run will start writing a 10digit number to random.txt.
2) filter.py when run will read random.txt and filters the 10 digit number according to the 1st digit and saves it to its respective text file(1.txt/2.txt….)
3) watch.py reads all the text file which filter created and prints the number of 10 digit numbers contained in the each of the text files from 1.txt to 9.txt

Dependencies:
python 2.7