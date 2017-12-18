# ❀ Spider Monkey Optimization (SMO) ❀
Source code and algorithm description for SMO algorithm in Wireless Sensor Networks (WSN)

## Cluster-Based Spider Monkey Optimization Protocol (SMO-C) [1-2]
```
 Initialize each Spider Monkey (SM) with K random cluster centers 
 While (termination criteria is not satisfied) do
	For all SMi do
		Calculate Euclidean distance of SMi with all cluster centroids 
		Assign SMi to the cluster that have nearest centroid
	End for
	Calculate the fitness 
	Find the local best and global best
	Update the cluster centroids according to self-experience, local and global experience
 End while
```

[1]	T. Gui, C. Ma, F. Wang and D. E. Wilkins, "Survey on swarm intelligence based routing protocols for wireless sensor networks: An extensive study." Industrial Technology (ICIT), 2016 IEEE International Conference on. IEEE, 2016. <br>
[2]	T. Gui, C. Ma, F. Wang, J. Li and D. E. Wilkins, "A novel cluster-based routing protocol wireless sensor networks using Spider Monkey Optimization." Industrial Electronics Society, IECON 2016-42nd Annual Conference of the IEEE. IEEE, 2016.


## Other Monkey-Based Optimization Algorithms in WSN [3-4]
**Rhesus Macaque Optimization Algorithm (RMO) [3]**
```
Set-up phase:
Step 1. Construction of sensor network:
Step 2. Run the LEACH model once
Step 3. Find redundant cluster heads
Step 4. Attach redundant cluster heads to the nearest cluster
Steady state:
Step 5. Randomly choose nodes for communication 
```

**Niching Monkey Optimization Algorithm (NMA) [4]**
```
Step 1. Compute mode shapes 
Step 2. Dual-structure coding
Step 3. Determine the number of monkeys M
Step 4. Population initialization using the principle of chaos
Step 5. Divide M monkeys into N niches
Step 6. Initial climb process
Step 7. Calculate fitness function 
Step 8. Removal of the monkey with highest fitness value
Step 9.  Place new monkey to the niche
Step 10. Calculate the average fitness value for every niche
Step 11. Replace the worst fitness value 
Step 12. Watch jump process
Step 13. Somersault process
Step 14. Terminate when criterion is satisfied
```

[3]	S. Kumar, and S. M. Kusuma. "Clustering protocol for wireless sensor networks based on Rhesus Macaque (Macaca mulatta) animal's social behavior." International Journal of Computer Applications 87.8 (2014) <br>
[4]	T. Yi, et al. "Sensor placement optimization in structural health monitoring using niching monkey algorithm." International Journal of Structural Stability and Dynamics 14.05 (2014).


## Baseline Routing Protocols [5-6]
<strong>Low-Energy Adaptive Clustering Hierarchy (LEACH) [5] <br>
[MATLAB Package 1](https://www.mathworks.com/matlabcentral/fileexchange/48162-leach--low-energy-adaptive-clustering-hierarchy-protocol-) <br>
[MATLAB Package 2](https://www.mathworks.com/matlabcentral/fileexchange/40115-low-energy-adaptive-clustering-hierarchy-protocol--leach-) <br>

**Energy Aware Multi-hop Multi-path Hierarchical (EAMMH) [6]** <br>



[5]	W. Heinzelman, Chandrakasan, A., and Balakrishnan, H., "Energy-Efficient Communication Protocols for Wireless Microsensor Networks", Proceedings of the 33rd Hawaaian International Conference on Systems Science (HICSS), January 2000. <br>
[6]	M.R. Mundada, V CyrilRaj and T Bhuvaneswari “Energy Aware Multi-Hop Multi-Path Hierarchical (EAMMH) Routing Protocol for Wireless Sensor Networks” European Journal Of Scientific Research ISSN 1450-216X Vol. 88 No 4 October, 2012.
