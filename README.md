# Sorting Algorithms Comparison
These use the technique of comparing array elements with each other to figure out the final sorted order. These have time complexity lower bound of O(n logn).

Points to remember

⭐ Insertion sort is a fast in-place sorting algorithm for small input sizes.

⭐ Quicksort has tight code & so hidden constant factor in its running time is small, making it a popular algorithm for sorting large input arrays. It generally outperforms heapsort in practice.

⭐ Heapsort and Merge sort are asymptotically optimal comparison sorts, and no comparison sort exists that is faster by more than a constant factor.

⭐ Counting sort is efficient when there are smaller int eger values with multiple occurences.

⭐ Radix sort is useful in problems where there are numbers in large ranges.

⭐ Bucket Sort is useful when input is uniformly distributed over a range and there are floating point values.

**#BIG-O Cheat Sheet** https://www.bigocheatsheet.com/ >> (For Data structure Wiki Links)

Common Data Structure Operations
Structure	         Time Complexity	                                                                                     Space Complexity
                   Average	                                        Worst	                                               Worst
                   Access	       Sear	      Inser   	  Dele    	  Access	      Sear	      Inser	     Dele 
**Array**          Θ(1)	         Θ(n)	      Θ(n)	      Θ(n)	      O(1)	        O(n)	      O(n)	     O(n)	           O(n)
**Stack**	         Θ(n)	         Θ(n)	      Θ(1)	      Θ(1)	      O(n)	        O(n)	      O(1)	     O(1)	           O(n)
**Queue**	         Θ(n)	         Θ(n)       Θ(1)	      Θ(1)	      O(n)	        O(n)	      O(1)	     O(1)	           O(n)
**Singly-Linked**	 Θ(n)	         Θ(n)       Θ(1)	      Θ(1)	      O(n)	        O(n)	      O(1)	     O(1)	           O(n)
**Doubly-Linked**	 Θ(n)	         Θ(n)       Θ(1)	      Θ(1)	      O(n)	        O(n)	      O(1)	     O(1)	           O(n)
**Skip List**	     Θ(log(n))     Θ(log(n))	Θ(log(n))	  Θ(log(n))	  O(n)	        O(n)	      O(n)	     O(n)	           O(n log(n))
**Hash Table**	   N/A	         Θ(1)	      Θ(1)	      Θ(1)	      N/A	          O(n)	      O(n)	     O(n)	           O(n)
**Binary Search**	 Θ(log(n))	   Θ(log(n))	Θ(log(n))	  Θ(log(n))	  O(n)	        O(n)	      O(n)	     O(n)	           O(n)
**Cartesian**	     N/A	         Θ(log(n))	Θ(log(n))	  Θ(log(n))	  N/A	          O(n)	      O(n)	     O(n)	           O(n)
**B-Tree**	       Θ(log(n))	   Θ(log(n))	Θ(log(n))	  Θ(log(n))	  O(log(n))	    O(log(n))	  O(log(n))	 O(log(n))	     O(n)
**Red-Black**	     Θ(log(n))	   Θ(log(n))	Θ(log(n))	  Θ(log(n))	  O(log(n))	    O(log(n))	  O(log(n))	 O(log(n))	     O(n)  
**Splay**	         N/A	         Θ(log(n))	Θ(log(n))	  Θ(log(n))	  N/A	          O(log(n))	  O(log(n))	 O(log(n))	     O(n)
**AVL**	           Θ(log(n))	   Θ(log(n))	Θ(log(n))	  Θ(log(n))	  O(log(n))	    O(log(n))	  O(log(n))	 O(log(n))	     O(n)
**KD**	           Θ(log(n))	   Θ(log(n))	Θ(log(n))	  Θ(log(n))	  O(n)	        O(n)	      O(n)	     O(n)	           O(n)

Array Sorting Algorithms
Algorithm	         Time Complexity	                           Space Complexity
                   Best	        Average	        Worst	         Worst
Quicksort	         Ω(n log(n))	Θ(n log(n))	    O(n^2)	       O(log(n))
Mergesort	         Ω(n log(n))	Θ(n log(n))	    O(n log(n))	   O(n)
Timsort	           Ω(n)	        Θ(n log(n))	    O(n log(n))	   O(n)
Heapsort	         Ω(n log(n))	Θ(n log(n))	    O(n log(n))	   O(1)
Bubble Sort	       Ω(n)	        Θ(n^2)	        O(n^2)	       O(1)
Insertion Sort	   Ω(n)	        Θ(n^2)	        O(n^2)	       O(1)
Selection Sort	   Ω(n^2)	      Θ(n^2)	        O(n^2)	       O(1)
Tree Sort	         Ω(n log(n))	Θ(n log(n))	    O(n^2)	       O(n)
Shell Sort	       Ω(n log(n))	Θ(n(log(n))^2)	O(n(log(n))^2) O(1)
Bucket Sort	       Ω(n+k)	      Θ(n+k)          O(n^2)	       O(n)
Radix Sort	       Ω(nk)	      Θ(nk)	          O(nk)	         O(n+k)
Counting Sort	     Ω(n+k)	      Θ(n+k)	        O(n+k)	       O(k)
Cubesort	         Ω(n)	        Θ(n log(n))	    O(n log(n))	   O(n)


![image](https://user-images.githubusercontent.com/54086674/145286009-4da1721e-b33d-4950-b03d-f13c7e63f8e1.png)

  
