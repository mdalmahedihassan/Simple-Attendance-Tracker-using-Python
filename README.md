# Simple-Attendance-Tracker-using-Python
This article will bring a simple tracker &amp; reminder system for attendance. The input to this system is an excel sheet containing the students' mail-id and their number of leaves in each class subject. 

This article will bring a simple tracker & reminder system for attendance. The input to this system is an excel sheet containing the students' mail-id and their number of leaves in each class subject. For say, if a student will not be allowed to write the exam for a particular subject if he takes more than 3 leaves. This tracker will send out an email to the student when he takes the second leave as a reminder that only 1 more left with him on that subject. If he takes further leave, both the student and the corresponding staff receive emails regarding the lack of attendance. The only thing to do is just enter the subject code and roll number of the student absent from the class and the rest will be taken care of by this tracker system.

Python Modules Used
Install the following modules using pip or conda commands.

openpyxl - To update and read from the excel sheet.
smtplib & email   - To send out emails.
Dataset in Use:
The Excel sheet should contain the following data:

Roll number
Student mail ID
Subject {1,2,........N}
For this article, consider three subjects and their codes as numbers for input: 

Computer Intelligence (CI)----> 1
Python ----> 2
Data Mining (DM) ----> 3

Gmail ID for sending mail
It is advisable to create a separate mail ID for use as the sender, as Google blocks less secure apps from signing in to Gmail. Certain permissions have to be given for sending the mail which is risky to do with a personal mail ID. If you do not give permissions you will end up with "bad credentials" error and will receive an email
