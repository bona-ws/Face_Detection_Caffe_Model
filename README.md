# Face Detection using Caffe Pretrained Model

What this app could do :

- Detecting faces in pictures
- Detecting faces in live webcam

Make sure you already install all requirement lists :

- numpy
- argparse
- imutils
- time
- cv2

## How to run this app
Clone this repo, move to the path and follow instruction below

### Face detection by images

Run this script

```groovy
python detect_faces.py --image images/pilkada.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel
```
You can add more images into folder "images/", and change the parameter images/"your_picture_name.jpg"

## Face detection by video camera

Run this script

```groovy
python detect_faces_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel
```

Just it. Have fun !
