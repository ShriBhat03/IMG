# IMAGE
# 1)Develop a pgm to display the grayscale image using read and write operation<br>
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
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 2)Develop a pgm to display image using matplotlib<br>
import matplotlib.image as mping<br>
import matplotlib.pyplot as plt<br>
img=mping.imread('leaf.jpg')<br>
plt.imshow(img)<br>
![image](https://user-images.githubusercontent.com/98145090/173804024-27d31380-8335-4e12-a2b8-9c1cc5bf8ae9.png)<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 3)Develop a pgm to perform liner transformation rotation<br>
from PIL import Image<br>
img=Image.open("leaf.jpg")<br>
img=img.rotate(180)<br>
img.show()<br>
cv2.WaitKey(0)<br>
cv2.destroyAllWndows()<br>
Output:<br>
 ![image](https://user-images.githubusercontent.com/98145090/173805940-de5be5ca-afb4-4154-97fd-0033a2ce123e.png)<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 5)Develop a pgm to convert color string to RGB color Values<br>
from PIL import ImageColor<br>
img=Image.new('RGB',(200,400),(255,255,0))<br>
img.show()<br>
Output:<br>
![image](https://user-images.githubusercontent.com/98145090/173814822-4902a90a-0522-47b2-8938-0e6e344e5352.png)<br>
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 4)Write a pgm to create image using colors<br>
from PIL import ImageColor<br>
img1=ImageColor.getrgb("yellow")<br>
print(img1)<br>
img2=ImageColor.getrgb("red")<br>
print(img2)<br>
Output:<br>
![image](https://user-images.githubusercontent.com/98145090/173812856-38cce19b-dd95-4a17-8007-67e5a3e67251.png)<br>
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
# 6)Develop a pgm to create image using various colors spaces<br>
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
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 7)Write a pgm to display the image attribute<br>
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

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 8)Develop a pgm to read image using URL<br>
from skimage import io<br>
import matplotlib.pyplot as plt<br>
url='https://assets.goal.com/v3/assets/bltcc7a7ffd2fbf71f5/bltc46c24cf519daecc/60df72b928853322c5823d7f/debc6f7ab23f69c656a6e7eb7d6912335f0d75f7.jpg?quality=80&width=620&format=pjpg&auto=webp'<br>
image=io.imread(url)<br>
plt.imshow(image)<br>
plt.show()<br>
Output:<br>
![image](https://user-images.githubusercontent.com/98145090/175259317-80315410-53e4-4645-9910-13e37d4dbf29.png)<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 9)Write a pgm to mask and blur the image <br>
9.1)import cv2<br>
import matplotlib.image as mping<br>
import matplotlib.pyplot as plt<br>
img=mping.imread('fly.jpg')<br>
plt.imshow(img)<br>
plt.show()<br>
Output:![image](https://user-images.githubusercontent.com/98145090/175263488-056efb77-3213-49ff-a4d2-d4ebba6c75d7.png)<br>
<br>
9.2)hsv_img=cv2.cvtColor(img,cv2.COLOR_RGB2HSV)<br>
light_orange=(1,190,200)<br>
dark_orange=(18,255,255)<br>
mask=cv2.inRange(hsv_img,light_orange,dark_orange)<br>
result=cv2.bitwise_and(img,img,mask=mask)<br>
plt.subplot(1,2,1)<br>
plt.imshow(mask,cmap='gray')<br>
plt.subplot(1,2,2)<br>
plt.imshow(result)<br>
plt.show()<br>
Output:![image](https://user-images.githubusercontent.com/98145090/175263597-d86f9587-b701-4450-bf49-12aa3e069c4e.png)<br>
<br>
9.3)light_white=(0,0,200)
dark_white=(145,60,255)<br>
mask_white=cv2.inRange(hsv_img,light_white,dark_white)<br>
result_white=cv2.bitwise_and(img,img,mask=mask_white)<br>
plt.subplot(1,2,1)<br>
plt.imshow(mask_white,cmap='gray')<br>
plt.subplot(1,2,2)<br>
plt.imshow(result_white)<br>
plt.show()<br>
Output:![image](https://user-images.githubusercontent.com/98145090/175263686-87652b22-a6ee-4b9e-913a-55d8ce4dac7a.png)<br>
<br>
9.4)final_mask=mask+mask_white<br>
final_result=cv2.bitwise_and(img,img,mask=final_mask)<br>
plt.subplot(1,2,1)<br>
plt.imshow(final_mask,cmap='gray')<br>
plt.subplot(1,2,2)<br>
plt.imshow(final_result)<br>
plt.show()<br>
Output:![image](https://user-images.githubusercontent.com/98145090/175263744-b6e04cdd-1e8d-405d-bb6b-b542464058cd.png)<br>
<br>
9.5)blur=cv2.GaussianBlur(final_result,(7,7),0)<br>
plt.imshow(blur)<br>
plt.show()<br>
Output:![image](https://user-images.githubusercontent.com/98145090/175263790-3ce98372-4639-49ec-9d21-19a2a23894bc.png)<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 10) Write a pgm to perform arithmatic operations on images<br>
import cv2<br>
import numpy as np<br>
import matplotlib.image as mping<br>
import matplotlib.pyplot as plt<br>
#Read file<br>
img1=cv2.imread('re.jpg')<br>
img2=cv2.imread('resi.jpg')<br>
#numpy add<br>
fimg1 = img1 - img2<br>
plt.imshow(fimg1)<br>
plt.show()<br>
#saving<br>
cv2.imwrite('output.jpg',fimg1)<br>
fimg2 = img1 - img2<br>
plt.imshow(fimg2)<br>
plt.show()<br>
#saving<br>
cv2.imwrite('output.jpg',fimg2)<br>
fimg3 = img1 * img2<br>
plt.imshow(fimg3)<br>
plt.show()<br>
#saving<br>
cv2.imwrite('output.jpg',fimg3)<br>
fimg4 = img1 / img2<br>
plt.imshow(fimg4)<br>
plt.show()<br>
#saving<br>
cv2.imwrite('output.jpg',fimg4)<br>
Output:![image](https://user-images.githubusercontent.com/98145090/175271947-e061e046-d02f-432a-ab7d-c8f37110bf82.png)
<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 11)
Output:<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 12)
import cv2 as c<br>
import numpy as np<br>
from PIL import Image<br>
array=np.zeros([100,200,3],dtype=np.uint8)<br>
array[:,:100]=[255,130,0]<br>
array[:,100:]=[0,0,255]<br>
img=Image.fromarray(array)<br>
img.save('IMAGES.jpg')<br>
img.show()<br>
c.waitKey(0)<br>
Output:![image](https://user-images.githubusercontent.com/98145090/175273618-276115e7-d2bb-4c02-a128-0f53531ea99f.png)<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 13)<br>import cv2<br>
img=cv2.imread('butterfly.jpg')<br>
print('Original image length width',img.shape)<br>
cv2.imshow('Original image',img)<br>
cv2.waitKey(0)<br>
imgresize=cv2.resize(img,(200,300))<br>
cv2.imshow('Resized image',imgresize)<br>
print('Resized image length width',imgresize.shape)<br>
cv2.waitKey(0)<br>
Output:![image](https://user-images.githubusercontent.com/98145090/175277298-b27ff34d-ad2f-4ad2-b6a8-c8abd5ca82ec.png)<br>

![image](https://user-images.githubusercontent.com/98145090/175276954-cec613e8-9b3f-4207-a558-0e4df4eb54d3.png)<br>
<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 14)import cv2<br>
img=cv2.imread('F://butterfly2.png')<br>
gray=cv2.cvtColor(img,cv2.COLOR_BGR2GRAY)<br>
hsv=cv2.cvtColor(img,cv2.COLOR_BGR2HSV)<br>
lab=cv2.cvtColor(img,cv2.COLOR_BGR2LAB)<br>
hls=cv2.cvtColor(img,cv2.COLOR_BGR2HLS)<br>
yuv=cv2.cvtColor(img,cv2.COLOR_BGR2YUV)<br>
cv2.imshow("GRAY image",gray)<br>
cv2.imshow("HSV image",hsv)<br>
cv2.imshow("LAB image",lab)<br>
cv2.imshow("HLS image",hls)<br>
cv2.imshow("YUV image",yuv)<br>
cv2.waitKey(0)<br>
cv2.destroyAllWindows()<br>
Output:<br>
![image](https://user-images.githubusercontent.com/98145090/175281759-538502ba-0702-4e32-94aa-417f41acf825.png)<br>
![image](https://user-images.githubusercontent.com/98145090/175281782-66d150f2-72d4-4ced-84e6-cb4ae72bca08.png)<br>
![image](https://user-images.githubusercontent.com/98145090/175281805-30fe455f-e65e-4bcd-a6dd-20108106d7cf.png)<br>
![image](https://user-images.githubusercontent.com/98145090/175281835-e527f194-54b5-406e-b526-f30d86855c71.png)<br>
![image](https://user-images.githubusercontent.com/98145090/175281856-1628742d-cc8d-4476-84a0-6b149c33fd1c.png)<br>
<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 15)Blurr
Output:![origin1](https://user-images.githubusercontent.com/98145090/176408332-69516204-658b-4297-bcab-a2bb1a7e3491.png)
![Gauss1](https://user-images.githubusercontent.com/98145090/176408394-a3d75e53-1708-46c7-92b0-acfdbbf5fdce.png)
![median1](https://user-images.githubusercontent.com/98145090/176408423-c6cb3e5c-d1ed-4399-a998-fcf71734cf0c.png)
![bilat1](https://user-images.githubusercontent.com/98145090/176408457-c95b72f7-c466-4c07-87b5-15ef7e5c4ae9.png)

<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 16)iMAGEeNHANCEMENT<br>
#Image Enhancement<br>
from PIL import Image<br>
from PIL import ImageEnhance<br>
image = Image.open('butterfly.jpg')<br>
image.show()<br>
enh_bri = ImageEnhance.Brightness(image)<br>
brightness=1.5<br>
image_brightened = enh_bri.enhance(brightness)<br>
image_brightened.show()<br>
enh_col = ImageEnhance.Color(image)<br>
color=1.5<br>
image_colored = enh_col.enhance(color)<br>
image_colored.show()<br>
enh_con = ImageEnhance.Contrast(image)
contrast=1.5<br>
image_contrasted = enh_con.enhance(contrast)<br>
image_contrasted.show()<br>
enh_sha = ImageEnhance.Sharpness(image)
sharpness=3.0<br>
image_sharped = enh_sha.enhance(sharpness)<br>
image_sharped.show()<br>
Output:![imgenhance](https://user-images.githubusercontent.com/98145090/176412110-bbfc7cc2-dfba-4080-8bf7-77823b42f6ee.png)<br>
<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
# 17)Read and Write<br>
import cv2<br>
OriginalImg=cv2.imread('naruto.jpg')<br>
GrayImg=cv2.imread('naruto.jpg',0)<br>
isSaved=cv2.imwrite('E:/i.jpg',GrayImg)<br>
cv2.imshow('display original Image', OriginalImg)<br>
cv2.imshow('display Grayscale Image',GrayImg)<br>
cv2.waitKey(0)<br>
cv2.destroyAllWindows()<br>
if isSaved:<br>
    print('The image is saved succesfully.')<br>
<br>
Output: The image is saved succesfully.<br>
 ![read write](https://user-images.githubusercontent.com/98145090/178708440-21929b12-885c-447e-aee4-62e22f459ddd.png)<br>
![read write gray](https://user-images.githubusercontent.com/98145090/178708470-4eb1389f-7b08-4300-8436-0564e9c06f42.png)<br>
<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
18)
Output:<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br>
<br>
19)
Output:<br>
