# Statistics Concepts
 __Descriptive statistics__
- It is a branch of statistics that deals with summarizing, organizing, and presenting data in a meaningful and informative way.
- Its primary goal is to describe and understand the main features of a dataset without making any inferences or generalizations to a larger population.
- Descriptive statistics is often the first step in data analysis and is crucial for gaining insights into the underlying patterns, trends, and characteristics of the data.
- Descriptive statistics are brief informational coefficients that summarize a given data set, which can be either a representation of the entire population or a sample of a population
- Descriptive statistics consists of three basic categories of measures:
  1) __measures of central tendency__ :These measures provide information about the center or typical value of a dataset.
      - Mean: The arithmetic average of all data points in the dataset.
      - Median: The middle value in a sorted dataset, separating the higher and lower values.
      - Mode: The value that appears most frequently in the dataset.
  2) __measures of variability (or spread)__ :These measures indicate the spread or variability of data points around the central tendency. 
      - Variance: A measure of how much the values in the dataset differ from the mean.
      - Standard Deviation: The square root of the variance, which provides a more interpretable measure of dispersion.
  3)  __frequency distribution(table).__ :These tables show the number of occurrences of different values or categories in the dataset.
- Let take one example  to understand in better way :
  
  | Attempt | marks |
  | :---: | :---: |
  |  1    | 65|
  |  2    | 60|
  |  3    | 50|
  |  4    | 55|
  |  5    | 80|
  |  6    | 60|
  |  7    | 75|
  |  8    | 60|

  __1)mean =__  (sum of all Values)/ (total number of Values)  = 65+60+50+55+80+60+75+60 / 8 = __63.12__
  
  __2)Median =__ (sort  all number and  find the middle value) =  i.e __60__
  
  __3)Mode =__ (find most frequently occurring value )= i.e __60__
  
  __4)Variance :__ (find the mean first, then compute the squared difference between each score and the mean) i.e
               [(65 - 63.125)^2 + (60 - 63.125)^2 + ... + (60 - 63.125)^2] / 8   = (3.765625 + 9.515625 + ... + 9.515625) / 8 == 53.828125 / 8
                __≈ 6.728515625__
  
  __5)Standard Deviation:__ The standard deviation is the square root of the variance. =√(6.728515625) __≈2.595__
Quartiles divide a dataset into four parts: 

__Percentile:__
  - It is value below which a certain percentage observation lie.
  - percentiles divide data into 100 equal parts.
    
__Quartiles:__
  - Quartiles are the set of values that divide the data points into four identical values using three individual data points.
  - Q1 = 25th Percentile
  - Q2 = 50th Percentile or Median
  - Q3 = 75th Percentile
  

__What is outliers?__
- Outliers are an observation of data that does not fit into  the rest of the data.
- Are extreme values that differ from most other data points in a dataset.

__Way to find outlier in data__
 1) Using Z-scores
 2) Using the Interquartile Range to Create Outlier Fences

__1)Using Z-scores__
- Z score = (x -mean) / std. deviation
    
__2)Using the Interquartile Range(IQR)__
- IQR is used to measure variability by dividing a data set into quartiles
- Steps to find out IQR
   - Q1 represents the 25th percentile of the data.
   - Q3 represents the 75th percentile of the data.
   - The difference between Q3 and Q1 is called the Inter-Quartile Range or IQR.
   - Lower Bound: (Q1 - 1.5 * IQR)
   - Upper Bound: (Q3 + 1.5 * IQR)
           
                    


