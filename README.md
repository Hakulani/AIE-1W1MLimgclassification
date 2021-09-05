# AIE-1W1MLimgclassification

![alt text](https://github.com/Hakulani/AIE-1W1MLimgclassification/blob/main/rferfge.JPG?raw=true)


AI Essential1 Week1 image classification botnoi ,  keras ,tenserflow

Create dataset from using google searching image file and save to folder

#Install and import lib
```
!pip uninstall keras
!pip uninstall tensorflow
!pip install keras==2.4.3
!pip install tensorflow==2.4.3
!pip install botnoi==0.2.1



import botnoi as bn
from botnoi import scrape as sc
from botnoi import cv
import os

```

#Create dataset

```
ds=createdataset(['โรงเรียน','โรงแรม'])

```
 
#Create  Classifier
```
createclassifier(['โรงเรียน','โรงแรม'],'โรงเรียนโรงแรม.mod')  # เปลี่ยนชื่อที่ต้องการแยก
```
