# Graph-using-trie-based-indexing
The objective of this code is twofold: first, to design and implement the Graph with Trie-Based Indexing data structure, and second, to explore its practical applications and analyze its time and space complexity.

This code develops the Graph with Trie-Based Indexing data structure, implement essential algorithms, evaluate performance, and demonstrate its applicability in domains like natural language processing, network analysis, and recommendation systems.

# Implementation details:
The hybrid data structure Graph with Trie based indexing is implemented using the adjacent list, where the main list can be maximum of size 27and all the child lists can be maximum of size 26.
For every node in the main list has a variable is_end which is a booleanf data type and stores True I the character/letter stored in that node is end of any string/word and stores False if it is not. 
We are going to use the directed graph for implementation.

This hybrid data structure is mainly used for storing and retriving the strings ,so the operations we are going to perform in this data structure are inserting a string and dearching for the string.
We can even perform the deletion but it is not efficient in some cases.

*Practical applications:*
1. Browser History
2. AutoComplete
3. Spell Checkers/Auto-correct
4. Longest Prefix Matching Algorithm (Maximum Prefix Length Match)
