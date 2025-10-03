CCSS Tutorial \#1: Early warning signals for tipping in complex systems -- miniproject
 
The aim of this project is for you to get some hands-on experience of calculating early warning signals for some sample time series displaying different features. Each group will give a short presentation ($\sim$ 5 minutes) on their progress and challenges. Hopefully by the end of the project you will have a better understanding of using lag-1 autocorrelation and variance to detect approaching tipping points.

Challenge: Using the first six sample time series provided, can you match each time series to each of the following scenarios:

1) Stationary time series (no change in forcing or noise)
2) Stationary system (no change in forcing) but changing noise property
3) Drifting linear system that cannot undergo tipping
4) Fast system that is slowly approaching fold bifurcation (classical scenario)
5) Slow system that at some instance in the time series crosses a fold bifurcation (although no tipping occurs during the full time series)
6) Fast system moving away from a fold bifurcation
   
Step 1: Just looking at the time series alone, how would you match the time series to the scenarios?

Step 2: Using the provided detrended time series, which have been detrended by removing the deterministic (no noise) solution, calculate the lag-1 autocorrelation and variance over a sliding window (suggest to start with using a quarter of the time series). Has this helped to classify the time series? How would you match the time series to the scenarios now?

Extra: Experiment with different window lengths and/or use your own detrending methods. For the stationary system with changing noise property, can you identify what feature of the noise is changing? Can you identify when the slow system crosses the fold bifurcation? A seventh time series has also been provided, can you describe a possible scenario for this time series? If you have your own time series, can you get any early warning? 


Contents of data:

t - Array of time points

ts# - Numbered original time series

ts#_detrended - Numbered original time series that have been detrended
