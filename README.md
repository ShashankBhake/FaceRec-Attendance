# Face Recognition based Attendance Management System
Attendance Management System based on Face Recognition using Python and OpenCV  

### Code Requirements
- Opencv(`pip install opencv-python`)
- Tkinter(Available in python)
- PIL (`pip install Pillow`)
- Pandas(`pip install pandas`)

### Steps to follow
- Download my Repository 
- Create a `TrainingImage` folder in a project.
- Open a `AMS_Run.py` and change the all paths with your system path
- Run `AMS_Run.py`.

### Working of this project

- After running, you need to enter your ID and name in box than click on `Take Images` button.
- It will collect ~70 images of your faces and save them in `TrainingImage` folder
- After that we need to train a model(to train, click on `Train Image` button.)
- It will take around 10 seconds for each person's image to train.
- After training click on `Automatic Attendance` ,it fills attendance by recognizing your face using the trained model (model will be saved in `TrainingImageLabel` )
- it will create `.csv` file of attendance according to time & subject.
- You can store data in database (install `wampserver`),change the DB name according to your in `AMS_Run.py`.
- `Manually Fill Attendance` Button in UI is to fill attendance manually(without face recognition),it creates a `.csv` and stores in a database.


### Screenshots

### Homepage
<img src="https://github.com/ShashankBhake/FaceRec-Attendance/blob/main/homepage.jpg">

### GUI
<img src="https://github.com/ShashankBhake/FaceRec-Attendance/blob/main/GUI.jpg">

### Checking students list
<img src="https://github.com/ShashankBhake/FaceRec-Attendance/blob/main/StudentList.jpg">

### Model Trained message
<img src="https://github.com/ShashankBhake/FaceRec-Attendance/blob/main/trainedPopup.jpg">

### Note:
- It requires high processing power(I have 8 GB RAM)
- Noisy image can reduce the accuracy.


