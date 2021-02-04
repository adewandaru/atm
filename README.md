# atm
Aggregated Topic Model

This topic model works on trained partitions from LLDA (we are sticking to Mallet's implementation of it).
What is needed from the trained partitions:
total-[steps].keys
total-[steps].xml 
files.

E.g. 
total-0.keys -> contains keys from 0-10000 document (just an example if you divide 10K partitions)
total-10000.eys -> contains keys from second partition (ie.e 10.000 to 20.000th documents)

