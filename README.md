﻿# insertionsort
In this implementation, we have two counters: i and j. The outer loop with counter i starts from the second element (i = 1) and iterates through the array. This represents the new card being picked and inserted into the sorted sequence.

The inner loop with counter j compares the current card (arr[i]) with the previous cards (arr[j]) and shifts the previous cards one position to the right until the correct position for the current card is found.

By using these two counters, we ensure that we only work with the first i-1 elements of the array
