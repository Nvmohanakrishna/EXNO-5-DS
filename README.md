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

# Coding:
```
import matplotlib.pyplot as plt
%matplotlib inline
import numpy as np

x=np.arange(10,20)
y=np.arange(11,21)
a=np.arange(40,50)
b=np.arange(50,60)

plt.scatter(x,y,c='g')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
y=x*x

plt.plot(x,y,'r*',linestyle='dashed',linewidth=2, markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
plt.show()

plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
plt.show()

x = np.arange(1,11)
y = 3 * x + 5
plt.title("Matplotlib demo")
plt.xlabel("x axis ")
plt.ylabel("y axis ")
plt.plot(x,y)
plt.show()

np.pi
3.141592653589793
# Compute the x and y coordinates for points on a sine curve
x = np.arange(1, 10 * np.pi, 0.2)
y = np.sin(x)
plt.title("sine wave form")
# Plot the points using matplotlib
plt.plot(x, y)
plt.show()
x = np.arange(1, 10 * np.pi, 0.2)
y_sin = np.sin(x)
y_cos = np.cos(x)
plt.subplot(2, 1, 1)

plt.plot(x, y_sin,'r--')
plt.title('Sine')

plt.subplot(2, 1, 2)
plt.plot(x, y_cos,'g--')
plt.title('Cosine')

plt.show()

x = [5,10,15]
y = [20,25,30]
x2 = [35,40,45]
y2 = [50,55,60]
plt.bar(x, y)
plt.bar(x2, y2, color = 'g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()

a = np.array([10,20,30,40,50,60,70,80,90,70,35,6,2,])
plt.hist(a)
plt.title("histogram")
plt.show()

data = [np.random.normal(0, std, 100) for std in range(2, 5)]

plt.boxplot(data,vert=True,patch_artist=False);
plt.show()

data = [np.random.normal(0, std, 100) for std in range(2, 5)]

plt.boxplot(data,vert=True,patch_artist=True);
plt.show()
 data
```
# Result:
<img width="669" height="433" alt="image" src="https://github.com/user-attachments/assets/85c4a0c9-af25-41bd-ac10-5f71adc6ad77" />

<img width="563" height="424" alt="image" src="https://github.com/user-attachments/assets/0aa06a8e-00e5-46de-a7b8-dc5dd3167014" />

<img width="609" height="389" alt="image" src="https://github.com/user-attachments/assets/adc5062d-ebef-4579-afdd-9771103543ff" />
