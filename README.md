# Lab1_COSC341
Lab 1: Android Basics (20 marks) 

The purpose of this lab is to help you get started with mobile application development with 
Android.  
Configuration note: 
When  you  create  your  app  on  Android  Studio,  be  sure  to  select  the  option  "Phone  and 
Tablet". Assignments will be marked using an Android Virtual Device (AVD) running a  Pixel 
3a with API 33. You must use Android Studio (with Java as the programming language), this 
is what the TAs will use to load, build, and run your code. 
Submission note: 
Upload a zip file containing the following folders to Canvas: Code and APK.  
- The Code folder should include two subfolders: Question 1 and Question 2 with the 
corresponding Android code.  
- APK folder should only contain two .apk files.  
 
Question 1 (10 marks): Create an Android application that allows users to switch between 
multiple images.  
The app should contain the followings: 
- An ImageView to display an image. First, load four images into your drawable folder. Now, 
Load one image at a time into the ImageView based on the button click events (see the 
button click instruction next) 
- Add one text view below the ImageView showing the current image number (e.g., 1 of 4)  
- Add three buttons: “NEXT”, “PREVIOUS” and “RANDOM”. Pressing the 
o “NEXT” button loads the next image into the ImageView. Once a user reaches the 
last  image  (e.g.,  4  of  4)  and  presses  the  NEXT  button  again,  the  application  will 
show the first image (e.g., 1 of 4). 
o “PREVIOUS” button will show the previous image. Once a user moves to the first 
image  (e.g.,  1 of 4)  and  presses  the  PREVIOUS  button  again,  the  application  will 
show the last image (e.g., 4 of 4). 
o  “RANDOM” button will display a random image from the list of images 
Note: This can also be solved using ImageSwitcher. However, we will use ImageView for this 
question.  

Grading Criteria: 

UI Component: 

[5 marks] ImageView showing an image, TextView showing the current image number, three 
buttons with proper layout  

Functionalities:  

[5 marks] The app shows correct images once the buttons are pressed 

