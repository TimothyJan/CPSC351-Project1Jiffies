# CPSC351-Project1Jiffies
CPSC 351 Operating Systems Concepts 

Project 1 Jiffies
View the ReadMe.txt files to view the output!

Objectives:
-Modify the hello.c project, and confirm that it correctly makes (using make), and displays the GOLDEN_PRIME_RATIO on module load, and the gcd of 3300 and 24 on module removal.

-Create a kernel module that creates a proc file named proc/jiffies, and that reports the current value of jiffies when the proc/jiffies file is read, such as with the command: 
cat proc/jiffies

-Be sure /proc/jiffies is removed when the module is removed

-Save the output of /proc/jiffies, and submit it with your project

-Create a kernel module that creates a proc fie named /proc/seconds, that reports the number of elapsed seconds since the kernel module was loaded, such as with the command 
cat proc/seconds. 

-Your calculation involves jiffies and HZ, and includes the header files needed to compile and run your code

-Be sure /proc/seconds is removed when the module is removed

-Save the output of reading from /proc/seconds, and submit it with your project


