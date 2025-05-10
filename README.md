# Project-4-CMPE-250-solution

Download Here: [Project 4 CMPE 250 solution](https://jarviscodinghub.com/assignment/project-4-cmpe-250-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

People! Today we are going to liberate the people of Panem! And of course we will do it by helping ’The Girl on Fire’, our beautiful leader, Katniss Everdeen.
1 Scenario
The people of District 13 have just learn that the villain Rose is planning an attack to cut the communication between certain districts to incapacitate Katniss Everdeen and her team. They also posses the name of these districts, however they do not know that which lines the villain will attack. But Katniss senses that, since Rose would desire to ﬁnish the job quickly, he will cut the minimum number of lines and he wants to cut the ones that would take less time to cut.
As a valuable team member of Katniss Everdeen, your job is to detect the lines that Rose would attack and calculate the minimum time needed to cut these lines to report how much time left and deploy your army to the correct locations.
2 Input & Output
As usual you are going to use ﬁles whose names are speciﬁed through terminal for input and output. The ﬁles will be in the following format:
The First line: Two integers N and D, number of districts and the number of the districts Rose will try to cut the communication between. The following N-1 lines: 3 integers, the speciﬁcations of communication lines, two integers to specify the id of the cities and one integer to specify time needed to cut the line, respectively. The following D lines: Integers that are the IDs of the districts that Rose will try to cut the communication between.
As output you are going to print just one integer, that is the minimum amount of time needed to cut the communication. You are NOT going to print the lines since the ordering of the lines and the lines themselves may diﬀer between implementations (i.e. There may have been
1
multiple answers for this case).
Here is a sample input and output:
Input Output 12 3 17 0 1 3 0 2 10 2 3 8 2 5 9 2 4 12 4 7 17 4 6 15 6 9 6 9 8 5 8 11 13 10 11 19 2 6 11
Table 1: Sample Input and Output
2
Figure 1: Representation of the sample test case.
Explanation of the sample test case
Note that according to the input ﬁle, it is known that Rose wants to cut the communication between the districts 2, 6 and 11. According to Katniss’ anticipation he will attack to the line between 2 and 4 and the line between 8 and 11 since cutting these lines will be the quickest and suﬃcient way of blocking the communication. Since time needed to cut these lines will be 12 + 5 = 17, you are expected to print 17 in this case.
Notes • The input graph will always be a tree and contain N-1 edges. • Did you notice that when the red edges above are removed, the graph has 3 components left – and 3 is a part of the input? • Think about using a cool data structure you learned in this semester.
3 Submission Details
You are supposed to use the Git system provided to you for all projects. No other type of submission will be accepted. Also pay attention to the following points: • Make sure that an executable is created after executing cmake CMakeLists.txt and make commands. Otherwise, you will get no credit. Your code will be tested with the command:
./project4 inputFile outputFile
• All source codes are checked automatically for similarity with other submissions and exercises from previous years. Make sure you write and submit your own code. • In our case, you are expected to use C++ as powerful, steady and ﬂexible as possible. Use mechanisms that aﬀects these issues positively. • Make sure you document your code with necessary inline comments, and use meaningful variable names. Do not over-comment, or make your variable names unnecessarily long
