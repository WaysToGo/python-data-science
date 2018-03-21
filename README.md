# python-data-science

## NumPy
what is numpy
- Numeric Python
- Alternative to Python List: NumPy Array 
- Calculations over entire arrays 


how to use?

```python

import numpy as np 
arr=[1,2,3,4]
np_arr=np.array(arr) # to convert in to numpy array where we can perform calculations over entire array
arr>2 #returns array([False,False,True,True])
arr[arr>2] #returns array([3,4])
#adding one string value to array changes whole array to string datatype 
#selecting and slicing syntax is similar to array 
```

---

## Matplotlib

- used for data analysis
- explore data
- report insights

 how to use?

```python
import matplotlib.pyplot as plt
year=[1960,1970,1980]
population=[2,3,4]
plt.plot(year,population) #year is x and population is on y axis
#this wont plot the data until we use show()
#plot will conntect all the points in graph 
plt.scatter(year,population)#plots only dots on the graph 
plt.show()

plt.hist(population,bins=3)#represents histogram based on the values and divides according to bins

#different customizations can be done like color plot type etc
plt.xlabel('year')#adds x label as year 
plt.title('world population') # adds title
plt.yticks([0,2],[0,2B])#first one is mumeric to plot  and second is label for representation 

#color is changed accordingly by passing it as a argument to the scatter or plot etc.
```
---

## pandas

- Pandas is an open source library
- providing high-performance, easy-to-use data structures 
- data analysis tools for Python

DataFrame

- DataFrame is one of Pandas' most important data structures
- a way to store tabular data
- One way to build a DataFrame is from a dictionary
