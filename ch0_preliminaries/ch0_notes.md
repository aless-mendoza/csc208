# Chapter 0 Notes
---
## Vocabulary
* **Discrete (adj)** -> Individually separate and distinct.
* **Mathematics** -> Problem solving regarding numbers, lines, functions...
* **Discrete Structures** -> Mathematical objects that we use to represent parts of the problems we are solving
    * The structures we will use are: **sets**, **functions**, **sequences**, **relations**, and **graphs**    

---

## Structures:

### Sets
* **Sets:** An unordered collection of elements
* **Set Comprehension (or Set Builder Notation):** $A$ = {x \$in$ $N$ : $x$ < 10} which reads as $A$ is the set of (=s) natural numbers ($N$) that satisfy the property that they are less than 10($x$ <10).
* We can build sets from ones we already have by using **Unions** or **Intersections**
* **Cardinality:** How many elements are in a set. Ex: $A$ = {1, 2, 3} The cardinality of $A$ is 3 because it has 3 elements

### Functions
* **Functions:** a rule that assigns each input exactly one output
* **Image:** output of an input
* **Domain:** The set of all inputs
* **Codomain:** The set of all allowable outputs
* **Range:** the set of all actual outputs aka the set of all images of elements form the domain
* $f$ : $X$ -> $Y$ where the funciton name is $f$, $X$ is the domain, and $Y$ is the codomain
* **Closed Formula:** each output is given by an explicit rule based solely on its input 
    * Ex. $f$($n$) = 3$n$ + 1 is a closed function since for every value of $n$ there is a defined output

### Sequences 
* **Sequences:** An ordered list of elements where order matters. 
* **Finite Sequence:** A sequence with a specific number of elements, e.g., {1, 2, 3}. 
* **Infinite Sequence:** A sequence that continues indefinitely, e.g., (4, 8, 12, $\dots$). 
* **Tuple:** A finite sequence with $n$ elements is called an $n$-tuple. 
* **Difference from Sets:** Unlike sets, sequences care about order. The sequence {1,2,3} is different from {2,3,1}, while the set {1,2,3} is the same as {2,3,1}. 
* **Function Representation:** A sequence can be thought of as a function ( $f$: $\mathbb{N}$ \to $X$), where the domain is a subset of natural numbers representing positions, and the codomain ($X$) is the set of possible elements. 
* **Closed Formula:** A formula that explicitly defines each term, e.g., [ $a_n$ = $\frac{n(n+1)}{2}$ ] defines the sequence of triangular numbers.
* **Recursive Definition:** Defines each term based on previous terms, e.g., Fibonacci sequence: [ $f_n$ = $f_{n-1}$ + $f_{n-2}$, $\quad$ $f_1$ = 1, $\quad$ $f_2$ = 1 ] 

### Relations 
* **Relations:** A way to describe relationships between elements of one or more sets. 
* **Binary Relation:** A relation between two elements, e.g., "less than" (<), "equal to" (=), or "divisibility" ($\mid$). 
* **Ternary Relation:** A relation involving three elements, e.g., the **Pythagorean triple** relation (a, b, c) if ( $a^2$ + $b^2$ = $c^2$ ). 
* **Set Representation:** A relation is a set of ordered pairs (or triples, etc.), e.g., the relation "less than" can be written as: [ $R$ = {(a, b) $\mid$ $a$ < $b$} ]
 * **Properties of Relations:** 
* **Reflexive:**  $aRa$ for all $a$ (e.g., "is equal to").
 * **Irreflexive:** $aRa$ never holds (e.g., "is less than"). 
* **Symmetric:** If $aRb$, then $bRa$ (e.g., "is a sibling of"). *
 **Antisymmetric:** If  $aRb$ and $bRa$, then $a$ = $b$ (e.g., "is less than or equal to"). 
* **Transitive:** If $aRb$ and $bRc$, then $aRc$ (e.g., "is an ancestor of"). 


### Graphs 
* **Graphs:** A mathematical structure consisting of **vertices** (nodes) and **edges** (connections). 
* **Graph Representation:** 
* **Vertices Set**: $V$ is the set of nodes. 
* **Edges Set**: $E$ is the set of connections, written as unordered pairs (a, b). 
* **Undirected Graph:** If (a, b)  is in $E$, then (b, a) is also in $E$. 
* **Directed Graph (Digraph):** Each edge has a direction, meaning (a, b) does not imply (b, a). 
* **Examples:** 
* **Friendship Graph:** Students are vertices, friendships are edges. 
* **Geographical Graph:** Countries as vertices, shared borders as edges.
 * **Flight Network:** Airports as vertices, direct flights as directed edges. 
* **Graph Theory Applications:** 
* Shortest path problems (e.g., GPS navigation). 
* Network connections (e.g., internet routing). 
* Social network analysis.

---

## Questions

* What is discrete math?
    * {0, 1, 2} is discrete because the elements are seperate whereas in y=x^2 the outputs aren't seperate
    * Typically ints (whole numbers)


* What are the four main topics that Professor Levin says will be presented in the book?
    * We will be covering **combinatorics**, **sequences**, **symbolic logic**, and **graph theory**

* What are discrete structures? Which specific examples are listed in the chapter? Briefly describe each of these.
    * **Discrete Structures** -> Mathematical objects that we use to represent parts of the problems we are solving
    * Examples:
        * **Sets:** An unordered collection of elements
        * **Functions:** a rule that assigns each input exactly one output
        * **Sequences:** An ordered list of elements where order matters.
        * **Relations:** A way to describe relationships between elements of one or more sets.
        * **Graphs:** A mathematical structure consisting of **vertices** (nodes) and **edges** (connections).
