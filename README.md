# Assignment
Wavelabs’ Lab setup consists of n nodes numbered from 0 to n - 1 connected by undirected node-to-node connections forming a network where connections[i] = [ai, bi] represents a connection between nodes ai and bi. Any node can reach other nodes directly or indirectly through the network.
A critical connection is a connection that, if removed, will make some nodes unable to reach some other node.
As a network engineer, it's important to maintain a list of critical connections. Return all critical connections in the network in any order.
Example:
 
Input: n = 4, connections = [[0,1],[1,2],[2,0],[1,3]]
Output: [[1,3]]
Explanation: [[3,1]] is also accepted.

Constraints:
●	2 <= n <= 105
●	n - 1 <= connections.length <= 105
●	0 <= ai, bi <= n - 1
●	ai != bi
●	There are no repeated connections.

Solve the questions in C++
