arithmeticSquare.py: pick the best average out of all pair sum of the two neighbors. <br /><br />
cuttingIntervals.py: flatten the intervals into time events, get (intervals with max cuts information) in between start events and end events. And then sort the (intervals with max cuts information) based on max cut that can be achieved. <br /><br />
finalExam.cpp: we utilize the c++ map data structure to help us achieve log N complexity insert and log N complexity delete. We store the difficulty intervals in a map structure, and modify it as we choose and assign to students, using binary search. <br /><br />
PrimesAndQueris.cpp: first pre - req is that we understand lifting-the-exponent lemma. Then since N is within the range of 5 * 10^5, and also based on the hint that we have range sum queries and point update, we would want to look at structures such as segment tree. After the data structure is chosen, we examine the formulas outlined in lifting-the-exponent lemma, and break it into several segment trees. <br /><br />