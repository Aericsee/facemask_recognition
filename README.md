# Facemask_recognition
An institute project which a facemask detection program is build

## Installation
> STEP 1
After unzipping the forked zip file of this project into your local machine, type the follwing command from the directory where you saved the project files in the command prompt: 
pip install -r requirements.txt

This will install thw following libraries:

absl-py==0.9.0
astunparse==1.6.3
cachetools==4.1.1
certifi==2020.6.20
chardet==3.0.4
cycler==0.10.0
gast==0.3.3
google-auth==1.19.2
google-auth-oauthlib==0.4.1
google-pasta==0.2.0
grpcio==1.30.0
h5py==2.10.0
idna==2.10
importlib-metadata==1.7.0
imutils==0.5.3
joblib==0.16.0
Keras-Preprocessing==1.1.2
kiwisolver==1.2.0
Markdown==3.2.2
matplotlib==3.3.0
numpy==1.19.1
oauthlib==3.1.0
opencv-python==4.3.0.36
opt-einsum==3.3.0
Pillow==7.2.0
protobuf==3.12.2
pyasn1==0.4.8
pyasn1-modules==0.2.8
pyparsing==2.4.7
python-dateutil==2.8.1
requests==2.24.0
requests-oauthlib==1.3.0
rsa==4.6
scikit-learn==0.23.1
scipy==1.4.1
six==1.15.0
sklearn==0.0
tensorboard==2.2.2
tensorboard-plugin-wit==1.7.0
tensorflow==2.2.0
tensorflow-estimator==2.2.0
termcolor==1.1.0
threadpoolctl==2.1.0
urllib3==1.25.10


> STEP 2
Open Jupyter Notebook and run Data Augmentation and Preprocessing.ipynb in order to train your custom dataset within your loacl machine and preprocess the images meanwhile.

> STEP 3
Run detect_mask_from_webcam.py from the same directory of your project folder in the command prompt in order to test the detector in real- time using the webcam.
