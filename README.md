# Spider Monkey Optimization (SMO)
Source code and algorithm description for Spider Monkey Optimization algorithm [1-2]. 

[1]	T. Gui, C. Ma, F. Wang and D. E. Wilkins, "Survey on swarm intelligence based routing protocols for wireless sensor networks: An extensive study." Industrial Technology (ICIT), 2016 IEEE International Conference on. IEEE, 2016. <br>
[2]	T. Gui, C. Ma, F. Wang, J. Li and D. E. Wilkins, "A novel cluster-based routing protocol wireless sensor networks using Spider Monkey Optimization." Industrial Electronics Society, IECON 2016-42nd Annual Conference of the IEEE. IEEE, 2016.

## Baseline Routing Protocols 
LEACH (multiple MATLAB packages) 
https://www.mathworks.com/matlabcentral/fileexchange/48162-leach--low-energy-adaptive-clustering-hierarchy-protocol-
https://www.mathworks.com/matlabcentral/fileexchange/40115-low-energy-adaptive-clustering-hierarchy-protocol--leach-


## Spider Monkey Optimization Algorithm Description:
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




