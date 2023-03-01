# 8-kyu-What-s-the-real-floor-
Americans are odd people: in their buildings, the first floor is actually the ground floor and there is no 13th floor (due to superstition).
<br><br>
Write a function that given a floor in the american system returns the floor in the european system.
<br><br>
With the 1st floor being replaced by the ground floor and the 13th floor being removed, the numbers move down to take their place. In case of above 13, they move down by two because there are two omitted numbers below them.
<br><br>
Basements (negatives) stay the same as the universal level.
<br><br>
Examples
<br>
1  =>  0 
<br>
0  =>  0
<br>
5  =>  4
<br>
15  =>  13
<br>
-3  =>  -3
