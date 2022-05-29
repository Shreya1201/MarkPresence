# MarkPresence
Face recognition attendance system

This project intends to serve as an efficient substitute for traditional manual attendance systems.
It can be used in corporate offices, schools, and organizations where security is essential.                   
It is an Attendance project that uses a webcam to detect faces and record the attendance live in an excel sheet.                
The system mainly works around 2 types of users
.Employee
.Admin

Following functionalities can be performed by the admin:
• Login
• Register new employees to the system by adding employee photos.
• View attendance report of all employees. 

Following functionalities can be performed by the employee:
• Mark his/her attendance by scanning their face

About files
Basics img : Folder which contains photos of all employees. Employee's name should be the file name.
attendance.py : Main ML model which compares your face with the images from the dataset and return the name and date 
time in an excel sheel.
attendance.csv : Excel sheet where attendance extries are done my ML model.
style.css : css file.
home.html : Main page of our website.
login.html : login page for Admin.
admin.html : Admin page where he/she can options to register new employee or view attendance of all employees.
uploadImg.html : Page where admin can register new employees by uploading their photos.
AttendanceTable : Page where admin can view attendance of all the employees.
contactUs.html : Page for any enquery.
attendancetotable.py : file to print excel sheet data on html page.
uploadImg : For uplaoding employee Image.

How to run?
1. Clone this repo.
2. Make a separate python virtual environment or use the default one already installed on your machine
3. Install pip, face_recognition, cv2, numpy, flask, os, datetime libraries.
4. Run the home.html file on your browser and enjoy.
