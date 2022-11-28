# Mini-Project--Application-of-NN



## Project Title:
## <p align="center">Gender Classification</p>
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
![d](https://user-images.githubusercontent.com/75235704/204225271-af386cc1-b902-477e-92ab-802a10bed85d.png)


## Advantage :
## Result:
