# stock-analysis


## Overview of Project
Here in this project, I determined the stock performance between 2017 and 2018 from  [stock-analysis](VBA_Challenge.xlsm) data to help Steve to know the stock performance . To do data analysis  manually and use Excel formulas for calculations is tidius. But with Visual Basic for Applications, which is typically referred to as "VBA," we can write code that will automate these analyses for us. Often used in the finance industry, VBA provides essentially infinite extensibility to Excel. Using code to automate tasks decreases the chance of errors and reduces the time needed to run analyses, especially if they need to be done repeatedly.

### Purpose of Analysis
Refactor the code to loop through all the data one time in order to collect the same information to determine whether refactoring code successfully made the VBA script run faster.Here I try to  make the code more efficient—by taking fewer steps, using less memory, or improving the logic of the code to make it easier for future users to read. and finally take less time to run.

## Analysis and Challenges

### Analysis of Date



### Challenges and Difficulties Encountered


## Results

### Comparison between stock performance in 2017 & 2018

From the analysis using VBA we got the stock performance for 2017 as follows:

![Output_2017](https://github.com/NishatSultana3538/stock-analysis/blob/main/Images/Output_2017.png)

And for 2018 as follows:

![Output_2018](https://github.com/NishatSultana3538/stock-analysis/blob/main/Images/Output_2018.png)


1. From the above output we can clearly see that overall stock performance was better in 2017 compared to 2018 as almost all the stock gives higher return in 2017.
2. Only stock that gives higher return in 2018 is "RUN".
### Comparison between execution times of the original script and the refactored script

Below are the runtime for 2017 and 2018 with the code where it calculates data for 2017 and 2018 separately:
![Previous_Image_2017](https://github.com/NishatSultana3538/stock-analysis/blob/main/Supporting%20Data/Previous_Runtime_2017.png)
![Previous_Image_2018](https://github.com/NishatSultana3538/stock-analysis/blob/main/Supporting%20Data/previous_Runtime_2018.png)
 
Below are the runtime for 2017 and 2018 with refactored code:
![Image_2017](https://github.com/NishatSultana3538/stock-analysis/blob/main/Resources/VBA-Challenge_2017.png)
![Image_2018](https://github.com/NishatSultana3538/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)

1. Comparing the runtime with refractored and original code shows that refactored code runs faster in both for year 2017 and 2018.
2. Creating arrays, using tickerIndex to loop through, and reusing code for years(in different sheets)
make the code more efficient and run faster.

##  Summary: 
### Advantages of refactoring code-
### Disadvantages of refactoring code-
### How do these pros and cons apply to refactoring the original VBA script?
