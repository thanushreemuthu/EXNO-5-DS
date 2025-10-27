# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
 import pandas as pd
 import numpy as np
 import seaborn as sns
 import matplotlib.pyplot as plt

 marks=[13,45,63,78]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(marks,student)
 plt.xlabel('Marks')
 plt.ylabel('Student name')
 plt.show()
 
 student=['A','B','C','D']
 attendence=[90,85,73,88]
 plt.plot(attendence,student)
 plt.xlabel('Attendence')
 plt.ylabel('Student name')
 plt.show()

 <img width="797" height="595" alt="image" src="https://github.com/user-attachments/assets/89396bfa-2d35-4b7b-8374-4e3f83630f8e" />

<img width="762" height="607" alt="image" src="https://github.com/user-attachments/assets/1b7b5b0e-c865-4372-94f7-0e8245d76f4d" />

 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
 
 x=np.arange(0,15)
 y=np.arange(0,15)
 x
 y
 plt.scatter(x,y,c='r')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()

 <img width="767" height="580" alt="image" src="https://github.com/user-attachments/assets/52f8e693-410d-47b8-b887-0a0a6dc18325" />

 <img width="770" height="635" alt="image" src="https://github.com/user-attachments/assets/cd9756b8-0780-4da6-bd54-e0a35e291d71" />

 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
 
 feedback=['Good','excellent','Perfect','Ok']
 slices=[4,10,3,8]
 color=['y','r','b','g']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()

<img width="629" height="576" alt="image" src="https://github.com/user-attachments/assets/a46f5785-753a-4bde-891d-6d7b2cc94086" />

<img width="605" height="561" alt="image" src="https://github.com/user-attachments/assets/81da61c0-a06e-48eb-80d9-dc4ce042e6a2" />

 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]

 plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()

 <img width="769" height="574" alt="image" src="https://github.com/user-attachments/assets/c1e84017-5f17-4ead-a7f1-08f017edb93e" />

 height = [10, 24, 36, 40, 5]
 names = ['one', 'two', 'three', 'four', 'five']
 c1=['red', 'green'] 
c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart!')
 plt.show()

 <img width="775" height="627" alt="image" src="https://github.com/user-attachments/assets/973e8a06-3db9-48c5-a8ac-8909426e28f7" />

 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()

<img width="740" height="566" alt="image" src="https://github.com/user-attachments/assets/b8c973eb-3f15-4844-a7ab-d1bfb8a6eae1" />

 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data

<img width="760" height="489" alt="image" src="https://github.com/user-attachments/assets/326ec6b7-ad8f-4938-b880-24b910e03589" />

 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')

 <img width="784" height="678" alt="image" src="https://github.com/user-attachments/assets/86710794-1c57-45c8-a0cf-dc4eabbae56d" />

# Result:
Data Visualization using matplot python library for the given datas is performed successfully.

