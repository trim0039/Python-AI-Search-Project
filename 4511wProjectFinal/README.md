# 4511wProjectFinal

Project

For your project, you can choose any problem that requires some of the algorithms and methods we are studying in class or, more in general, that requires some intelligence.
Requirements

The project can be done alone or in a group of two.
Your project should include:
a programming component (write your own program or install some open source software and use it to solve a problem of interest. There is no requirement to use Lisp for the project),
a short literature search component (read 6-8 papers related to the topic of your project and report on them),
an original experimental component (run the software on a new problem of your own choice and analyze the results),
a written report.
A short proposal (around 500 words) is due March 25 as Writing 4. The proposal should include:
team members. If two students work together on the same project they should submit a single paper, indicating which parts each person wrote. A paper with more than one author is expected to be longer to reflect the larger effort.
a brief description of the problem you intend to address and why it is interesting,
the approach you will take to solve it (i.e . what algorithms are you going to use to solve the problem),
the software you'll need to write. modify, or use (i.e. how much of this software already exists? How much will you need to make from scratch?),
how you intend to run your experiments and analyze results (i.e. what and how will you measure the algorithms),
preliminary results (if any),
biliographic references to the papers cited.
an estimated timeline for the work schedule.
The literature review part for the project is due April 8 as Writing 5.
The final project report is due April 29. 
The report should be 10-12 pages long, and written using Latex. It should include:
Title, authors, date, a short abstract.
A short description of your problem and why it is interesting (1-2 pages).
A brief review of the background of the problem (2-3 pages). This should be your Writing 4.
A description of your approach to solve the problem. Include both representation and algorithms (1-2 pages).
A description of the design of the experiments and results (2-3 pages).
Analysis of the results (1-2 pages).
Conclusions, summarizing the problem and results and outlining future work you would do to make further progress (0.5-1 page).
Bibliography.
If the project is a group project, please indicate the contribution of each of the team members.
Each student is expected to spend approximatively 50 hours on the project, including the initial research, programming and evaluation, and writings. The scope of the project should reflect this level of effort.
You do not need to include the source code of the program(s) you wrote/used. The project will be evaluated on the report, so please make sure you say in the report if you used publicly available code or wrote your own and give an idea of the complexity of the code.
Grading

Project proposal: it will count for 3% of the class score. You will get the full score on it as long as you submit the information requested.
Project report: It will count for 12% of the class score. The points will be allocated as follows:
Writing:	quality of writing (10%)
organization of the report (10%)
use of Latex (5%)
Literature search:	coverage and analysis (15%)
Problem and solution:	complexity of problem and appropriateness of solution (15%)
quality and complexity of programming or development of novel methods (15%)
Experimental part:	design and extensiveness of experiments (15%)
analysis of results (15%)
Ideas for Project

Here are some ideas for your project. These are only suggestions and that you are free to propose any other project of your own choice.
Write an automated player for a non-trivial two-player game, like Othello or 3D Tic-Tac-Toe.
Write a a simple spam filter based on naive Bayes probability, following the steps outlined in A plan for Spam by Paul Graham. The article describes the problem and provides an outline of the method to be used. The article provides some Lisp code, and Paul Graham provides some more useful Lisp code. You do not need to do this in Lisp, any programming language will work, but it is particularly simple to write it in Lisp. If interested in using lisp for this, look here for more details.
Use A* or some other algorithm to find shortest paths in a map of Minneapolis, shown here. The map data are in the file map.lisp. 
The format of the file is as follows: each line contains information about a segment of a road. Each line includes 5 numbers in parentheses. The first number is 1 to indicate a one way road or 2 to indicate a two-way road. The next two integer numbers are the x and y coordinates of the start of the segment, the next two numbers are the x and y coordinates of the end of the segment, For instance, (1 1121 7568 1042 7545) indicates a one way road starting at point [1121, 7568] and ending at [1042, 7545]. There are 1357 lines in the file, each corresponding to a road segment. 
You do not need to use Lisp, the lisp format is used for the data because of convenience.
Solve the Traveling Salesperson Problem using real data. Large data sets are available at https://people.sc.fsu.edu/~jburkardt/datasets/tsp/tsp.html and at http://www.math.uwaterloo.ca/tsp/data/index.html and other places.
read the paper How MapQuest Works . Look at www.siam.org/meetings/alenex04/abstacts/rgutman1.pdf for an interesting routing algorithm.
RoboCup runs a simulation league where a team of simulated robots plays soccer against another team. Visit the official site at http://www.robocup.org/ for information about the different leagues. 
The RoboRescue simulation league addresses problems related to automating disaster management. There are two main subunits, the Agent Simulation and the Virtual Robots. The agent simulation focuses on large scale (city level) planning for disaster management, while the virtual robots provides a realistic simulation environment for robots. Look at https://rescuesim.robocup.org/ for information and for the simulator.
Help for Literature Search

Go to the ACM Digital Library, which is accessible to students and faculty. If the link does not work, you can get to it from the UofM library page ACM guide to computing literature
The AI Topics library from AAAI offers a collection of pages with information about AI and various subjects within AI. The library is organized by topics and is a good place to get a start on the subfields of AI.
use Google with a few key terms. In general you will find lots of references.
Avoiding Plagiarism

There is a very good web site http://plagiarismtest.org/student.html that will help you understanding if you are plagiarizing others work in your report. Take a look at it. The page for students has some very clear definitions.
Typesetting your paper

Information on LaTeX.
Copyright: © 2016-2020 by the Regents of the University of Minnesota 
Department of Computer Science and Engineering. All rights reserved. 
Comments to: Maria Gini
Changes and corrections are in red. Last updated 03/09/2020 11:20:19Last updated 01/19/2020 01:37:51
