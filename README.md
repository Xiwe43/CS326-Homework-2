# CS326-Homework-2
CS326 Homework 2


Submission:
Submit
your code in Canvas as one “hw2.scm” file containing all your
functions.
The
file must be able to load and be tested in the interpreter.
Consequently,
the file must be in a simple text format; do not submit Word, PDF,


Also
make sure that any auxiliary information (such as your name or
question numbers) is commented out.
xemptyz
xemptyz
(55
pts) Consider an implementation of sets with Scheme lists. A set is
an unordered collection of elements, without duplicates.
xemptyz
(11
pts) Write a recursive function (is-set?
L),
which determines whether the list L
is a set. The following examples illustrate the use of this
function:
xemptyz
&gt;
(is-set? '(1 2 5))
xemptyz
#t
xemptyz
(is-set?
'(1 5 2 5))
xemptyz
#f
xemptyz
(11
pts) Write a recursive function (make-set
L),
which returns a set built from list L by removing duplicates, if
any. Remember that the order of set elements does not matter. The
following example illustrates the use of this function:
xemptyz
(make-set
'(4 3 5 3 4 1))
xemptyz
(5341)
xemptyz
(11
pts) Write a recursive function (subset?
A S),
which determines whether the set A
is
a subset of the set
S.
xemptyz
(11
pts) Write a recursive function (union
A B),
which returns the union of sets A
and
xemptyz
B.
xemptyz
(11
pts) Write a recursive function (intersection
A B),
which returns the intersection of sets A
and B.
(33
pts) Consider an implementation of binary trees with Scheme lists,
as in the following example:
xemptyz
Before
proceeding, it may be useful to define three auxiliary functions (val
T),
(left
T) and
(right T),
which return the value in the root of tree
T,
its left subtree
and
its right subtree, respectively.
xemptyz
(11
pts) Write a recursive function (tree-member?
V T),
which determines whether V
appears
as an element in the tree
T.
The following example illustrates the use of this
function:
xemptyz
(tree-member?
17 T)
xemptyz
#t
xemptyz
(11
pts) Write a recursive function (preorder
T),
which returns the list of all elements in the tree T corresponding
to a preorder traversal of the tree. The following example
illustrates the use of this function:
xemptyz
(preorder
T)
xemptyz
(135189221725)
xemptyz
(11
pts) Write a recursive function (inorder
T),
which returns the list of all elements in the tree T corresponding
to an inorder traversal of the tree. The following example
illustrates the use of this function:
xemptyz
(inorder
T)
xemptyz
(158913172225)
xemptyz
xemptyz
(12
pts) Write a recursive function (deep-delete
V L),
which takes as arguments a value V
and a list L,
and returns a list identical to L
except that all occurrences of V
in L
or in any sublist of L
have been deleted. The following example illustrates the use of this
function:
xemptyz
(deep-delete
3 '(1 2 3 (4 3) 5 (6 (3 7)) 8)) (1 2 (4) 5 (6 (7)) 8)
xemptyz
(Extra
Credit - 10 pts) A binary
search tree
is a binary tree for which the value in each node is greater than or
equal to all values in its left subtree, and less than all values in
its right
subtree.
The binary tree given as example in problem 2 also qualifies as a
binary search tree. Using the same list representation, write a
recursive function (insert-bst
V T),
which returns the binary search tree that results by inserting value
V
into binary search tree T.
For example, by inserting the value 20 into the binary search tree T
shown above, the result should be:
xemptyz
xemptyz

Coding Help Email: 📧 xujuncoding@gmail.com

