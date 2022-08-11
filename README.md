# Android-apk-automation-testing---POST-IMAGE
Python Automation Appium (Task 2): Using Appium Automation to post an Image in ATG app running on an android emulator

This is Banao Internship Selection task 2
This is a Automation program that automate an app(ATG) running in an android emulator(android studio).
Goal is to post an image through app.

Loggin Id Used:- hello@atg.world Password:- Pass@123

--------------------------------------------------------------------------------------

Steps involved:-
----------------
step 1: Grant Storage and Media Permission

step 2:Log Into the app

step 3:If 'Got It' Button Shows Up Press It

step 4:Go to Post Option and Select Image

step 5:Select 1st Image

step 6:Hit Post

step 7:Go Back To Home Page

step 9:Checking Post In My Posts

-----------------------------------------------------------------------------------------------------------

Test Cases:-
------------
1 --> When you are not Logged In. We need to enter email address and passward to get started.

2 --> When you are Logged In. Just Print "Already logged In" and Continue

3 --> "Got It" button shows up sometimes on home page. So have to account for that

4 --> If there is no Image to select in gallary

-------------

NOTE:- Appium Sever and Emulator both should be running.
