# BigData-Ex1
First exercise in Big Data course

**Exercise 1:**
-----------------------------------------------------------

**Q1. How many files are there now?** 6

**Q2. Did number of mapper change?** No

**Q3. Did number of reducer changed?** Yes

**Q4. Did number of output files change? Why?** Yes, because the number of output files is according to the nuber of reducer. At first we had: Launched reduce tasks=3, and than we had: Launched reduce tasks=6.

**Q5. What does the value of 'Merged Map outputs' represents and how is it calculated?** Merged Map outputs is the number of map-output files that needed to be merged. In another words, it's the number of intermediate map-output files that were sent to each reducer and had to be merged during the shuffle and sort phase. As we see this number is = map tasks x reduce tasks.


**Exercise 2**
-----------------------------------------------------------

**Q1. Is your change in the mapper or in the reducer?**  In the mapper

**Q2. Please submit your code in GitHub** Added as mapper.py

**Exercise 3**
------------------------------------------------------------------
**Q1. Is your change in the mapper or in the reducer?** In the reducer

**Q2. Please submit your code in GitHub** Added as reducer.py

**Q3. Print the output of the MapReduce and add to the project.** <img width="464" height="53" alt="image" src="https://github.com/user-attachments/assets/927669f5-ab00-4389-8611-fd0a319df8f4" />
