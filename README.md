# DrowsinessVF

## Please download in the face shape file in the project directory : "shape_predictor_68_face_landmarks.dat" from this link:

https://github.com/AKSHAYUBHAT/TensorFace/blob/master/openface/models/dlib/shape_predictor_68_face_landmarks.dat


## Type these on Anaconada Prompt :

pip install --upgrade imutils

pip install playsound

pip install https://pypi.python.org/packages/da/06/bd3e241c4eb0a662914b3b4875fc52dd176a9db0d4a2c915ac2ad8800e9e/dlib-19.7.0-cp36-cp36m-win_amd64.whl#md5=b7330a5b2d46420343fbed5df69e6a3f

## To execute the script : 

python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat --alarm alarm.wav
