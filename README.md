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
   
  B. Scores by school spending
    Image Old: 
    Image New:
    
  C. Scores by school size
    Image Old: 
    Image New:
    
  D. Scores by school type
    Image Old: 
    Image New:

# Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
