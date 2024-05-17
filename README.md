The all.csv dataset contains aggregated traffic data with a 5-minute aggregation period. We have structured the dataset's columns as follows:
Time: This represents the end time for each 5-minute aggregate period.
Hex: This is the identifier for the target frame through which vehicles have passed during the aggregation period.
Prehex: Identifies the source frame from which vehicles originated before reaching the target frame.
Count: The number of vehicles that passed through the target frame from the source frame within each period.
AvgDuration: The average travel time for vehicles moving from the source frame to the target frame.
IsPair: A binary indicator showing whether the target frame and source frame constitute a pair. Each target frame has one source frame designated as its pair, 
though it may have connections to multiple other source frames not considered as pairs.

For more Details, please read  and cite the paper:
@article{Fofanah2024Staf,
title={Staf: Convolutional Spatio-Temporal Transformer Architecture Based on Augmented Feature Learning for Traffic Flow Forecasting},
author={Fofanah, Abdul J. and Chen, David and Wen, Lian and Zhang, Shaoyang},
journal={Social Science Research Network},
url={https://ssrn.com/abstract=4826658},
doi={10.2139/ssrn.4826658},
year={2024}
}
