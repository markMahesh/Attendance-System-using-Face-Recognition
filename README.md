# Attendance-System-using-Face-Recognition

In this project one can mark his/her attendance just by looking in camera. Easy to use easy to mainatain.

So this project was made in jupyter notebook in which i was unable to upload images in tkinter, i recommend to use soem other API.

Now comming to the project when you run the complete code successfully into your system you will see GUI(graphical user interface) where 2 fields has to be filled if a student is new in your class. Then you will see a button "Take Images" click on that and you will see your camera is opened and then it will take 60 frames of yours and save it in the training image directory. After that click on button "Train Images". After training a file "trainner.yml" will be saved in training image label. Lastly click on "Mark Attendance" button, if camera is able to identify your image then it will show your name else it will mark you as unknown and your image will be stored in the "ImagesUnknown" directory. after closing the camera you will be able to see the attendance on your screen as well as in "Attendance" directory.
