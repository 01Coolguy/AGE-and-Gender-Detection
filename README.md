# AGE-and-Gender-Detection
 The project detects the Age and Gender of the Given image
 #Technology: 
 CNN,Machine Learning,JupyterNotebook,Anaconda Navigator,Python,Libraries such as(Tensorflow,Layers,numpy,keras,Flatten,Tkinter)Kaggle Dataset

## lib
```bash
pip install Tensorflow
pip install tkinter
pip install numpy
```

## Usage

```python
import tensorflow as tf
import cv2 as cv2
import numpy as np
import matplotlib.pyplot as plt 
```

## Dataset
Create training data from the UTKFace dataset [currently not supported]
Firstly, download images from the website of the UTKFace dataset. UTKFace.tar.gz can be downloaded from Aligned&Cropped Faces in Datasets section. Then, extract the archive.


Finally, run the following script to create the training data:

python create_db_utkface.py -i UTKFace -o UTKFace.mat
[NOTE]: Because the face images in the UTKFace dataset is tightly cropped (there is no margin around the face region), faces should also be cropped in demo.py if weights trained by the UTKFace dataset is used. Please set the margin argument to 0 for tight cropping:

## Sample



![Screenshot 2023-05-21 001833](https://github.com/01Coolguy/AGE-and-Gender-Detection/assets/110630419/6ce96858-d58a-4d97-93c7-4d69ce70f0a3)

![Screenshot 2023-05-21 002123](https://github.com/01Coolguy/AGE-and-Gender-Detection/assets/110630419/71eb73a7-7b9e-435f-a483-8efcf220faf6)


