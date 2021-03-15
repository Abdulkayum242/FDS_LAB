# -*- coding: utf-8 -*-
"""
Created on Sun Mar 14 16:43:00 2021

@author: onero
"""

import numpy as np 
import pandas as pd
import seaborn as sns 
import matplotlib.pyplot as plt
import random
import statsmodels.api as sm 
import pylab as py 

df=sns.load_dataset("iris")
df

avg=df["sepal_length"].mean()
mean=round(avg,2)
mean
std=df["sepal_length"].std()
sd=round(std,2)
sd
data=df["sepal_length"].apply(lambda x: x-mean/sd)
data
sns.kdeplot(data, shade=True)

## QQ plot
sm.qqplot(data,line="45") 
py.show() 



## example 2
df1=np.random.normal(2,5,100)
df1
mean1=4
sd1=6
sample=[]
for i in df1:
    a=(i-mean1)/sd1
    print(a)
    sample.append(a)
    
sample
sns.kdeplot(sample, shade=True)

## QQ plot
sm.qqplot(df1,line="45")
py.show()


## example 3

df2=np.random.normal(0,1,100)
df2
mean2=0
sd2=1
samp1=[]
for i in df2:
    a=(i-mean2)/sd2
    print(a)
    samp1.append(a)
    
samp1
sns.kdeplot(samp1, shade=True)

## QQ plot
sm.qqplot(df2,line="45")
py.show()


## example 4 
df3=np.random.normal(1,3,100)
df3
mean3=1
sd3=3
samp2=[]
for i in df3:
    a=(i-mean3)/sd3
    print(a)
    samp2.append(a)
    
samp2
sns.kdeplot(samp2, shade=True)

## QQ plot
sm.qqplot(df3,line="45")
py.show()



## example 5
df4=np.random.normal(2,1,100)
df4
mean4=2
sd4=1
samp3=[]
for i in df4:
    a=(i-mean4)/sd4
    print(a)
    samp3.append(a)
    
samp3
sns.kdeplot(samp3, shade=True)

## QQ plot
sm.qqplot(df4,line="45")
py.show()



