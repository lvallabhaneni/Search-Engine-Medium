# Search-Engine-Medium
The solution for medium level problem.
The description for the problem is:
## Description
Now let's Improve your search engine to make it support complex queries containing word sequences and use several strategies that determine how to match data.
## Objectives
In this stage, your program should be able to use such searching strategies as ALL, ANY, and NONE.
### Take, for example, these six sample lines:
Dwight Joseph djo@gmail.com <br>
Rene Webb webb@gmail.com <br>
Katie Jacobs <br>
Erick Harrington harrington@gmail.com <br>
Myrtle Medina <br>
Erick Burgess <br>
### If the strategy is ALL, the program should print lines containing all the words from the query.
Query: <br>
Harrington Erick <br>
Result: <br>
Erick Harrington harrington@gmail.com <br>
### If the strategy is ANY, the program should print the lines containing at least one word from the query.
Query: <br>
Erick Dwight webb@gmail.com <br>
Result: <br>
Erick Harrington harrington@gmail.com <br>
Erick Burgess <br>
Dwight Joseph djo@gmail.com <br>
Rene Webb webb@gmail.com <br>
### If the strategy is NONE, the program should print lines that do not contain words from the query at all:
Query: <br>
djo@gmail.com ERICK <br>
Result: <br>
Katie Jacobs <br>
Myrtle Medina <br>
Rene Webb webb@gmail.com <br>
### All listed operations are implemented in the inverted index. The results should not contain duplicates.
### Do not forget to use methods to decompose your program.
### Example
The lines that start with > represent the user input. Note that these symbols are not part of the input. <br>
=== Menu === <br>
1. Find a person <br>
2. Print all persons <br>
0. Exit <br>
> 1 <br>
Select a matching strategy: ALL, ANY, NONE <br>
> ANY <br>
Enter a name or email to search all suitable people. <br>
> Katie Erick QQQ <br>
3 persons found: <br>
Katie Jacobs <br>
Erick Harrington harrington@gmail.com <br>
Erick Burgess <br>
