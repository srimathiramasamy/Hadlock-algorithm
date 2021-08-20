# Hadlock-algorithm
   It uses detour number (instead of labeling wavefront in Lee's router)  Detour number, d(P): # of grid cells directed away from its target on path P. 
 MD(S, T): the Manhattan distance between S and T.  Path length of P, l(P): l(P) = MD(S, T) + 2 d(P).  MD(S, T) fixed!  Minimize d(P) to find the shortest path. 
For any cell labeled i, label its adjacent unblocked cells away from T i+1; label i otherwise.  Time and space complexities: O(MN), but substantially reduces the # of searched cells.  Finds the shortest path between S and T
d(P): # of grid cells directed away from its target on path P.  MD(S, T): the Manhattan distance between S and T.  Path length of P, l(P): l(P) = MD(S, T) + 2d(P).  MD(S, T) fixed!  Minimize d(P) to find the shortest path.  For any cell labeled i, label its adjacent unblocked cells away from T i+1; label i otherwise.
 
