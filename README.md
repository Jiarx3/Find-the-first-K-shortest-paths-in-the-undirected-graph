# Find-the-first-K-shortest-paths-in-the-undirected-graph

Write a program that does the following:
1.The program begins by receiving input related to building an undirected graph:
(a) The first is two integers m,n, the former represents the number of vertices of the graph, followed by the number of edges.
(b) Next enter m strings, which are the vertex names.
(c) Finally, there are three inputs in line n, which are two strings S1,S2, and then an integer w.
Specifically, there is an edge between the vertices of S1 and S2, with a weight of w.
2.Then accept the string until you hit the keyword "quit" :
(a) If you read "ban", read another string S1 and add it to the blacklist of relay points. Under the
No point on the blacklist can be used as a relay point for all paths that are searched for the second time.
(b) If you read "unban", read another string S1 to remove it from the blacklist of the middle point.
(c) If you read "maxTrans", read another integer Y. Whatever path we find next time is going to be medium
The number of successor points is less than or equal to Y. If Y is negative, the default value is unrestricted
The number.
(d) If you read "paths", then the next two strings, S1 and S2, represent the beginning and end, respectively, and then follow
Down here is an integer k. Output k shortest simple paths from S1 to S2, and output
Each path must meet the requirements for relay points and not use blacklisted vertices
As a relay point. If the total number of paths meeting all conditions is less than k, all paths are output, and
Output from shortest to longest and indicate the length of each path. In addition, also print out the output
The total number of paths.
(e) If you read "quit", the program is over.
3.The processing time of each instruction is required to be less than 3 seconds.
