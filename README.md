# Motion-detecting
This is a project where I used an arduino ESP32 with a PIR motion detector to both update a self hosted web server and send messages through signals api to my phone to update me when motion is detected.

I had to work around constraints like:
The api’s limit of 40 messages per 4 hours.
I also had to overcome the challenge of updating the web server's html to display; the new motion detected, a counter of all detection and a call to a different website to the current time for the detection. 

![20231005_141125](https://github.com/BadBanana5/Motion-detecting/assets/134112996/c3b0e513-bef6-42a5-a285-8eb3fa1ca47f)
![Screenshot_20231005-142115_Signal](https://github.com/BadBanana5/Motion-detecting/assets/134112996/f2024523-18b6-4e0c-9b68-0c370ce81c23)
