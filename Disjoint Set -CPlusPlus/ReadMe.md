# Solution of Merging Communities(Disjoint Set Range + Path Compression)
### The challenge is from: https://www.hackerrank.com/challenges/merging-communitiesa


People connect with each other in a social network. A connection between Person ```I``` and Person ```J``` is represented as ```M I J```. When two persons belonging to different communities connect, the net effect is the merger of both communities which ```I``` and ```J``` belongs to.

At the beginning, there are ```N``` people representing ```N``` communities. Suppose person ```1``` and ```2``` connected and later ```2``` and ```3``` connected, then ```1```,```2```, and ```3``` will belong to the same community.

There are two type of queries:

 1, ```M I J ==>```communities containing person ```I``` and ```J``` merged (if they belong to different communities).

 2, ```Q I ===>```print the size of the community to which person ```I``` belongs.

Input Format

The first line of input will contain integers ```N``` and ```Q```, i.e. the number of people and the number of queries.
The next ```Q``` lines will contain the queries.



Output Format

The output of the queries.

Sample Input
~~~~
3 6
Q 1
M 1 2
Q 2
M 2 3
Q 3
Q 2
~~~~
Sample Output
~~~~
1
2
3
3
~~~~
Explanation

Initial size of each of the community is ```1```.
