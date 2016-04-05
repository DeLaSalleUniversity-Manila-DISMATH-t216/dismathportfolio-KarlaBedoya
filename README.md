# dismathportfolio-KarlaBedoya
dismathportfolio-KarlaBedoya created by Classroom for GitHub

Karla Bedoya
DISMATH EL

# Week 1:
* I was intoduced to Discrete Mathematics and what we will be learning for the whole term.
* I learned about different terms that we'll be using such as:
  * Mathematical proof
  * Proposition
  * Logical deduction
  * Axiom
  * Propositional variables
* I was also taught how to use a truth table to prove statements.
* I learned about logical connectives and how they are used:
  * Negation
  * Conjunction
  * Disjunction
  * Exclusive or
  * Conditional
  * Biconditional
* We focused more on conditional statements since it seems to be the most confusing.
* I was introduced to logical equivalences which can also be used to prove statements.

# Week 2:
* I learned about Predicate Logic which deals with more detailed statements.
* I also learned about Quantifiers and its two types:
  * Existential Quantifier
  * Universal Quantifier
    * An example thath proves that a statement is actually not a universal quantifier is a "counter example."
* I was introduced to different terms used in rules of inference:
  * Argument
  * Valid
  * Fallacy
* Note that the validity of a statement is different from its truthfulness.
* After that, we were taught the actual rules of inference:
  * Modus Pollens
  * Modus Tollens
  * Hypothetical Syllogism
  * Disjunctive Syllogism
  * Addition
  * Simplification
  * Conjunction
  * Resolution

# Week 3:
* I learned about the different methods of proof:
  * Direct proof is where we assume p is true and show that q is also true.
  * Proof by contraposition where we assume ¬q is true and then show that ¬p is also true.
  * Vacuous and Trivial Proof
  * Proof by contradiction is where we assume ¬p is true and show that it ends up in contradiction, leading us to know that p is actually true.

#Week 4:
* We discussed about another method of proving which is Proof by Equivalence. 
  * We must show that p q and q p are both true. 
* Another proof that I learned is Mathematical Induction. 
  * There are two steps to use this: the basis step and the inductive step. 
  * Direct proof is used for the inductive step. 
* We then discussed about different definitions:
  * Recrusive/Inductive Definition
  
#Week 5:
* We reviewed recursive algorithms by discussing examples and doing some exercises.
* We started on a new topic called Program Correctness.
  * Program Verification
    * Show that the correct answer is obtained if the programs terminates, then show that the program always terminates.
  * Hoare Triple
    * p(S)q
  * We had a few examples to further understand the topic
* Another topic discussed is Power Series

#Week 6:
* We started on a new topic which is Functions
  * A function f is an assignent of exactly one element of B to each element A
  * One-to-one function or injection is where you can't assign the same value to two different domain elements.
  * Onto function or subjection is where functions have equal range and domain.
  * One-to-one corresponence or bijective is both one-to-one and onto.
 
#Week 7:
* We did not have classes this week.

#Week 8:
* We started discussing about algorithms.
  * Algorithm is a finite set of precise instructions for performing a computation or for solving a problem.
  * One example of algorithm is finding the maximum value in a finite sequence. A step by step process is:
    * Set temporary maximum equal to first integer of the sequence.
    * Compare to the next integer in the sequence. If it is larger that the temporary max, set it to temp max.
    * Repeat until there are no integers left in the sequence.
* I learned about the use of pseudocode which is a description of algorithm written in the structure of a programming language but is for human reading.
* I also learned about searching algorithms.
  * It is the problem of locating an element in an ordered list.
  * We discussed the two types of searching algorithms which are:
    * Linear search
    * Binary search
 
#Week 9:
* We were introduced to different types of sorting algorithms.
  * The first is bubble sort algorithm where it compares adjacent elements and then interchange them if they are in the wrong order.
  * Another is Insertion sort algorithm where it inserts elements in proper order.
* We were also taught of greedy algorithms which selects the best choice of each step instead of considering all sequences of steps.

#Week 10:
* We started discussingabout growth of functions.
  * This is often describe using Big-O notation.
  * Big-O notation can be used to estimate the sum of the first n positive integers, or for factorials.
  * We also learned about big-omega and big-theta notation.
  * Big-o is for upper bound, bog-omega is lower bound, and big theta is both upper and lower bound.
* This week we also learned about algorithm time complexity
  * Constant complexity
  * Logarithmic complexity
  * Linear complexity
  * n log n complexity
  * polynomial complexity
  * exponential complexity
  * factorial complexity
* I learned about division and modulo
  * this can be described with the equation a = dq + r

#Week 11:
We didn't have classes this week.

#Week 12:
* We discussed about our project for this course.
* We started with a new topic with Graph Theory.
* Graph is a discrete structure consisting of vertices and edges that connect them.
  *  ◯ - vertex
  *  ___ - edge
  * Some applications of graph theory could be LAN, socian networks, etc.
* Terminologies:
  * Degree - the number of edges connected to a vertex
  * Subgraph - a graph that is a part of an original graph
  * Paths - a sequence of edges that begins at a vertex of a graph and travels from vertex to vertex along edges of the graph
* In order to easily know how many edges there is in a graph, we were introduced to the Handshaking Theorem.
  * Twice the edges is equal to the summation of vertices times its degree.
* Next, we  discussed about Euler paths and circuits.
  * A graph is an euler path if there is a path passing through each edge exactly once.
  * However, an euler circuit is somehow like an euler path, except the path must lead back to the starting point, closing the graph.
* Having to trace each graph to know if it is an euler path or circuit can be confusing and time confusing, so we were taught an easier way to do so:
  * If all the nodes have even degrees, then it is automatically an euler circuit.
  * If there is exactly two nodes with odd degrees, then it is automatically an euler path.
* There is a formula for finding how many regions there are in a graph, called Euler's formula.
  * r = e - v + 2
* This week, we also learned about Hamilton paths and circuits, which are like euler paths and circuits, except instead of edges, it has to pass through every vertex.
* Unlike in euler's paths and circuits, there is no fast way to know if a graph is a hamilton path or circuit; we have to trace it manually.
* However, we can know that a graph is not a hamilton circuit if there is a pandant. which is a node with only one degree
* Another topic we discussed is the matrices of graphs. We can use adjacency matrix to represent connections in graphs.
* Planar graphs are graphs that can be drawn without its edges having to cross.
  * We can prove that a graph is not planar by Kuratowski's theorem
  * This states that if a graph has a subgraph that is K(3,3) or K(5), then it is automatically not planar.

#Week 13:
* We started the week by discussing Coloring Graphs
 * It can be easier understood if we treat the nodes as islands and the edges as borders.
 * In coloring, no adjacent islands should have the same color.
 * If the graph is planar, the maximum number of colors that can be use is 4.
* Another topic we discussed is trees.
* I learned that trees are connected undirected graphs with no simple circuits.
* Terms:
  * Internal vertices - vertices with children
  * Leaves - vertices with no children
  


