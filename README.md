# Mini-Project--Application-of-NN



## Project Title:
## <p align="center">Gender Classification</p>

## Algorithm:
1.Install deepface

2.Import necessary packages

3.Read the image

4.Analyze the gender using deepface
## Program:
```py
/*
Program to implement 
Developed by   :DurgaDevi P
RegisterNumber :  212220230015
*/
#install deepface
pip install deepface

#import packages
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt

#read the image
img=cv2.imread('durga2.jpeg')
plt.imshow(img[:,:,::-1])
plt.show()

#Analyze gender
result=DeepFace.analyze(img,actions=['gender'])
result2=DeepFace.analyze(img,actions=['emotion'])

#print the gender
print("Gender : ",result['gender'])

```
## Output:
![d](https://user-images.githubusercontent.com/75235704/204225271-af386cc1-b902-477e-92ab-802a10bed85d.png)



## Result:
 Thus the program for gender classification is implemented successfully.
