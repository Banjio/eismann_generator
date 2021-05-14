# Challenge 

* Generate an eisman signal from a sample file in minute resolution
for one month of data
* Save to file and plot &Rightarrow; This is the final result


# Approach

* Without doing much data analysis I would suppose that 
the eisman signal follows some pattern
* Therefore, a good start is to build simple samples
based on the time stamps only

# Implementation

* DataLoader &Rightarrow; Loads and preprocesses the data (mainly a pandas wrapper)
* DataPool &Rightarrow; Splits the data so that samples can be drawn from the pool
* DataSampler &Rightarrow; Samples from the data pool