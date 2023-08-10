# Face recognition photo to camera

<p align="justify">
Facial recognition where an image of a person reocnoce and validates it through the camera, ie compares what you are seeing in the camera with the image if they are the same comes out the label of the selected name and if not comes out "False".
</p>

<p align="center">
  <img src="README-images\detect.PNG" alt="StepLast">
</p>

## Steps to implement

Note: Have **good GPU** 

1. Modify root to your root 'dlib-19.22.99-cp310-cp310-win_amd64.whl'
   
   <p align="center">
  <img src="README-images\req.PNG" alt="StepLast">
 </p>

1. Use Dockerfile 
2. Use virtual enviroments and apply  requirements.txt 
```python
#virtual enviroment with conda 
conda create -n my_enviroment python=3.10.12

pip install -r requirements.txt
```
if you do not want to use requirements.txt
```python
#install dependecies o libraries
#Same root 
pip install dlib-19.22.99-cp310-cp310-win_amd64.whl

pip install face-recognition
pip install opencv-python
```

---
#### Another way to do it but more time consuming or error with dlib

##### Steps 

1. Install Visual Studio 
   
 <p align="center">
  <img src="README-images\visual-studio.PNG" alt="StepLast">
 </p>

 <p align="center">
  <img src="README-images\instalation-option.PNG" alt="StepLast">
 </p>

2. Without virtual enviroments , in local cmd
```python
#install dependecies o libraries
pip install cmake

pip install dlib 

```  
For all packets to be transmitted to a virtual environment such as conda is 
```python
conda install -c conda-forge dlib
```  
3. You can now create a virtual environment and make 
```python
pip install face-recognition
pip install opencv-python
``` 
Or if is local 
```python
pip install face-recognition
pip install opencv-python
``` 
