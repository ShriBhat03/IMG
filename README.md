# IMAGE
1)Develop a pgm to display the grayscale image using read and write operation<br>
#plant<br>
import cv2<br>
img=cv2.imread('plant.jpg',0)<br>
cv2.imshow('image',img)<br>
cv2.waitKey(0)<br>
cv2.destroyAllWindows()<br>
O/P:<br>
![plant op](https://user-images.githubusercontent.com/98145090/173802776-7d1f3cc5-c2c7-485a-9b73-d2ae1939426f.png)<br>
#Flower<br>
import cv2<br>
img=cv2.imread('flower.jpg',0)<br>
cv2.imshow('image',img)<br>
cv2.waitKey(0)<br>
cv2.destroyAllWindows()<br>
O/P:<br>
 ![image](https://user-images.githubusercontent.com/98145090/173801925-79c87582-01ed-4e10-a6ce-4e44c593381c.png)<br>
 #butterfly<br>
import cv2<br>
img=cv2.imread('butterfly.jpg',0)<br>
cv2.imshow('image',img)<br>
cv2.waitKey(0)<br>
cv2.destroyAllWindows()<br>
O/P:<br>
![image](https://user-images.githubusercontent.com/98145090/173802198-9c4a43d4-2b97-49c5-bd83-f9fe6801ab43.png)<br>
 #leaf<br>
import cv2<br>
img=cv2.imread('leaf.jpg',0)<br>
cv2.imshow('image',img)<br>
cv2.waitKey(0)<br>
cv2.destroyAllWindows()<br>
O/P:<br>
![image](https://user-images.githubusercontent.com/98145090/173802421-a87d2e49-0f2b-4375-8c86-3029462dd7a8.png)<br>
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
2)Develop a pgm to display image using matplotlib<br>
import matplotlib.image as mping<br>
import matplotlib.pyplot as plt<br>
img=mping.imread('leaf.jpg')<br>
plt.imshow(img)<br>
![image](https://user-images.githubusercontent.com/98145090/173804024-27d31380-8335-4e12-a2b8-9c1cc5bf8ae9.png)<br>
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
3)Develop a pgm to perform liner transformation rotation<br>
from PIL import Image<br>
img=Image.open("leaf.jpg")<br>
img=img.rotate(180)<br>
img.show()<br>
cv2.WaitKey(0)<br>
cv2.destroyAllWndows()<br>
Output:<br>
 ![image](https://user-images.githubusercontent.com/98145090/173805940-de5be5ca-afb4-4154-97fd-0033a2ce123e.png)<br>
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
5)Develop a pgm to convert color string to RGB color Values<br>
from PIL import ImageColor<br>
img=Image.new('RGB',(200,400),(255,255,0))<br>
img.show()<br>
Output:<br>
![image](https://user-images.githubusercontent.com/98145090/173814822-4902a90a-0522-47b2-8938-0e6e344e5352.png)<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
4)Write a pgm to create image using colors<br>
from PIL import ImageColor<br>
img1=ImageColor.getrgb("yellow")<br>
print(img1)<br>
img2=ImageColor.getrgb("red")<br>
print(img2)<br>
Output:<br>
![image](https://user-images.githubusercontent.com/98145090/173812856-38cce19b-dd95-4a17-8007-67e5a3e67251.png)<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
6)Develop a pgm to create image using various colors spaces<br>
import cv2<br>
import matplotlib.pyplot as plt<br>
import numpy as np<br>
img=cv2.imread('leaf.jpg')<br>
plt.imshow(img)<br>
plt.show()<br>
img=cv2.cvtColor(img,cv2.COLOR_BGR2RGB)<br>
plt.imshow(img)<br>
plt.show()<br>
img=cv2.cvtColor(img,cv2.COLOR_RGB2HSV)<br>
plt.imshow(img)<br>
plt.show()<br>
image.close()<br>
Output:<br>
![6 leaf](https://user-images.githubusercontent.com/98145090/173813575-bb08cb6a-a370-44f1-adb7-2b81cc6d58fe.png)<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
7)Write a pgm to display the image attribute<br>
from PIL import Image<br>
image=Image.open('leaf.jpg')<br>
print("filename:", image.filename)<br>
print("Format:",image.format)<br>
print("Mode:",image.mode)<br>
print("size:",image.size)<br>
print("width",image.width)<br>
print("height",image.height)
image.close()<br>
Output:<br>
![7 leaf](https://user-images.githubusercontent.com/98145090/173809660-e3cfc405-3486-44d5-a9fa-ea7440316743.png)<br>

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
8)<br>

Output:<br>
<br>
