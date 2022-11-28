# Binary Search Tree

## Write the Binary-Search-Tree stages of the sequence [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

- We start our first phase based on 7.

 
   7 



- We compare 7 with the side element 5 and write it to the right or left of the case. This comparison process will be the same for each stage. We continue our stages by making comparisons.7> is greater than 5 so we add 5 to the left side of 7.

 
      7
     /
    5 
       


- We add 1 to the left of 5 since 5>1 

 
         7
        /
       5
      /
     1
 


- 8>7>5>1 This time, we do our comparison not according to 1, but according to 7, which is the top element of our tree. This is because 8 is greater than 7, 5 or 1. As a result we add 8 to the right side of 7.
 

         7
        / \
       5   8
      /
     1

 


- We add it to the right of 1 because 5>3>1 3 is greater than 1 and less than 5.

 
         7
        / \
       5   8
      /
     1
      \
       3
 


- We add 6>3>1>5 to the right of 5 because 6 is greater than 3, less than 1, and greater than 5.
 

         7
        / \
       5   8
      / \
     1   6
      \
       3 
       



- Since the number 0 is the smallest of this sequence and also less than 1, we add it to the left side of 1.

 
           7
          / \
         5   8
        / \
       1   6
      / \
     0   3

 

- 9>8>7>6>5>1>0 9 is greater than 8 in this case, so we add it to the right of 8.

 
         7
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3

 


- We add it to the right of 3 because 4>3 

 
         7
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3
        \
         4
 


- 2>3 is added to the left of 3 because it is less than 2 3.
- As a result, our root is 7, 5 on the left and 8 on the right.

 
         7
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3
      / \
     2   4 
     

