
Facial Recognition Demo
========================
facial recognition program with PyQT5 GUI.


Dependencies
========================
python 3.6, cmake

```
pip install -r requirements.txt
```

Executing program
========================
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

Video Demo
========================
https://github.com/taufik-adinugraha/face-recognition-demo-PyQT5/blob/main/demo_video.mp4
