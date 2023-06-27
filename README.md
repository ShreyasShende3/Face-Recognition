<h3 align="center">Classroom Attendance System Using Face Recogntiion</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
</div>

---

<p align="center"> This is a Python program for an attendance system using facial recognition.
    <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [Known Issues](#known_issues)
- [Authors](#authors)
- [License](#license)

## 🧐 About <a name = "about"></a>
The code provides visualizations and insights into various aspects of IPL matches, including toss decisions, match wins, runs scored, and bowling and batting performances.

## 🏁 Getting Started <a name = "getting_started"></a>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 
### Prerequisites
What things you need to install for this project and how to install them.

```
Python 3.x
OpenCV library
Tkinter library
PIL library
pandas library
```

### Installing
The following commands can be used to install the prerequisites and run the code.

1) Install Dependencies

```
pip install opencv-python tkinter pillow pandas

```

2) Clone the repository

```
https://github.com/ShreyasShende3/Face-Recognition.git
```
3) After cloning change the directory to the directory name

```
cd Face-Recognition
```

### Usage

1) Run the script using the following command:
```
python Test.py
```
The program will open a graphical user interface.

2) There are two main functionalities: Take Images and Track Images.
 - Take Images: Enter the ID and Name of the person and click the "Take Images" button. The program will capture multiple images of the person's face using the webcam and save them for training.
 - Take Attendance: Click the "Take Attendance" button to start tracking faces in real-time using the webcam. The program will recognize the faces based on the trained images and display the corresponding ID and Name.

3) The program also provides an option to change the password for accessing the functionalities.
```
Defualt Password is : admin
```
Note: The program stores the captured images and attendance records in the respective folders.

## How to take attendance(follow this) :
1) Enter ID and Name
2) Click take images
3) Save profile using the password
4) Then click take attendance
5) Now the data that will be saved in each folder will be :
    - Attendance :- Saves an excel file for each date which includes ID,Name, Date and Time
    - Student Deatils :- Saves an excel file for all students added
    - Training Image :- Saves the images of students taken
    - Training Label :- Contains the password file and the Trainner file
      
6) You can delete the placeholder files I've added in the Attendance,Student Details and Training Image folders

7) After the completion of all this steps syou should be able the following output :
![Output](https://github.com/ShreyasShende3/Face-Recognition/blob/main/Screenshot%20(8).png)

## Known Issues and Errors <a name= "known_issues"></a>
The following errors might occur and I'll suggest some fixes for it.

1) The most important thing before you run the code is to make sure that you have this file:
```
haarcascade_frontalface_default.xml
```
2) cv2 issues. Sometimes with newer versions of opencv some functions may not work. To resolve this simply downgrade the version of opencv

3) AttributeError: module 'cv2' has no attribute 'face_LBPHFaceRecognizer'. To resolve this use the following command:
```
pip install opencv-contrib-python --upgrade
```
or
```
pip install opencv-contrib-python --user
```

## ✍️ Authors <a name = "authors"></a>
- [@Shreyas](https://github.com/ShreyasShende3)
- [@Aneesh](https://github.com/aneeshkhole)
- [@Varad](https://github.com/VaradKarajkhede)
- [@Atharva](https://github.com/EuroNOX)

## License <a name = "license"></a>
GNU General Public License v3.0
