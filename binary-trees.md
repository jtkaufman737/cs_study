- Quick because they divide the number of items that need to be searched in half at each step
- The highest node in the tree is (confusingly) called the 'root'
- If you get all the way down the branches without a successful search result, you've reached a 'leaf'
- Example:

[0][1][2][3][4][5][6][7][8][9]

                 5

            /         \

           2           8  -- middle of the remaining subsets

        /     \     /     \

       1       4   7       9

    /        /   /
   0        3    6

[Q]: It looks like the middle node is selected, then the middle of the subset. I was interested in why it picked 1 and 4 to go together, I would think it be 1 or 3. Or does it always have to be the pattern that the node below is LESS THAN the one above?
