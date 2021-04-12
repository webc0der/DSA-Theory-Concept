# DSA-Theory-Concept
THEORY CONCEPTS OF DSA

- PHYSICAL DS:
Array
LinkedList

- LOGICAL DS:
Tree
Hashing
stack
Queue
grap

- ALGOS:
magic framwork
greedy algo
divide conquer
dynamic programming

- Data Structure:
it is way to organise data in such a way that enable it to process it in efficient time

- ALGORITHM:
it is set set of rule to be followed to solve a problem

- Primitive data structures:
these are the data structures privided by the programing language, Ex- Interger, float, char , boolean

- NON-PRIMITIVE DATA STRUCTURES:
this can categorized in two types:
    -> Physical data structure: Array, Linked List
    -> Logical data structures: tree, stack, queue, graph
logical ds have the concept but the implementation is based on in any of the phyical ds
EX- stack can be implmented based on array or linked list and same goes for Queue also

- RECURSION:
    -> same operation is performed with different inputs
    -> in every operation we try to minimize the the problem so that we will be closer to reach the solution
    -> in recursive operation it is mandatory to have base condition, and once that condition get satified the recursive opration stops and gives us the solution
    -> recursion can be applied in tree and graph DS.
    -> can be applied in divide and conquer, greedy and dynamic programing, stack, sorting(quick sort, merge sort)
    -> format of recursive function:
    -> recursive case: the case where function will recur
    -> base case: the case where function will not recur
    -> recursion vs iteration:
    -> time: recur take more time becaouse it needs to access the stack memory to push and pop the recorsive method calls, hence it more time than iteration
    -> space efficiency: recur takes more space than iteration, as it store multiple method calls in stack memory

- ALGORITHM RUN TIME ANALYSIS
    -> it is a procedure to measure the performance of the given alorithm in run time
    -> Notations:
    -> Omega notation: this defines the tighter lower bound of  given alogo. this defines the best performance of an algo, that means the alog wont take less than the given time
    -> Bog-o(O) notation: this defines the tighter upper bound of an algo. this defines the worst case performance of an algo, that means the algo wont take more than the calculated given time.
    -> theta notation: this defines the average bound of an aglo. this defines the average performance of an algo by consider all possible inputs or large number of inputs.
    -> types of Big-o notation:
    -> O(1): order of one: constant time complexity: adding an element at front of LL 
    -> O(log n): logarithmic time complexity: finding an element in a sorted array
    -> O(n): linear time complexity: finding an element in unsroted array
    -> O(n logn): linear lodarithmic time complexity: merge sort
    -> O(n2): quadratic time comlexity: shortest path b/w two nodes
    -> O(n3): cubic time complexity: matrix multiply
    -> O(2n): Exponential time complexity

- ARRAY DATA STRUCTURES
    -> collection of similar data types
    -> contigous memory localtion with similar data types
    -> size of an array cant be modified
    -> 3d array: arr[depth][row][column]
    -> 2d and 3d array also get stores in memory in flat manner: 2d example: [0][0],[0][1],[0][2]  3d example:[0][0][0],[0][0][1],[0][0][2]
    -> 1d array
    -> declariont: creating a reference variable arr
    -> instantiating: assinging the size of array, then system allocates a memory location for it
    -> initalizing: adding values to it then system assing the location of memory to the refernce variable created
    -> initializing and traversing in 2d has time complexity of O(mn)
    -> when to use array: when it was nneded to access a cell randomly in a data string struction
    -> in array we cannot store data of diff types
    -> in array we have to initialize the size first
    -> practicle use of array: in dynamic programming(find the longest substring which is palindrome), in hash tables

- LINKED LIST
    -> linked list is linear data structure where each element is sepearate object or node
    -> each elemnt is consist of two items: data and the reference to the next node or object
    -> a train is an example of linked list
    -> a linked list is always have one head which point s to 1st node and the tail which point to the last node of the linked list
    -> no of node can be increased and decresed dynamically
    -> nodes cannot be accessed randomly
    -> we have tail in ll to add a new node at the end of a ll in O(1) complexity(we can directly goit the last node through tail and can add a new one), and if we dont ahve tail then we have travese from 1st to go last O(n).
    -> types of linled list:
    -> single linked list
    -> single linked list