# DBSCAN_1D

![DBSCAN]('DBSCAN_1D.png')

Python implementation of DBSCAN algorithm for 1D

DBSCAN (Density-based spatial clustering of applications with noise) is a data clustering algorithm proposed by Martin Ester et al [1].

Given a set of points and a maximum allowed gap the algorithm groups the points into clusters so that any point in the cluster is within maximum allowed gap distance to another point in the same cluster. If a point is at a distance higher than the maximum allowed gap to any existing clusters of points then it becomes part of a new cluster.

There is a 3rd parameter, minimum number of points in a cluster which implies that small clusters (with less elements than specified by this parameter) are discarded.


*From Wikipedia:*

Two points p and q are density-connected if there is a point o such that both p and q are density-reachable from o. Density-connectedness is symmetric.

A cluster then satisfies two properties:
* All points within the cluster are mutually density-connected.
* If a point is density-reachable from any point of the cluster, it is part of the cluster as well.
