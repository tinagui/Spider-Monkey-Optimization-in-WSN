# Spider-Monkey-Optimization
```
Spider Monkey Optimization Clustering (SMO-C) Algorithm:
Initialize each Spider Monkey (node) with K random cluster centers (heads)
 while (Termination criteria is not satisfied) do
	for all SM i do
		calculate Euclidean distance of SMi with all cluster centroids assign SMi to the cluster that have nearest centroid
	end for
	calculate the fitness (the distance of each node from the sink)
	find the local best and global best
	update the cluster centroids according to self-experience, local and global 	experience
 end while
```
