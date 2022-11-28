# Mini-Project--Application-of-NN


(Expected the following details in the report )
## Project Title:
Gender Classification
## Project Description 
## Algorithm:
## Program:
```py
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
![d](https://user-images.githubusercontent.com/75235704/204224961-a94437f9-8ab0-40ab-b67f-97418f1fea93.png)


## Advantage :
## Result:
