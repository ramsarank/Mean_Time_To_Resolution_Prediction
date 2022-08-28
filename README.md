## MTTR Metric - Mean Time to Resolve is the average time taken to fully resolve a ticket (failure). It includes time spent in 
1. Detecting the failure
2. Problem Diagnosis
3. Fixing the issue
4. Time spent on ensuring the failure not reoccuring

The MTTR has a strong connection (correlation) with customer satisifcation. 

Note about calculation consideration:
Sum the resolution times of the tickets for a required period of time and divide the sum by total number of tickets in the same period of time.

There are submetrics that we can look for the contributions and make a plan of action to target the submetrics, which indirectly gives the improvement in the MTTR metric -- the final metric we are concerned about:
1. Mean Time To Respond
2. Mean TIme To Acknowledge
3. Mean Time To Failure
