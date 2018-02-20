# OracleNet
Code, animations, and supplementary material for OracleNet 


[![OracleNet (Paper 168, RSS 2018)](https://img.youtube.com/vi/2KYesBrx2kk/0.jpg)](https://youtu.be/2KYesBrx2kk "OracleNet (Paper 168, RSS 2018)")


Performance trends with variable dataset and network sizes
----------------------------------------------------------

To analyze the learning capabilities of OracleNet, we performed experiments on environment 'Difficult 2' (refer to Fig. 5 in the paper) with variable dataset and network sizes. Success rates and path optimality (benchmarked against A*) are used to measure performance trends. Note that all trends presented here do not involve the use of the repair and rewire models, since the purpose is to (1) study the role of dataset and network sizes in generating successfull paths, and (2) to show that with sufficient data and an appropriately chosen well-trained network, OracleNet is able to generate near-optimal feasible paths on its own and repair is needed only to handle the edge cases while rewire takes it closer to being absolutely optimal. 

### Variable Dataset Sizes ###

![alt text](../master/Trends/trend_po_d.png?raw=true "Dataset Trends")


The network size is kept fixed here (same as the network architecture described in Section IV.A) and the dataset size is incrementally increased to a maximum of 100,000 valid A* generated paths.  
