# School_District_Analysis
# Overview of school district analysis 
Expanding on the past PyCitySchools pandas-Py activity. 
A school district collects the standarized scores for math and reading. Maria is the chief data scientist, we are assisting her. 
The analysis will inform the school board of how to distribute the spending for the next school year.
Our new objective: To help the school board find the faulty reading and math scores for Thomas High School. 
Due to academic dishonesty, we want to find these figures, and replace the score with NaNs. 
We want to ensure that this does not affect the previous data. After, our supervisor has asked to repeat the school analysis. 

# Results
# 1. How is the district summary affected?
Image Old: 
Image New:
Observing the two ouputs above, we see that the general parameters of number in total students, total schools and budget stay the same (as expected). However, by finding the cheated scores through Thomas High, we see the adjusted scores drop. 
For instance, in the passing math column we see a decline from 74.98 to 74.76%; which in the context of distributing budgets, makes a difference for the school board. If the board asked for rounded figures, we would need see the differences in the two dataframes, but it is noteworthy to mention the overall passing percentage had a 1% difference. 

# 2. How is the school summary affected?
Image Old: 
Image New:
By looking at the two school summary photos, we see key differences in the data first display by Thomas High. 
Due to their dishonesty, we saw an inflation in their numbers, specifically in the passing math, reading, and overall percentages. 
Take for instance the adjusted vs original passing math %---Thomas High initially reported nearly 98% passing math, and in our adjusted outputs, we see only 69.91% passing this subject! 
The same holds true for the % passing reading column, and the overall percentage dropped by nearly 25 percentage points.

# 3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Image Old: 
Image New:
In the original ouput we see that Thomas High ranked at #2 overall, just behind Cabrera High. After our adjustements, we see that Thomas fell towards the middle of schools. 
The intent is quite clear---by increasing their percentage points in key categories, they were able to place their school in prime position for more funding. 

# 4. How does replacing the ninth-grade scores affect the following:
  A. Math and reading scores by grade
    Image Old: 
    Image New:
    We were able to remove the initial 83.6 math average and 83.7 reading average. Both figures contributed to an unclean and inaccurate dataset for the school district analysis. By removing and replacing as NaN, we restore the integrity of the data, and are able to move towards repeating our analysis. 
   
  B. Scores by school spending
    Image Old: 
    Image New:
    We did not see much of a spending impact (as we intially predicted). For instance, through our spending ranges, we initally thought to see Thomas High fall significantly, but it is placed in the $630-644 bin for scores by school spending. 
    
  C. Scores by school size
    Image Old: 
    Image New:
    Once again, we see little imact here---Thomas High is still considered a mid/medium sized school, even after dropping some of the scores as mentioned above. 
    
  D. Scores by school type
    Image Old: 
    Image New:
    Thomas High is still classified as a "Charter", and this figure would likely not be applicable according to the number of datapoints added/removed. 

# Summary
In general we see four major changes in the updated analysis: 
1. The passing rate for Thomas High (overall % passing) fell from 91 to 65%
2. Thomas High saw a steep decline in its math and reading averages, which explains the drop in passing percentages. 
3. By adding the Nan to the report, we have succsefully removed the corrupt datapoints. This can be found at the 9th grade level. 
4. Thomas High ranks #8 instead of its #2 false rank prior to the repeated analysis. 
