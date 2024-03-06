Smart Attendance System
This project is a Smart Attendance System designed to record attendance using facial recognition technology. It consists of several Python scripts and a Streamlit web application.

Features
Add_faces.py: This script is used to add faces to the dataset. Faces are recorded via webcam.

test.py: This script records attendance of added faces. Press 'o' to record attendance. It creates a CSV file corresponding to the date with records of name and timestamp.

app.py: This script runs a Streamlit web application where attendance is displayed and can be downloaded in CSV format.

Usage
Run python Add_faces.py to add faces to the dataset. Faces will be recorded using the webcam.

Run python test.py to record attendance. Press 'o' to record attendance. The script will create a CSV file with attendance records for the corresponding date.

Run streamlit run app.py to start the Streamlit web application. Attendance will be displayed here and can be downloaded in CSV format.

Requirements:
Python 3.x
OpenCV
Streamlit

Installation:
Clone the repository:
git clone https://github.com/Aryan556gaur/Smart-Attendance-System.git

Install the required dependencies:
pip install -r requirements.txt
