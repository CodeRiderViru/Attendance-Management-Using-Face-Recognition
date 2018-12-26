# Attendance-Management-Using-Face-Recognition
An attendance management system which use Real-Time face recognition for attendance. Database use is in mongoDB.

# Basic Overview
This is my attempt to make a Face recognition system for classroom or office attendance . The basic approach here is feed your dataset into simease network which will give a relevant encoding of face. The architecture of simease network use inception blocks. INCEPTION BLOCK is a 
concept in Deep learning  in which we can use different size of filters in a single layer.

![46079121-d1ebd300-c1b3-11e8-88b7-ce9dba37b37e](https://user-images.githubusercontent.com/42006221/50447326-5c250e00-0940-11e9-812b-9fe1724738be.jpg)


![screenshot 108](https://user-images.githubusercontent.com/42006221/50447422-0d2ba880-0941-11e9-9a3d-ddcd2ce715cf.png)

Screenshot are taken from Deep Learning Specialization Coursera(Andrew NG )

Step 1.
Load faceRecoModel ,and  architecture of this model in utility file .

Step 2.
Load weights ,i have provided all weights which i downloaded directly facenet 

step 3.
generate Encodings ,input your images into this cnn architecture and store all your dataset images encoding in a list

step 4.
Create new Nueral Network for Classification task
Feed this list of encodings to this nueral network.

Step 5 
Recognise the person 


Yeah that's all for this task Isn't it easy ?


For attendance storing purpose i have used MongoDB that part is self-explantiory.
