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
```
import matplotlib.pyplot as plt
x=[0,1,2,3,4,5]
y=[10,20,4,16,30,40]
plt.plot(x,y)
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH")
plt.show()
```
![435443196-e6f963c3-01c4-43b8-ad59-5b3356d20a2f](https://github.com/user-attachments/assets/73de93a9-7312-4b9e-a85b-8ceba6497cda)
```
x1=[1,2,3]
y1=[2,4,1]
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.plot(x1,y1,label="line 1")
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH")
plt.legend()
plt.show()
```
![435443224-533fcc25-0ab3-4d30-af97-3e7c360a041a](https://github.com/user-attachments/assets/b7a27372-22fd-4dcf-a423-4b8bf2565b7f)
```

x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color="red",linewidth=9,linestyle="dashed",marker='o',markerfacecolor='green',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH")
plt.show()
```
![435443251-66b748af-f252-446d-9f31-87143806d950](https://github.com/user-attachments/assets/ff8a2cd4-8bc2-4a41-b316-0ac600433815)

```
years = range(2000, 2012)
apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931, 0.934, 0.936, 0.937, 0.9375, 0.9372, 0.939]
oranges = [0.962, 0.941, 0.93, 0.923, 0.918, 0.908, 0.897, 0.894, 0.891, 0.886, 0.9, 0.896]

plt.plot(years, apples)
plt.plot(years, oranges)

plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples', 'Oranges'])
```
![435443268-ddefa414-6d01-43f6-abb2-4d26c6626460](https://github.com/user-attachments/assets/3cd3567e-d060-48fe-bf9d-a4a8b254395c)

```
yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(yield_apples)
```
![435443283-c030b27d-bbbb-4024-96f2-d9cb273851d8](https://github.com/user-attachments/assets/f66ce829-981c-477c-9a84-429e506d52b2)

```
years = [2010, 2011, 2012, 2013, 2014, 2015]
yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(years, yield_apples)
plt.xlabel('YEAR')
plt.ylabel('YIELD(tons per hectare)')
```
![435443305-6f3089ec-8e97-468d-9c39-d72e7b050031](https://github.com/user-attachments/assets/3c232fb3-0693-4d35-9ce8-bb2da67e6d92)
```

plt.figure(figsize=(10,6))
y=list(range(2000,2012))
plt.plot(y,oranges,marker='o')
plt.title("YIELD OF ORANGES(tons per hectare)")
```
![435443331-09400eae-1c69-4fe8-bf04-369e0f775bec](https://github.com/user-attachments/assets/f9b4bb63-207f-4075-ac5f-62537d034133)

```
plt.plot(y,oranges,marker='x')
plt.plot(y,apples,marker='o')
plt.xlabel("YEAR")
plt.ylabel("YIELD(tons per hectare)")
plt.title("YIELD OF ORANGES AND APPLES(tons per hectare)")
plt.legend(["oranges","apples"])
```
![435443355-98445f98-d9f3-4ae7-9b1a-5a0cf7da215f](https://github.com/user-attachments/assets/07622bd6-ba1a-42ea-8c97-c953854f230e)

```
x=[0,1,2,3,4,5]
y=[10,20,4,16,30,40]
plt.scatter(x,y,s=30,color="red")
plt.show()
```
![435443370-e7bb1233-036a-4250-b60c-3bb1ca389e27](https://github.com/user-attachments/assets/8f821316-20b8-4443-9af2-28fa7e2fd707)

```
x=[0,1,2,3,4,5]
y=[10,20,4,16,30,40]
plt.scatter(x,y,marker="*",color="blue")
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("SCATTER PLOT")
plt.legend()
plt.show()
```
![435443413-3e8db8c9-2ea9-4370-9c8f-2c6b9c22e62d](https://github.com/user-attachments/assets/27c052d5-7f43-41e0-9438-9d52b3f2b617)

```
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![435443429-4535e010-9150-461e-b838-26d70c9fc66b](https://github.com/user-attachments/assets/f670ae37-13cd-474a-be80-785a805ae5e4)
```
Y
```
![435443462-5bfcc40e-f79f-4bde-9d1a-1223840b3247](https://github.com/user-attachments/assets/03f1cef7-8259-4c73-8dd8-26af8e2ab2d4)

```
plt.scatter(x,y,c="r")
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH IN 2D")
plt.savefig("Test.png")
```
![435443483-edcb0655-c683-4689-b09d-068840ba440c](https://github.com/user-attachments/assets/9c2e6ddd-49bc-45b2-bedd-77ee65684503)

```
y=x*x
y
```
![435443501-01dcebdd-2422-40a8-a138-7fc57b63b416](https://github.com/user-attachments/assets/d257f4ef-42eb-4348-be6f-8a134d7a1925)
```

plt.plot(x,y,'g*',linestyle="dashed",linewidth=2,markersize=12)
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("2D GRAPH")
```
![435443520-4dd7f126-daa3-41a2-bac8-d4a699b2e4bc](https://github.com/user-attachments/assets/2bc725e7-6482-4011-a018-7d47c8be9099)

```
plt.subplot(2, 2, 1)
plt.plot(x, y, 'r--')

plt.subplot(2, 2, 2)
plt.plot(x, y, 'g*--')

plt.subplot(2, 2, 3)
plt.plot(x, y, 'bo')

plt.subplot(2, 2, 4)
plt.plot(x, y, 'go')
```
![435443532-322f105d-7558-4741-a7ad-0e780a4d99c8](https://github.com/user-attachments/assets/62e543d8-ce7c-4f49-b254-0a57e0601e9f)
```

x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x, y)
plt.show()

```
![435443549-0532cadd-fedd-4abd-ab01-7f2129dec995](https://github.com/user-attachments/assets/5c3e7da7-95f2-4470-8dc4-1022631d7e6c)

```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2=[5, 7, 9, 11, 13]
y3=[2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```

![435443576-d26085db-547e-4520-b3c7-8dd0e2452296](https://github.com/user-attachments/assets/c293f3b1-9d29-4407-8012-5e5f62b67d49)

```
plt.stackplot(x, y1, y2, y3, labels=['Line 1', 'Line 2', 'Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```

![435443590-6e4ca601-2c7d-4584-84a0-6d885b6e4138](https://github.com/user-attachments/assets/0644e41b-c1ab-43ac-8ad2-40515ca96b99)

```
from scipy.interpolate import make_interp_spline
x= np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])
y = np.array([2, 4, 5, 7, 8, 8, 9, 10, 11, 12])
spl = make_interp_spline(x, y)
x_smooth = np.linspace(x.min(), x.max(), 100)
y_smooth = spl(x_smooth)
plt.plot(x, y, 'o', label='data')
plt.plot(x_smooth, y_smooth, '-', label='spline')
plt.legend()
plt.title("SPLINE CHART")
plt.show()
```

![435443614-ecc696e9-1240-477b-95df-ed258fa945cf](https://github.com/user-attachments/assets/a89f3c32-0dce-4b3a-9c2b-5ff4c9721f5d)
```

val=[5,4,8,6,3]
names=["A","B","C","D","E"]
plt.bar(names,val,color="red")
plt.title("BAR GRAPH")
plt.show()
```
![435443634-0d1449e7-757d-47b6-8777-951046dcc6ec](https://github.com/user-attachments/assets/079548d1-c19a-49b0-8030-b55f9eeacdfb)
```

plt.barh(names,val,color="pink")
plt.title("BAR GRAPH(horizontal)")
plt.show()

```
![435443649-dfe2ac34-9cb2-42bf-b69e-e7ede87f1215](https://github.com/user-attachments/assets/f2e19c41-7588-4dbf-8e45-a8199c5b13ed)

```
height=[10,24,36,37,45]
names=['one','two','three','four','five']
c1=['red','blue']
c2=['b','g']
plt.bar(names,height,color=c1,width=0.8)
plt.xlabel("names")
plt.ylabel("height")
plt.title("BAR CHART")
plt.show()
```


![435443703-a5b7d71c-62d8-4e56-baa9-fe3d7affe05d](https://github.com/user-attachments/assets/c4f99a1d-cc62-4dab-83e5-4c81887c9d3b)

```
x=[2,8,10]
y=[11,16,9] 
x2=[3,9,11] 
y2=[6,15,7]
plt.bar(x, y,color='yellowgreen') 
plt.bar(x2, y2, color = 'purple')
plt.title("Bar graph")
plt.ylabel('Y axis')
plt.xlabel('x axis')
plt.show()
```
![435443726-38219006-1b9f-43aa-aae5-7c6bc6fc5258](https://github.com/user-attachments/assets/ff940247-9bd4-456d-9c73-84ba4fa14525)
```

ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0, 100)
bins=10
plt.hist(ages, bins, range, color='cyan', histtype='bar', rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('Histogram')
plt.show()
```
![435443745-431ea6bf-d3e2-4848-b797-2b9d4f51516b](https://github.com/user-attachments/assets/5e75eb62-3185-4b00-a995-d301adf2268a)

```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins=10, color='blue', alpha=0.5)
plt.show()
```
![435443767-99fefd74-333a-463a-ab6f-726ec7cecf15](https://github.com/user-attachments/assets/d64ded62-39d8-4dcc-9412-41e981468ae2)

```
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data

```
![435443814-03d8540f-60ae-468d-9ae0-f56e0e16f7b9](https://github.com/user-attachments/assets/b9e1604d-eb08-45c0-8e68-0c9bd5ffa1a6)
```

fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_title("BOX PLOT")
ax.set_ylabel("Y-AXIS")
ax.set_xlabel("X-AXIS")
```
![435443840-765b76af-0126-460c-b2fa-64c3e8b44570](https://github.com/user-attachments/assets/eeed3060-8c1b-42c6-afac-2f931b0b1a3e)

```
activities = ['eat', 'sleep', 'work', 'play']
slices=[3, 7, 8, 6]
colors = ['r', 'y', 'g', 'b']
plt.pie(slices,labels=activities,colors=colors,startangle=90, 
        shadow=True,explode=(0,0,0.1,0), radius=1.2, autopct='%1.1f%%')
plt.legend ()
plt.show()

```

![435443855-b56e792a-957c-44bb-b4df-b2648ea9f30a](https://github.com/user-attachments/assets/57d52a59-9a08-43e5-983a-1fab84b2667f)
```

labels=['Python','C++','Ruby','Java']
sizes=[215, 130, 245, 210] 
colors=['gold', 'yellowgreen', 'lightcoral', 'lightskyblue'] 
explode=(0,0.4,0,0.5)
plt.pie(sizes, explode=explode, labels=labels, colors=colors, autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```

![435443883-64d715a0-e308-4fc7-8ef3-b08e1a1c9bf8](https://github.com/user-attachments/assets/3b9a2b74-c7cf-4729-84a1-04fa9592b171)

# Result:
Data visualization using matplot library is verified

