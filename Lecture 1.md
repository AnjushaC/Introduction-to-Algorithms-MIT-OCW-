
# Algorithmic thinking, Peak finding <center>
### Why time complexities matter? 
Asymptotic complexity : How an algorithm performs (how fast) as input size grows.<br/>
Efficient procedures for solving large scale problems in this class. Scalability is also a concern.
## Peak Finding
### One dimensional version
Given an array of length n, find a pea,k where a number at index i is a 'peak', if 
                                      value[i-1] <= value[i] >= value[i+1], if i-1 <0 or i+1 >length of array, check only one side

