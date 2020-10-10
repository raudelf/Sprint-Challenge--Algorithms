#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n)

I chose this because the function only has one loop. Also, the runtime depends on how large the input is which gives us a linear operation.

b) O(n^2)

I believe this would be the runttime because there are two functions nested within each other. From what I remember in class, when there are functions nessted, you multiply that function by the other's(n \* n) which gives us n^2.

c) O(n)

Like the first one, there is only one for loop. The runtime will essentially depend on how large the input is which is n. Thus, giving us a linear operation on the Big O Graph.

## Exercise II

I believe that the best way to go about this would be to do a binary search. In a way, the floors are like an array that has already been sorted. Instead of going through them one by one, we can go ahead and start in the middle to see what would happen. If the egg were to break, we would go down the building (or to the left in an array). If not, we would move up the building (or to the right of the array) until the egg would break. We would continue to do this until we reach a floor where the egg breaks, which means the floor before it broke would have to equal f.

I believe the runtime for this function would be O(log n) because it is one looping function where the input is being divided in half. Which would flatten out the curve after the first initial run.
