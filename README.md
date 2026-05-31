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
```py
import matplotlib.pyplot as plt
import numpy as np 
x=np.arange(10,20)
y=np.arange(21,31)
a=np.arange(45,55)
b=np.arange(55,65)
plt.scatter(x,y,c='g')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')

y=x*x
plt.plot(x,y,'r*',linestyle='solid',linewidth=3, markersize=10)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
plt.show()

plt.subplot(3,3,1)
plt.plot(x,y,'r--')
plt.subplot(3,3,2)
plt.plot(x,y,'g*--')
plt.subplot(3,3,3)
plt.plot(x,y,'bo')
plt.subplot(3,3,4)
plt.plot(a,b,'go')
plt.show()

x = np.arange(0,10) 
y = 3 * x + 5 
plt.title("Matplotlib demo") 
plt.xlabel("x axis caption") 
plt.ylabel("y axis caption") 
plt.plot(x,y) 
plt.show()

np.pi
x = np.arange(0, 4 * np.pi, 0.1) 
y = np.sin(x) 
plt.title("cosine wave form") 

# Plot the points using matplotlib 
plt.plot(x, y) 
plt.show()

x = np.arange(0, 5 * np.pi, 0.1) 
y_sin = np.sin(x) 
y_cos = np.cos(x)  
  
# Set up a subplot grid that has height 2 and width 1, 
# and set the first such subplot as active. 
plt.subplot(2, 1, 1)
  
# Make the first plot 
plt.plot(x, y_sin,'r--') 
plt.title('Sine')  
  
# Set the second subplot as active, and make the second plot. 
plt.subplot(2, 1, 2) 
plt.plot(x, y_cos,'g--') 
plt.title('Cosine')  
  
# Show the figure. 
plt.show()

x = [2,4,6] 
y = [4,8,10]  

x2 = [1,3,5] 
y2 = [2,6,8] 
plt.bar(x, y) 
plt.bar(x2, y2, color = 'g') 
plt.title('Bar graph') 
plt.ylabel('Y axis') 
plt.xlabel('X axis')  

plt.show()

a = np.array([22,87,5,43,56,73,55,54,11,20,51,5,79,31,27]) 
plt.hist(a) 
plt.title("histogram") 
plt.show()

data = [np.random.normal(0, std, 100) for std in range(1, 4)]

# rectangular box plot
plt.boxplot(data,vert=True,patch_artist=False);  
plt.show()

data = [np.random.normal(0, std, 100) for std in range(1, 6)]

# rectangular box plot
plt.boxplot(data,vert=True,patch_artist=True);
plt.show()

data

labels = 'Python', 'C++', 'Ruby', 'Java'
sizes = [200, 130, 245, 210]
colors = ['red', 'cyan', 'yellow', 'lightskyblue']
explode = (0.4, 0, 0, 0)  # explode 1st slice

# Plot
plt.pie(sizes, explode=explode, labels=labels, colors=colors,
autopct='%1.1f%%', shadow=False)

plt.axis('equal')
plt.show()
```
<img width="750" height="597" alt="image" src="https://github.com/user-attachments/assets/cc8ce1c7-0c38-4e5f-b4f0-66c2b6614b6c" />
<img width="744" height="362" alt="image" src="https://github.com/user-attachments/assets/aa2e4d66-abf2-492b-b04b-0abf4f4e34c8" />
<img width="776" height="611" alt="image" src="https://github.com/user-attachments/assets/da42fe09-1e3e-4c80-8e91-9cbfd9a6ed09" />
<img width="782" height="593" alt="image" src="https://github.com/user-attachments/assets/a9683011-ba74-44e3-a5e8-7d26c1369387" />
<img width="796" height="656" alt="image" src="https://github.com/user-attachments/assets/6c2f2997-358a-411c-a09f-e11dc9eaaf9e" />
<img width="807" height="631" alt="image" src="https://github.com/user-attachments/assets/0e7323c3-a3ab-4095-b21e-3f30380aee9d" />
<img width="801" height="613" alt="image" src="https://github.com/user-attachments/assets/34bf176d-506a-453c-8613-644401b5eef3" />
<img width="787" height="561" alt="image" src="https://github.com/user-attachments/assets/5b24c4fb-6c91-4a10-8f3a-29b4959625ea" />
<img width="756" height="556" alt="image" src="https://github.com/user-attachments/assets/fb237455-1425-453a-9c71-a09841af6f9d" />

# Result:
 Include your result here
