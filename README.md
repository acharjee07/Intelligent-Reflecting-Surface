# This repository contains my solution to the IEEE Signal Processing Cup 2021


<center><img src="https://signalprocessingsociety.org/sites/default/files/uploads/images/community_involvement/SPCup2021.jpg"></center>

## Configuring an Intelligent Reflecting Surface with gradiant based optimization


With Pytorch an algoritm is implemented. By whcih given a channel matrix, a 64*64 grid IRS is optimized with the gradient calculated by maximizing the power of a the signal.

The algorithm works by an iterative approach in each iteratoin total 4096 elements are are selected either 1 or -1 based on the gradient value of each elements. It takes less than 10 iteratin to reach the optimum configuraiton 
