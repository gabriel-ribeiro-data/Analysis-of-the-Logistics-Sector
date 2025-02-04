
# Time Analysis of Sorting Algorithms in Java: SelectionSort, BinaryInsertionSort, and Heapsort.
----

### This repository features a data analysis project for a company's logistics sector using Power BI. The dataset was cleaned and processed, resulting in the creation of an interactive dashboard for data visualization and interpretation. Please note that the language of the implementation is in the authors' native language (Brazilian Portuguese).
----

## Introduction
  This project consists of developing a software application using the Java programming language, focused on analyzing the performance of sorting algorithms. The main objective is to compare the execution time of three sorting algorithms: SelectionSort, BinaryInsertionSort, and HeapSort. The application processes datasets of varying sizes (1,000, 5,000, and 10,000 numbers) to measure and evaluate the efficiency of each algorithm in sorting tasks.

Additionally, the aim is to provide a clear and practical implementation, enabling users to understand how different sorting algorithms perform under various conditions. This project highlights the importance of algorithm efficiency in computer science and helps users deepen their knowledge of performance analysis and the trade-offs involved in algorithm design.

The sorting algorithms analyzed in this project differ significantly in their approach and time complexity. SelectionSort, a simple comparison-based algorithm, iteratively selects the smallest element and places it in its correct position. BinaryInsertionSort optimizes the insertion process by using binary search to determine the position of each element. HeapSort, on the other hand, leverages the heap data structure to efficiently sort elements. By comparing their performance, this project provides valuable insights into how algorithmic design impacts computational efficiency.

## Dashboard Creation from Transformed Data
  The Big-O notation represents the upper bound of the execution time, indicating the complexity of the worst case, that is, the one containing the largest number of instructions. The order of Big-O terms is given by: O(1) < O(log n) < O(Sqrt(n)) < O(n) < O(n log n) < O(n^2) < O(n^3) < O(2^n). The larger the term, the worse the algorithm's efficiency will be, and the greater the number of instructions, as shown in the graph in Fig. 1.

<table align="center">
  <tr>
    <td align="center">
      <img src='/Images/Image 1.png' width="1000">
    </td>
  </tr>
  <tr>
    <td align="center">
      <em>Fig. 1. Big-O notation;
      Source: DicionarioTec (2024)</em>
    </td>
  </tr>
</table>

## Spreadsheet Transformation Using Power Query
  As seen in Fig. 2, the spreadsheet was transformed using the Power Query tool so that the dashboard could later be designed as desired.
  
<table align="center">
  <tr>
    <td align="center">
      <img src='/Images/Image 2.png' width="1000">
    </td>
  </tr>
  <tr>
    <td align="center">
      <em>Fig. 2. Graphical Representation of a Section of the Spreadsheet </em>
    </td>
  </tr>
</table>
<br>

## Authors
