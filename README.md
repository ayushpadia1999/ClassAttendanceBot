# ClassAttendanceBot
 This is a script which can be called repeatedly to attend all your online classes.Please note that this was made only for Educational Purposes ;) and we do not recommend using it to bunk class .
 
 This is a script which can be called repeatedly to attend all online classes for a student from KIIT University using a python Bot.Please note that this was made only for Educational Purposes and I do not recommend using it to bunk class. The Bot is built on python using pyautogui.

 This bot can be used by calling a function with the meeting link, time and Duration Of Meeting , the name of the function depends on the platform on which the meeting is being conducted and it automatically opens Google Meet or zoom at the entered time and logs in on the behalf of the user. The bot automatically enters using the KIIT email ID of the user and switches off the Audio and Video of the user while entering the meet.
Once the meeting is done, it closes the Google Chrome page and this process continues every time the user has an online class to attend.

The Bot uses Image Recognition in order to use the various buttons on zoom and google meet required to log into a meeting. After the bot enters the meeting it automatically opens the chat window in order to periodically search for attendance links or students entering their roll no. in order to be marked present.

When the bot encounters a google form it clicks on the form and inputs the users roll no and submits it. If it finds more than 5 students entering their roll numbers in the chat box. It automatically enters the user's Roll No in the chat box and exits the meeting.  

Future Scope:
Speech Recognition can be used in order to enable the script to play a pre-recorded voice note from the user saying ‘present’  whenever the professor calls out their name or roll no. Further a UI can be developed to make it easier for the user to use it without having to call functions repeatedly. 


