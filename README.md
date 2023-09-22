# PythonStats
## Statistics Basics With Python   
-------------------------------------------------------------------------------------------------
For this tutorial I have used Global Youtube statistics data from Kaggle, You can download it via this link: https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023

Or you can also find the .csv in this repository along with the complete codes, this .py file contains instrustions of all codes with # and markdown cells, Good luck! Happy learning.

Here is a quick review of the basic concepts:     

***************************************************************************************************
## Measures of central Tendencies:
Mean   = sum of all values/ number of all values   
Median = middle value 
Mode   = most frequent value  

When to use mean?   
When the distribution is symmetrical and there are no outliers.   

When to use median?   
When the distribution is skewed and there are outliers.    

When to use mode?   
When working with categorical data, for instance which category occurs most frequently.   


-------------------------------------------------------------------------------------------------
## Normal distribution:    

1. Symmetrical about it's mean,    
2. Mean = Median = Mode    
3. Tails of curve never touch axis    
4. Most of the data around center    

3 sigma rule for values in a normal distribution     
68% +- 1SD , 68 Percent of the data is distributed plus minus 1 SD about mean  
95%  +- 2SD, 95 percent of the data is distributed plus minus 2 SD about mean  
99.7% +- 3SD  99.7 percent of the data is distributed plus minus 3 SD about mean  
SD(standard deviation)     

![WhatsApp Image 2023-09-22 at 16 39 51](https://github.com/huddaluni/PythonStats/assets/117635800/0a3a3cb4-f12e-48df-b2cd-7ecbb5705a32)     



## Skewed Distribution:   

1. Asymmetric Skewed away from center either left or right(positively or negatively)   
2. Mean ≠ Median ≠ Mode   
3. Values clustered around high or low ends of x-axis

![WhatsApp Image 2023-09-22 at 16 39 50 (1)](https://github.com/huddaluni/PythonStats/assets/117635800/39c16753-16b7-4c4f-8ae3-148f37b24e5a)    




## Kurtosis:

A descriptor of shape and it describes the shape of the distribution, there are three types of shapes defined by kurtosis
1. Leptokurtic: pointed   
2. Mesokurtic: normal   
3. Platykurtic: flattened


![WhatsApp Image 2023-09-22 at 16 39 50](https://github.com/huddaluni/PythonStats/assets/117635800/985e40cd-c5f2-451f-8495-a496d00a6213)    





-------------------------------------------------------------------------------------------------  

# Measures of Position 
A way to see where a value(data point) falls within a sample distribution

## Common measures of position:
Box and Whiskers plot
Deciles
Inter quartile range
Outliers
Percentiles
Quartiles
Standard Scores

### Box and Whiskers plot:
The 5 number summary  

1. Min     
(left whisker)   
|    
*----------------------   
 2. Q1(lower quartile)    
|    
3. Median   
|    
4. Q3(upper quartile)    
*-----------------------   
|    
(Right whisker)    
5. Max





![WhatsApp Image 2023-09-22 at 16 39 49 (1)](https://github.com/huddaluni/PythonStats/assets/117635800/0475d342-3b74-4c0f-bd4f-e2dabd7ac015)





![WhatsApp Image 2023-09-22 at 16 39 49](https://github.com/huddaluni/PythonStats/assets/117635800/0e23021c-0ee9-4e6a-a414-972e60ab49d0)   






### Inter quartile range   
IQR= Q3 - Q1     
Shows where 50 percent of distribution values are   

### Deciles:    
Splits the data in to tenths    
   
### Quartiles:   
Splits data into 4 quarters, lowest two middle and highest     
    
### Percentiles:    
Where the certain percentage of scores fall below that number   
    
### Standard Scores: 
zscore   


-------------------------------------------------------------------------------------------------

## Z scores:    
Defines a value within a distribution relative to the spread of distribution and compares 2 values   

If I score 85/100 in math n class average is 75   
then a +2 z score can tells I did better than rest of the class,   
If classmate got 65 it could be -2 z score   



![WhatsApp Image 2023-09-22 at 16 39 48](https://github.com/huddaluni/PythonStats/assets/117635800/60e14e23-ced9-437c-a757-5e4d25160840)   






### Facts about Z scores:   
Standardization   
Transforms data to mean = 0 and SD = 1, making easier to compare different data sets   

Interpretation   
+z value above mean   
-z value below mean   
Value of z tells how far or near the value is from mean   


-------------------------------------------------------------------------------------------------


