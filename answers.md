# CMPS 2200 Reciation 5
## Answers

**Name:** Natalie Gockerman


Place all written answers from `recitation-05.md` here for easier grading.







- **1b.**
When comparing both fixed and random pivot functions within qsrot and ssort on lists that are both ranodm and already sorted, I visualized both the best and worst case sccenarios. On random lists, the functions grow by nlogn. However, the random pivot option is slightly better in performance becuase the list is pratitioned more effectively. On the other hand, ssort grows much faster, at a rate of n^2. On sorted lists, the fixed pivot option begins to grow fasster at a rate of n^2 because the partitions are more uneffective while random pivot and ssort remain the same.



- **1c.**
With random lists, Timsort performs most similarly to qsort with a random pivot, but still slightly better. Both show growth of Θ(nlogn). However with sorted data, Timsort has a growth of Θ(n) making it much more efficient than any of the other sorting functions because of its ability to find the already sorted order.
