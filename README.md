<h1>UCR_DTW</h1>

&emsp;An implementation of "<b>Searching and Mining Trillions of Time Series Subsequences under Dynamic Time Warping, 2011</b>"
 
-------

<h3>Improvement</h3>
 - Fix the sorting bug. (Origin version wouldn't swap when the difference of  two values is less than 1.)
 - Delay the z-normalize for t sequence. (Only dtw apply the tz array, so there is no need to do z-normalize when keogh_data)