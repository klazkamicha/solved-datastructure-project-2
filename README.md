Download Link: https://assignmentchef.com/product/solved-datastructure-project-2
<br>






Introduction:

In this project you will modify the author’s BinarySearchTree code     to implement some new methods.

Description:

Modify the author’s BinarySearchTree code to implement the methods    shown below.

Each method is 10 points.

<ol>

 <li>nodeCount</li>

</ol>

Recursively traverses the tree and returns the count of nodes.

<ol>

 <li>isFull Returns true if the tree is full.  A full tree has every node            as either a leaf or a parent with two children.</li>

 <li>compareStructure</li>

</ol>

Compares the structure of current tree to another tree and returns           true if they match.

For example, these two trees have the same structure:

5           10                   /          /  

3   8       5   15

/          /                 1   4       2   7

<ol>

 <li>equals</li>

</ol>

Compares the current tree to another tree and returns true           if they are identical.

<ol>

 <li>copy</li>

</ol>

Creates and returns a new tree that is a copy of the original tree.     f) mirror

Creates and returns a new tree that is a mirror image of the original tree.         For example, for the tree on the left, the tree on the right is returned:




100                 100

/                  /   

50   150    –&gt;     150  50

/                           

40                           40

                           /          45                         45

<ol>

 <li>isMirror Returns true if the tree is a mirror of the passed tree.</li>

 <li>rotateRight</li>

</ol>

Performs a single rotation on the node having the passed value.         If a RotateRight on 100 is performed:

100                  50

/                   /   

50   150    –&gt;      40   100

/                           

40                      45    150



45




<ol>

 <li>g) rotateLeft</li>

</ol>

As above but left rotation.

<ol>

 <li>printLevels – performs a level-by-level printing of the tree.</li>

 <li>main – demonstrate in your main method that all of your new methods work.</li>

</ol>

Submit to eLearning:

BinarySearchTree.java