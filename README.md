
# BINARY-SEARCH-TREE-DSA
Binary-search-trees-in-JavaScript


| No.| Questions                                                                                                                                                                   |
| ---| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    | **Binary search tree**                                                                                                                                                     |                                                                                                                                                  
| 1  | [Binary-search-tree-and-its-applications](#)                                                                                                                                |
| 2  | [Height-balanced-BST](#)                                                                                                                                                    |
| 3  | [BST Insertion](#)                                                                                                                                                          |
| 4  | [Inorder successor and predecessor](#)                                                                                                                                      |
| 5  | [BTS Delection](#)                                                                                                                                                          |



| 1  | [Binary-search-tree-and-its-applications](#)   
# 1.1 Binaary search Tree 
<p> Left sub -tree :LT, Right sub- Tree: RT, Where P: Parent  </p>
<p> Let we assume that 'LEFT' :sub-tree  ≤ P' is called left side smaller </p>  
<p> Let we assume that 'RIGHT' :sub-tree ≥  P' is called right side is bigger </p>  

![](./BSTApplications/image1.png)

# 1.2 Binary search Tree
<ul>
<li><p> same like wise LEFT PARENT value </p>
<li><p> KEY REPRESENTS values of the tree and CURRENT tells the value of PARENT </p>
<li><p> When ever KEY values LESS then the CURRENT PARENT value then its represents the LEFT side of the tree </p>
</li><P> Select the LEFT side elements of the KEY values which are LESS than PARENT TREE</P> 

<li><p> Same like wise RIGHT PARENT value </p>
<li><p> KET REPRESENTS values of the tree and CURRENT tells the value of PARENT </p>
<li><p> When ever KEY values GREATER then the CURRENT PARENT value then its represents the RIGHT side of the tree </p>
<li><p> select the RIGHT side elements of the KEY values which are GREATER than PARENT TREE </p></li>


<li><p> KEY === CURRENT is equal to parent value </p></li>

<li><p> DISTENCE From root node to fargest d done is 4 </p>
<li><P> Distence feom fargest d node to root node is HEIGHT of the Tree </P></li>
<li><p>search is taken as o(h) time,I can search any type of tree </p></li>
<li><p>height of the Tree is also 4 and the number of compressions is also 4 </p></li>
<li><p> IMP 11.19</p>
<li><P> Binary Search search TREE=> o(h) and in an unsorted array |---------------| o(n) </P>
<li><p> search time complexity is o(h) times </p>p </li>
<li><p> restrict the hight of the array in an unsorted array we need to ettrate o(n) times <p>
<li><p> let say construct a tree a binary search tree then h =log(n) the SEARCH will becomes =>o(h)  means SEARCH => o(logN) </p></li>

   <p> if h == logN   NODES =7 AND HEIGHT H = log 7 2 => 3
   <P> IF h == logN   NODES =4 and HEIGHT h = log 4 4 =>
  <p>in a stand binary standard there is non restrection</p> 
  <p>In a balanced binary search tree it is directly it is h= o(logn) and search = o(logn)</p>      
<li><p> Search complexity improve dramatically o(n), if h == logn  <p> 
<li><p> Search=> o(logn) </p>
<li><p> Nodes , N =7 anf HEIGHT , h=log7 2 <p></li>
<li><p> |h(l) - h(r)| ≤ 1    

  
</ul>


![](./BSTApplications/image2.png)
<p></p>

| 2  | [Height-balanced-BST](#)   
# HSTHeight-balanced-types

![](./HeightbalancedBST/image1.png)

<li><p> Red Black Tree </p></li>
<li><p> AVL trees </p></li>
<li><p> while, Red Black tree is important when compared to this AVL are more important in Binart search tree </p></li>

| 3 | [ BSTinsertion ](#)
# BST insertion types

![](./BSTinsertion/image1.png)

<p> Let insert new element 13 and compare from root element and find correct position for 13 </p>
<p> Attach the new node </p>
<p> First compare Root Node 10 is (greater then or equal) or (less then or equal) BST as a rule is that root element is greater then ket lements it is left side of the BST </P>
<P> Second if is some case ROOT element is less than KEY elements then it is belongs to RIGHT HAND side of the tree </P>
<p> INSERT '13' > 10 ------> it belongs to LEFT SIDE of the TREE  </p>
<p> INSERT  13  < 15 ------> it belongs to RIGHT SIDE of the TREE  </p>
<p> INSERT  13  > 12 ------> it belongs to LEFT SIDE of the TREE that means 12 RIGHT SIDE , LAST ELEMENT </p>
   
 <p> INSERT 16' > 10 ------> it belongs to RIGHT SIDE of the TREE  </p>
<p> INSERT  16  > 15 ------> it belongs to RIGHT SIDE of the TREE  </p>
<p> INSERT  16  < 19 ------> it belongs to LEFT SIDE of the TREE that means 19 LEFT SIDE, LAST ELEMENT  </p>
<P> TC => O(h) </P> 
   <p> HEIGHT OF THE TIME COMPLEXITY </p>

 | 4  | [Inorder successor and predecessor](#)
   # Inorder successor Inorder predecessor
  <p> Inorder successor </p>
  <p> Inorder predecessor </p>
<p> Inordersuccessor
   15(9) = 10
   15(3) = 5
   15(12) = 15
</p>
<p> Inorder predecessor 
   Ip(9) = 8
   Ip(7) = 5
   Ip(12) = 11
   
  | 5 | [BTS Delection](#)
  
</p>
<li>Inorder successor less then parent node it comes under left side</li>
<li>Greater then parent node and the key values are greater than parent node </li>   
</p>

