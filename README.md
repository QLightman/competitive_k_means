# competitive_k_means
Apply the idea of Rival Penalized Competitive Learning (RPCL) to k-mean
so that the number of clusters is automatically determined. The way to locate the extra center is by
examing the distances between each centers. I assume that the extra center cutting apart some of the points in other center, so after each time the center of
each cluster is relocated, we need to select the two centers where their distance
is the shortest. Then kick the center where its group is smaller than the other
point away to some ratio. 

## Dataset
![three-cluster dataset](https://github.com/QLightman/competitive_k_means/blob/master/data.png)
## Result
![three-cluster dataset result](https://github.com/QLightman/competitive_k_means/blob/master/iterations/6interations.jpg)

## License
![MIT](https://github.com/QLightman/k-means/blob/master/LICENSE)