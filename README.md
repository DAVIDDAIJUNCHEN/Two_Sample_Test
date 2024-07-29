# Two_Sample_Test
This repo is created to archive experiment data for two sampling test on ASR model performance comparision. 

## 
There are four ASR models tested on two types of test sets. The first type of ASR test sets are regression test sets, which are collected for general purposes and has 46 test sets.
The second type of ASR test sets are about Car related domains, which contains 23 test sets. Among the four ASR models, one is conventional hybrid ASR model, three of them are End2End ASR models. 

In Table 1 and 2, we present the WERs on the 46 regression and 23 car domain test sets respectively. In those tests, if we test by launching 50 parallel jobs for each test set and $RTF=0.5$, then 
it takes around 390 mins machine time to finish the regression test sets with one ASR model. Similarly, it takes 35 mins to finish the car domain test sets with one ASR model.


