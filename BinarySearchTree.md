

# Binary Search Tree Project

Example Array= [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] <br>

> I choose the root as 6 <br>

* 7 > 6 so, 7 goes into **right** branch. <br>

* 5 < 6 so, 5 goes into **left** branch. <br>

* 1 < 6 so, goes into **left** branch. 1 < 5 so, goes into **left** branch again(below the 5) <br>       

* 8 > 6 so, 8 goes into **right** branch. 7 < 8 so, goes into **right** branch again(below the 7) <br>

* 3 < 6 so, goes into **left** branch. 3 < 5 so, goes into **left** branch again(below the 5). 3>1 so, it goes into **right** side of the 1 <br>     
   
* 0 < 6 so, goes into **left** branch. 0 < 5 so, goes into **left** branch again(below the 5). 0<1 so, it goes into **left** branch(below the 1) <br>  

* 9 > 6 so, goes into **right** branch.9 > 7 so, goes into **right** branch again(below the 7). 8<9 so, it goes into **right** branch(below the 8) <br>  

* 4 < 6 so, goes into **left** branch. 4<5 so, goes into **left** branch again(below the 5). 1<4 so, it goes into **right** branch(below the 1) <br> 

* 2 < 6 so, goes into **left** branch. 2<5 so, goes into **left** branch again(below the 5). 2>1 so, it goes into **right** branch(below the 1). 2<4 so, goes into **left** branch again(below the 4)<br> 
-------- 6------   <br>
-------5/-\7----   <br>
---- 1/\3--/\8--   <br>
---0/\4----/\9--   <br>
-----2/\ --------   <br>