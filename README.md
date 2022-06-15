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
2)Develop a pgm to display image using matplotlib<br>
import matplotlib.image as mping<br>
import matplotlib.pyplot as plt<br>
img=mping.imread('leaf.jpg')<br>
plt.imshow(img)<br>
![image](https://user-images.githubusercontent.com/98145090/173804024-27d31380-8335-4e12-a2b8-9c1cc5bf8ae9.png)<br>
3)Develop a pgm to perform liner transformation rotation<br>
from PIL import Image<br>
img=Image.open("leaf.jpg")<br>
img=img.rotate(180)<br>
img.show()<br>
cv2.WaitKey(0)<br>
cv2.destroyAllWndows()<br>
Output:<br>
 ![image](https://user-images.githubusercontent.com/98145090/173805940-de5be5ca-afb4-4154-97fd-0033a2ce123e.png)<br>
4)Develop a pgm to convert color string to RGB color Values

Output:<br>
5)
