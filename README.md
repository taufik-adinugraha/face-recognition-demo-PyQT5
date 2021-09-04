# Project Title
Facial Recognition Demo


## Description
facial recognition program with PyQT5 GUI.

## Getting Started

### Dependencies
python 3.6

### Installing
pip install -r requirements.txt

### Executing program

```
cd codes
python main.py
```

it might be necessary to modify facealigner.py from dlib library:

from
```
M = cv2.getRotationMatrix2D(eyesCenter, angle, scale)
```
into
```
M = cv2.getRotationMatrix2D([int(i) for i in eyesCenter], angle, scale)
```
