# Binary_Search

### Term.java
Implement an immutable comparable data type Term in
Term.java that represents an autocomplete term: a string query and an associated real-valued
weight. You must implement the following API, which supports comparing terms by three
different orders: lexicographic order by query string (the natural order); in descending order by
weight (an alternate order); and lexicographic order by query string but using only the first
r characters (a family of alternate orderings). The last order may seem a bit odd, but you will use
it in Problem 3 to find all terms that start with a given prefix (of length r).

### BinarySearchDeluxe.java
When binary searching a sorted array that contains more than
one key equal to the search key, the client may want to know the index of either the first or the last
such key. 

### Autocomplete.java
Implement a data type that provides autocomplete
functionality for a given set of string and weights, using Term and BinarySearchDeluxe. To
do so, sort the terms in lexicographic order; use binary search to find the set of terms that start with
a given prefix; and sort the matching terms in descending order by weight.
