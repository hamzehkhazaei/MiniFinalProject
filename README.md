## EECS3221-Z Final Project
**Out:** April 17, 2020 at 8:00am  
**Due:** April 19, 2020 at 11:59pm

### Description
Write a program that implements the following disk-scheduling algorithms: 
1. FCFS   
2. SCAN 
3. C-SCAN

These algorithms have been explained in the OSC book, sections `11.2.1`, `11.2.2` and, `11.2.3`, respectively.

Your program will service a disk with 100 cylinders numbered 0 to 99. 
The program will generate a random series of 25 unique cylinder requests and save them in a file called `input.txt`.
Then your program read the `input.txt` file and service them according to each of the algorithms listed above. 
The program will be passed the initial position of the disk head and 
report the seek sequence and the total amount of head movement required by each algorithm in a file called 
`output.txt`. 

The two files provided here serve as sample input and the correct output. Your program should populate the 
`input.txt` file with a new random series of 25 unique cylinder requests every time it is being executed.  
Also, note that the format of your `input.txt` and `output.txt` files should be the same as the sample 
files provided here. 

#### Hints
1. Assume that the *initial head position* is 33. 
2. In SCAN algorithm, assume that the disk arm is moving toward 0 from the initial head position.
3. In C_SCAN algorithm, assume that the disk arm is moving toward 99 from the initial head position.

### Submission and Evaluation 
You need to submit your `C source code`, `input.txt`, `output.txt` and a `Makefile` that compiles your code in one 
zip file. Following table shows the grading schema.

| Item        | Mark           |
| ------------- |:-------------:|
| FCFS Algorithm      | 5 |
| SCAN Algorithm      | 10 |
| C_SCAN Algorithm    | 10 |
| **Sum**             | **25** | 