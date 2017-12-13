### Spider Monkey Optimization (SMO)

## Source code and algorithm description for Spider Monkey Optimization algorithm in multiple applications [1-2].

[1]	T. Gui, C. Ma, F. Wang and D. E. Wilkins, "Survey on swarm intelligence based routing protocols for wireless sensor networks: An extensive study." Industrial Technology (ICIT), 2016 IEEE International Conference on. IEEE, 2016.
[2]	T. Gui, C. Ma, F. Wang, J. Li and D. E. Wilkins, "A novel cluster-based routing protocol wireless sensor networks using Spider Monkey Optimization." Industrial Electronics Society, IECON 2016-42nd Annual Conference of the IEEE. IEEE, 2016.


# SMO Algorithm Description
```
Spider Monkey Optimization Clustering (SMO-C) Algorithm:
 Initialize each Spider Monkey (node) with K random cluster centers (heads)
 While (Termination criteria is not satisfied) do
	For all SM i do
		Calculate Euclidean distance of SMi with all cluster centroids assign SMi to the cluster that have nearest centroid
	End for
	Calculate the fitness (the distance of each node from the sink)
	Find the local best and global best
	Update the cluster centroids according to self-experience, local and global experience
 End while
```

