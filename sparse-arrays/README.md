# Sparse Arrays

There is a collection of input strings and a collection of query strings. For each query string, determine how many times it occurs in the list of input strings.

For example, given input strings = ['ab', 'ab', 'abc'] and queries = ['ab', 'abc', 'bc'], we find 2 instances of 'ab', 1 of 'abc' and 0 of 'bc'. For each query, we add an element to our return array, results = [2,1,0].

Function Description
Complete the function matchingStrings in the editor below. The function must return an array of integers representing the frequency of occurrence of each query string in strings.

matchingStrings has the following parameters:
1. strings - an array of strings to search
2. queries - an array of query strings

Input Format
The first line contains and integer n, the size of strings. 
Each of the next n lines contains a string strings[i]. 
The next line contains q, the size of queries. 
Each of the next q lines contains a string q[i].

Constraints
1 =< n =< 1000
1 =< q =< 1000
1 =< |strings[i], |queries[i] =< 20
