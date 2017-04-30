## Effect of Discretization 

Apparently, central park is better visible with a finer discretization. 

<img src="https://github.com/jArumugam/BigFish/blob/master/results/binned_fares_40x40.png" width="400" height="400" /><img src="https://github.com/jArumugam/BigFish/blob/master/results/binned_fares_80x80.png" width="400" height="400" /> 

However, dependence of other structures in the data on discretization is not that apparent. 

Sweet spots do change with discretization and are more precisely located. 

<center>
<img src="https://github.com/jArumugam/BigFish/blob/master/results/Weekday-00_40x40.png" width="485" height="300" /><img src="https://github.com/jArumugam/BigFish/blob/master/results/Weekday-00_80x80.png" width="485" height="300" /> 
</center>

Theweights indicate optimality of a grid point with respect to pickups. Higher the weights, the better is a location (at a particular instance).


## Network Abstraction of Pickup Locations 

Here the pickup locations are abstracted as a graph. A weighted graph reveals structure differently. 

<img src="https://github.com/jArumugam/BigFish/blob/master/results/unweighted_graph_Y16_full.png" width="350" height="350" /><img src="https://github.com/jArumugam/BigFish/blob/master/results/weighted_graph_Y16_partial.png" width="350" height="350" />

The weighted graph was formed based on the number of trips between nodes. 

