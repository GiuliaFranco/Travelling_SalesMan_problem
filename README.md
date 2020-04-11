# TSP-heuristics
Implementing various heuristics for Travelling Salesman Problem (TSP), Namely Lin-Kernighan Heuristic, Nearest Neighour Heuristic, genetic algorithm, Simulated Annealing

#abouts files attached
	TSP_Data: is directory of All TSPLIB instances (data needs to keep this kind of format!)
	readData.py: is reading file from TSP_Data
	All other python files or implemetation of algorithm

Steps for running algorithms
# terminal commands
	$ python 'algorithm.py' 'filename'  #for nearest-neighbour
-'algorithm.py': 2-opt.py, nn.py, ga_2-opt_tsp.py, ga_tsp.py	   
-'filename' picked any file from TSP_Data folder eg. ch130.tsp or a280.tsp

# Example runs	
	$ python 2-opt.py kroB100.tsp
	
# Example runs other algorithms in other_script folder
	$ python nn.py kroB100.tsp
	$ python ga_tsp.py kroB100.tsp
	$ python ga_2-opt_tsp.py kroB100.tsp
	$ python runSA.py kroB100.tsp
	$ python runSA2opt.py kroB100.tsp 
 
 
 
