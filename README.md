# Travelling-Salesman-Problem

    For this project, we implement four algorithms.
        Brute Forece            (.\TSP-BruteForce.cpp)
        Dynamic Programming     (.\TSP-DP.cpp)
        Greedy                  (.\TSPNearestNeighbor.java)
        Lin-Kernighan           (all files in .\LK)
    All codes runs well in Windows cmd.exe by  ".\g++ -std=c++11 ...." 

    We are using adjacency matrix to represent a graph for TSP.

    Our input file is built by (.\Input file\TSP_inputfile.cpp), which built N*N adjacency matrix. 
    The weight of each edges is randomly chosen between 50 and 500.

    We use N=9 / 30 / 100 / 300 to test all algorithms. All these input files is in (.\Input file).

# Lin-Kernighan

    The way to compile this code in cmd is ".\g++ -std=c++ -o TSP-LK LKMatrixcpp LKMain.cpp"

    Our LK code uses the result of Greedy as input tour.
    (for N=9/30/100/300, they are in .\Input file\tour9/30/100/300.txt).

    The maximum of the 2-opt is set as 100. If N>100, it's better to flip more times than 100. 

# P.S. 
    If you want to run the code, you must edit the code for proper input file to get proper result in accordance with your need.
