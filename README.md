# Tensorflow-2-Real-Time-Object-Detection


### Prerequisites

- Python
- TensorFlow
- TensorBoard
- Protobuf v3 or above

### Steps For Installation - 

(1) Tensorflow - To Download TensorFlow and TensorFlow GPU, you can use pip or conda commands:
#### For CPU
pip install tensorflow
#### For GPU
pip install tensorflow-gpu


#### For all the other libraries, we can use pip or conda to install them. The code is provided below:

- pip install Cython
- pip install contextlib2
- pip install pillow
- pip install lxml
- pip install jupyter
- pip install matplotlib

(2) Next Download Protobuf latest version and extract it.

https://github.com/google/protobuf/releases 


(3) Now you need to clone or download TensorFlow’s Model from GitHub. Once downloaded and extracted, rename the "models-masters" to just "models."

https://github.com/tensorflow/models

(4) keep “models” and “protobuf” under one folder named "Tensorflow. or any thing of your choice"

(5) Next, we need to go inside the Tensorflow folder and then inside the research folder and run protobuf from there using this command:

open cmd - 

cd C:\Users\Nitin\Desktop\Tensorflow\models\research

once you are in the research dirextory, execute protobuf using this command - 

 'C:\Users\Nitin\Desktop\Tensorflow\protoc-3.15.8-win64\bin\protoc.exe' object_detection/protos/*.proto --python_out=.


To check whether this worked or not, you can go to the protos folder inside models>research>object_detection>protos and there, you can see that for every proto file, there’s one python file created.

(6) Now run setup.py file which is inside research directory by using this command - 
  - To install a package that includes a setup.py file, open a command or terminal window and:
- cd into the root directory where setup.py is located.
- Enter: python setup.py install

(7) Now create a python ipynb or .py(object_detection_real_time) file inside research directory.

(8) run python file.


