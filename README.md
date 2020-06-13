# Numpy used To create multi dimensional arrays
# Adding two arrays using for loop
from numpy import*
arr1=array([1,2,3,4])
arr2=array([5,6,7,8])
sum_array=[]
for i in range(len(arr1)):
    sum_array.append(arr1[i]+arr2[i])
print(sum_array)

