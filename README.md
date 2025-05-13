# ece590-project-2--dfs-bfs-solved
**TO GET THIS SOLUTION VISIT:** [ECE590 Project 2- DFS/BFS Solved](https://www.ankitcodinghub.com/product/ece590-project-2-dfs-bfs-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94254&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE590 Project 2- DFS\/BFS Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1 Problem Statement

You will have three primary tasks in this project:

1. Properly implement a Stack class for use in DFS.

2. Properly implement a cyclic Queue class for use in BFS.

3. Implement the function bdfs that can run either DFS or BFS to solve the maze.

You should test your code in the main function of the project2.py file, since this file im- ports all of the others.

You must submit your project2.py, p2stack.py, and p2queue.py code online on Sakai. If you worked with a partner, only submit one version of your completed project and indicate clearly the names and NetIDs of both partners.

This project is worth 100 points. The points will be assigned as follows: • 20 points each for a correct Stack and Queue

• 30 points each for a correct DFS and BFS implementation

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1.1 Stack Class

You have been provided with a partially implemented Stack class in p2stack.py. It has 3 class attributes:

• stack: the array (a python list we are treating like an array) representing the stack

• top: the index of the top element of the stack (will point directly at the top element) • numElems: the number of elements currently in the stack

There are 2 fully implemented member functions:

<ul>
<li>init : the constructor which initializes an empty stack</li>
<li>repr : the printing function that displays the stack’s info in a readable format
You will be responsible for implementing five more member functions:
</li>
</ul>
<ul>
<li>isFull: this function should return true when the stack is full (and requires resizing)</li>
<li>isEmpty: this function should return true when the stack is empty</li>
<li>resize: this function should resize the stack by doubling the size of the array</li>
<li>push: this function should take in some value and push it onto the top of the stack Note: it is intended that you call the isFull and resize functions from within the
push function only, i.e., you should not call them elsewhere before the call to push.
</li>
<li>pop: this function should pop the top value off the stack and return it
Note: you are not allowed to use built-in functions like append or remove for these tasks. Instead, you are expected to implement these functions directly using the provided attributes of the Stack class.

It is highly suggested that you ensure your Stack code is working correctly before proceeding.
</li>
</ul>
1.2 Queue Class

You have been provided with a partially implemented Queue class in p2queue.py (note that you need to implement a cyclic queue as discussed in lecture). It has 4 class attributes:

<ul>
<li>queue: the array representing the queue</li>
<li>front: the index of the front element of the queue (will point directly at the front
element), this is the next element to be popped
</li>
<li>rear: the index that is ONE PAST the rear element of the queue, this is the location where the next pushed value will be written</li>
<li>numElems: the number of elements currently in the queue 2</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
There are 2 fully implemented member functions:

<ul>
<li>init : the constructor which initializes an empty queue</li>
<li>repr : the printing function that displays the queue’s info in a readable format
You will be responsible for implementing five more member functions:
</li>
</ul>
<ul>
<li>isFull: this function should return true when the queue is full (and requires resizing)</li>
<li>isEmpty: this function should return true when the queue is empty</li>
<li>resize: this function should resize the queue by doubling the size of the array, while also unwrapping the queue so that the front and rear values are reset</li>
<li>push: this function should take in some value and push it into the rear of the queue Note: it is intended that you call the isFull and resize functions from within the
push function only, i.e., you should not call them elsewhere before the call to push.
</li>
<li>pop: this function should pop the front value from the queue and return it
Note: you are not allowed to use built-in functions like append or remove for these tasks. Instead, you are expected to implement these functions directly using the provided attributes of the Queue class.

It is highly suggested that you ensure your Queue code is working correctly before proceeding.
</li>
</ul>
1.3 DFS/BFS Implementation

The bulk of your submission will concern the function bdfs in project2.py. This function should take in an input Maze object and a string that is either ‘DFS’ or ‘BFS’. Your imple- mentation of this function should be able to run either DFS or BFS depending on this input string. Recall that the only major difference between the two algorithms is that one uses a stack and the other uses a queue.

The Maze class provides you with both an adjacency list of Vertex objects, and an adjacency matrix. So, you may use whichever representation you prefer when creating this function.

The output of this bdfs should be a list of vertex ranks (NOT Vertex objects) representing the path starting at the start vertex (which should be the first rank in your returned path) and ending at the exit vertex (which should be the last rank in your returned path).

You should not call this function directly when creating your code, but should instead use the Maze class’s member function solve, i.e., to test the small open room maze with printing and plotting enabled:

<pre>m = Maze(0, True)
m.solve(‘DFS’)
m.solve(‘BFS’)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Note that the path will be overwritten with each call to solve, so you can re-solve a maze that has already been solved.

Note that the function call testMazes(True) will test all four provided mazes with both DFS and BFS, and print the resulting paths (you can set the verbosity input to False to suppress the printing).

2 Provided Code

Your goal in this project will be to implement both DFS and BFS to solve several given mazes. To aid you in this, you have been provided with several fully functioning classes, several partially implemented classes, and functions for creating and testing the mazes.

2.1 Vertex Class

The first of the fully functioning classes is the Vertex class in p2maze.py. This class has 5 class attributes:

• rank: the rank (label) of the given vertex

• neigh: the list of the neighboring vertices

• dist: the distance from the start vertex

• visited: a flag for marking a vertex as visited • prev: the previous vertex in the path

Along with these are three implemented member functions:

</div>
</div>
<div class="layoutArea">
<div class="column">
•

• •

</div>
<div class="column">
init : this is the constructor function for the Vertex class. It requires an input rank for the vertex, and sets all of the attributes to have reasonable starting values. You will create a new Vertex with a call: v = Vertex(rank).

repr : this function is called whenever a Vertex is printed, i.e. when the call print(v) is made. It simply prints the rank of the vertex.

isEqual: this takes in a second Vertex as an input, and compares the rank of the two vertices, returning True if they are equal rank (i.e., if they had the same label). This function can be called using: v.isEqual(u).

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
2.2 Maze Class

You have also been provided with a fully functioning Maze class in p2maze.py with 7 class attributes:

<ul>
<li>maze: a 2D array representing the maze (for internal use only)</li>
<li>adjList: the adjacency list of Vertex objects</li>
<li>adjMat: the adjacency matrix (stored as a 2D list of 0 or 1)</li>
<li>start: the starting Vertex object</li>
<li>exit: the exit Vertex object</li>
<li>path: what will ultimately contain the path from start to exit, stored as a list of ranks
(not a list of vertices)
</li>
<li>verb: a flag that controls the verbosity of the printing, set to False to suppress printing the maze when solving and testing
The Maze class has 6 member functions:
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
•

•

• • •

</div>
<div class="column">
init : this is the constructor for the Maze class. It has two optional inputs: the mazeNum which selects which maze to use (options: 0,1,2,3 – default: 0); and the verbosity (True/False – default: False). This initialization function correctly creates the adjacency list and matrix, and finds the start and exit vertices. The path attribute is initialized as an empty list. A new maze can be created with the call

m = Maze(mazeNum, verbosity).

repr : this function is called when a Maze object is printed. It will check to see if a path has been set, and if that path correctly solves the maze. If verbosity is True, this function will print out the maze with a highlighted path if one was present. If verbosity if False, only statements concerning the correctness of the path will be printed.

When the maze is printed, walls are marked with an ‘X’, the start with an ‘s’, the exit with an ‘e’, and the path with ‘o’. If you see a ‘G’, it means your path attempted to pass through a wall. If you see an ‘R’, your path had a repeated vertex.

printList: this function can be used to aid with debugging. It prints the adjacency list in a more readable format.

printMat: this function can be used to aid with debugging. It prints the adjacency matrix in a more readable format.

plot maze solution: this function will create a matplotlib figure based on the current maze and path info. It takes in as input a flag for plotting (default: True), which will actually call the plt.show() command when True. If this flag is set to False, the figure is created, and a later call to plt.show() will display it.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
• solve: this function takes in an alg (either the string ‘DFS’ or the string ‘BFS’), a flag for verbosity (default: True), and a flag for plotting (default: True). It then calls the function bdfs on the maze to obtain the path through the maze, which you will be responsible for implementing.

2.3 getMaze and testMazes

You have also been provided with two functions that create the maze and test your code. The getMaze function is found in p2maze.py, while the textMazes function is in p2tests.py:

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
<div class="layoutArea">
<div class="column">
•

</div>
<div class="column">
getMaze: this function takes in 0, 1, 2, 3, 4, or 5 and outputs the 2D array of 0s and 1s representing the maze. This is used internally by the Maze class. The mazes are:

<ol start="0">
<li>A small open room for debugging.</li>
<li>A small maze for debugging.</li>
<li>A large maze.</li>
<li>A large zig-zag map.</li>
<li>A specially designed test that will guarentee different behaviors for DFS and BFS. For this maze, DFS cannot find the shortest path, while BFS must find the shortest path.</li>
<li>A randomly generated maze.</li>
</ol>
testMazes: this function will allow you to test your code on the entire set of mazes. It takes in an optional argument verbosity, which controls whether each maze gets printed as it is solved (default = False).

Pair Programming

</div>
</div>
<div class="layoutArea">
<div class="column">
•

</div>
</div>
<div class="layoutArea">
<div class="column">
You are allowed to work in pairs for this project. If you elect to work with a partner:

<ul>
<li>You should submit only one version of your final code and report. Have one partner upload the code and report on their Sakai site. Make sure that both partner’s names are clearly indicated at the top of both the code and the report.</li>
<li>When work is being done on this project, both partners are required to be physically present at the machine in question, with one partner typing (‘driving’) and the other partner watching (‘navigating’).</li>
<li>You should split your time equally between driving and navigating to ensure that both partners spend time coding.</li>
<li>You are allowed to discuss this project with other students in the class, but the code you submit must be written by you and your partner alone.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
4 Style Points

Part of your grade for this project will be ‘style points’. The idea here is that the code you turn in must be well commented and readable. A reasonable user aught to be able to read through your provided code and be able to understand what it is you have done, and how your functions work. For these sorting algorithms, this means that a grader should be able to read over your code and tell that your algorithms are implemented correctly.

The guidelines for these ‘style points’:

<ul>
<li>Your program file should have a header stating the name of the program, the author(s), and the date.</li>
<li>All functions need a comment stating: the name of the function, what the function does, what the inputs are, and what the outputs are.</li>
<li>Every major block of code should have a comment explaining what the block of code is doing. This need not be every line, and it is left to your discretion to determine how frequently you place these comments. However, you should have enough comments to clearly explain the behavior of your code.</li>
<li>Please limit yourself to 80 characters in a line of code. In python, you can use the symbol \ to indicate a line break/continuation.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
