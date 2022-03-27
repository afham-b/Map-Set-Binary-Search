# Map-Set-Binary-Search
App sorts a set of strings, using map or set binary search

source: https://www.geeksforgeeks.org/set-vs-map-c-stl/
set and map in STL are similar in the sense that they both use Red Black Tree (A self balancing BST). Note that the time complexities of search, insert and delete are O(Log n). 
Differences: 
The difference is set is used to store only keys while map is used to store key value pairs. For example consider in the problem of printing sorted distinct elements, we use set as there is value needed for a key. While if we change the problem to print frequencies of distinct sorted elements, we use map. We need map to store array values as key and frequencies as value.
