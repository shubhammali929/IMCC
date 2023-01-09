Step 1: Total_water = 0

Step 2: Traverse the array from start to end.

    (a) For every element, traverse the array from start to that index and find the maximum on its left. Let this be max_left.

    (b) Traverse the array from the current index to end and find the maximum on its right. Let this be max_right.

    (c) Trapped water in this, column=min((max_left, max_right)- array[i]).

    (d) Total_water = Total_water + Trapped_water.

Step 3: Print the Total_water.
