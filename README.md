# READ AND WRITE AN IMAGE
## AIM
To write a python program using OpenCV to do the following image manipulations.
i) Read, display, and write an image.
ii) Access the rows and columns in an image.
iii) Cut and paste a small portion of the image.

## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
Choose an image and save it as a filename.jpg
### Step2:
Use imread(filename, flags) to read the file.
### Step3:
Use imshow(window_name, image) to display the image.
### Step4:
Use imwrite(filename, image) to write the image.
### Step5:
End the program and close the output image windows.
## Program:
### Developed By lisha
### Register Number: 212220230028
i) #To Read,display the image

image=cv2.imread("1.jpeg")
cv2.imshow("image",image)

ii) #To write the image

cv2.imwrite("image2.jpeg",image)

iii) #Find the shape of the Image

print(image.shape)

iv) #To access rows and columns

for i in range(70,90):
  for j in range(110,170):
   image[i][j]=[0,0,0]
   
v) #To cut and paste portion of image

image[2000:2700,2000:2700]=image[1000:1700,1000:1700]

## Output:

### i) Read and display the image

![image](https://user-images.githubusercontent.com/75237886/161375369-a5cf9b32-9382-449b-937f-2c0ba8b40f44.png)


### ii)Write the image

![image](https://user-images.githubusercontent.com/75237886/161375415-581db536-27a3-4327-9f60-cb7637048f8e.png)


### iii)Shape of the Image

![image](https://user-images.githubusercontent.com/75237886/161375444-40ef52ea-3cd0-44e5-9a47-a7ee415e655f.png)


### iv)Access rows and columns
![image](https://user-images.githubusercontent.com/75237886/161375523-08064d6c-95e8-4416-b171-c9dffc59d9a5.png)


### v)Cut and paste portion of image
![image](https://user-images.githubusercontent.com/75237886/161375773-b9c2bb7b-d207-447d-aecb-9ab68e59d000.png)



## Result:
Thus the images are read, displayed, and written successfully using the python program.


