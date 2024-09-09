# ECE2112_PA2
John Felipe M. Domingo

This is an introductory assignment to help students understand the basics of Python.
Done by an undergraduate student of Electronics Engineering at the University of Santo Tomas.
Section: 2ECE-A

This assignment deals with the use of numpy, a Python library that focuses on arrays and matrices. 
Including an assortment of routines for fast operations on arrays, including mathematical, 
logical, shape manipulation, sorting, selecting I/O, statistical operations and much more.

Problem code:

A. Normalization Problem
   For this problem, we are tasked with making a code that uses normalization to organize data.
   Normalization is the process of organizing data in a database and it is one of the most basic
   preprocessing techniques in data analytics.
   The students are supposed to utilize the functions std and mean in numpy to recreate the formula
   for normalization.

   My problem code features two codes, one utilizing the main std and mean functions of numpy and
   utilizing minimum and maximum values. While both are normalization techniques, their outputs
   and uses are are different. 
   1. Using std and mean (Main code for the assignment)
      For Z-score normalization, the standardized data can have positive and negative values.
      The resulting values represent how many standard deviations away a particular data point is from the mean.
      
      ![image](https://github.com/user-attachments/assets/6749cea2-bf8d-4fc1-a8ee-543808e25bc6)

   3. Using X_min and X_max (Additional Code)
      For min-max scaling, the values are fixed from 0 to 1 and this is useful when you are limiting data values
      from zero to one.
      
      ![image](https://github.com/user-attachments/assets/a9d61577-ed9f-4b11-85ca-f8ffcd921c5c)
  
   
B. Divisible by 3 problem
   For this problem, we are tasked with creating a 10x10 array that features values from 1 to 100.
   Then squaring the first 100 terms using "n ** 2" and lastly checks the elements that are 
   divisible by 3.

   For this problem I utilized the np.arrange, "n ** 2", and the modulo operator "%" to solve the 
   problem. I also organized the created array using numpy's .reshape function.
   
   ![image](https://github.com/user-attachments/assets/4961bccc-ab07-4092-84d1-0f16d300e2a4)




