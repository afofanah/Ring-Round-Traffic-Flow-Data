The all.csv dataset contains aggregated traffic data with a 5-minute aggregation period. We have structured the dataset's columns as follows:
Time: This represents the end time for each 5-minute aggregate period.
Hex: This is the identifier for the target frame through which vehicles have passed during the aggregation period.
Prehex: Identifies the source frame from which vehicles originated before reaching the target frame.
Count: The number of vehicles that passed through the target frame from the source frame within each period.
AvgDuration: The average travel time for vehicles moving from the source frame to the target frame.
IsPair: A binary indicator showing whether the target frame and source frame constitute a pair. Each target frame has one source frame designated as its pair, 
though it may have connections to multiple other source frames not considered as pairs.

For more Details, please read the paper title: "STAF: Convolutional Spatio-Temporal Transformer Architecture based on Augmented Feature Learning for Traffic Flow Forecasting"
Authors: Abdul Joseph Fofanah, Larry Wen, David Chen, and Shaoyang Zhang
