# Homework 4

## Project Goals
The goal of this project is to:
1.	Familiarize students with **sorting**
2.  Familiarize students with the **time complexity**.

## Program
First choose TWO sorting algorithms from the following list:
- selection sort
-	insertion sort
-	bubble sort  

and ONE algorithm from the following list:
-	merge sort
-	quick sort 
-	radix sort

Create a program which randomly generate [1,000, 10,000, and 100,000] integer values (in the range of 0 to 10^6) to be inserted into a data structure. NOTE that this data should not be sorted AND all algorithms should use the same data when the data size is the same.  

Test the speed of each algorithm for sorting the data.  

Also, test the speed of each algorithm when the data is already sorted (for the same input data). 

The following output should be provided for an average of 10 sorts of **each algorithm and input size**:
-	the CPU time (use the same machine)
-	the number of comparisons
-	the number of swaps 

Note: You can only use (i.e., copy) code from the book and slides. You need to develop the rest of the code yourself. 

Deliverables:
-	Source code for each of your classes
-	A main driver that tests the classes with randomly generated data.
-	The data input files (there should be 6 of them – sorted and unsorted data for each input size)
- Test output of your algorithms (with a table of each run and their averages for each of the metrics listed above)
  -	Tables
    - Include data for individual runs
    - 6 tables per algorithm (so 18 total)
    - Rows: single program execution
    - Comlumns: metrics (run time, comparisons, swaps) 
    - Example: 
      - Algorithm 1 1000: Sorted 
      - Algorithm 1 1000: Unsorted
      - Algorithm 1 10000: Sorted 
      - Algorithm 1 10000: Unsorted
      - Algorithm 1 100000: Sorted 
      - Algorithm 1 100000: Unsorted
  - Graphs
    - Use averages of the 10 runs
    - 6 graphs
      - Metric + scenario 
    - Example:
      - RunTime – Unsorted
    - Graph averages for each algorithm
      - Algorithm 1
      - Algorithm 2
      - Algorithm 3 
    - input size should be the x-axis
    - time/comparison/swaps should be the y-axis
