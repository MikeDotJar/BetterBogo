This is my take on an edited form of Bogo Sort. IF you don't know, Bogo sort (also known as bad sort), is a sorting algorithm that 
relies on randomizing the array until all the elements are sorted. This algorithm is meant to be one of the worst sorting algorithms 
ever. Because of this, I decided to make a modified Bogo Sort which I named BetterBogo Sort which works similarly to Bogo sort since
it also randomizes the given array. However, after each randomization the algorithm will check if the first element is the smallest
in the array. If it's the smallest, then the algorithm will increase the index by 1 and randomize the array from that point until
the entire array is sorted. Obviously this is still very inefficient and would virtually go on forever with larger arrays. However,
it was a very fun side project. I Also included algorithms BubbleSort, SelectionSort, and InsertionSort for comparison. Please note:
I did make the BubbleSort, SelectionSort, and InsertionSort algorithms in my code.