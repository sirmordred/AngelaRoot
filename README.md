# AngelaRoot

Whats this and behind the story:
- Well, all of this story is started with the exploration of vulnerability in Oneplus devices by mysterious twitter user who are using 'Elliot Alderson' as her/his nickname :) and you know Elliot Alderson is the real name of main character which is pro-hacker in Mr.Robot series, you can take a look his/her twitter flood from here https://twitter.com/fs0c131y/status/930115188988182531?lang=tr
he just found out an unknown app which called as 'EngineerMode.apk' in Oneplus phones and later he succesfully disassembled the apk and found the vulnerability, the app itself is a testing app and left by Oneplus engineers while production, and as a mistake (but lots of people think that they put it intentionally for spying users) they forgot to remove that test app from release-builds,
THE MOST MYSTERIOUS PART is:
with that app and vulnerability, users (and hackers too) can grant root privileges (god mode in linux, you can do anything you want with that root privileges) with the following command **adb shell am start -n com.android.engineeringmode/.qualcomm.DiagEnabled --es "code" "PASSWD"** and what is PASSWD, well its 'Angela' :) thanx to twitter user who explored this vulnerability, he also disassembled/extracted required password to issue the above command, and its really shocked lots of people, the password was 'Angela' and nickname of twitter user who explored this vulnerability is Elliot Alderson as i wrote above

And what is AngelaRoot app, well after exploration of vulnerability, i succesfully made an app which automates all process so users dont need to make lots of steps, they just need to initiate 2 scripts after opening app and voila they can grant root privilege to their android phones

Download: http://www.mediafire.com/file/nm7x9zitvvzfuy5/AngelaRootV4.apk

Developed by @sirmordred Oguzhan Yigit

Credits to Security Researcher @fs0c131y for finding the vulnerability

Thanx to @Zelmarked for testing it on OnePlus3T

Instructions:

- Make sure you enabled "USB Debugging" option on Development Settings

- Open app

- Tap to "Enter FSOCIETY World !" button

- Connect your phone to your PC and type "adb devices" command into PC's terminal to be sure device is detected by PC (it should say something like "2345234857845 device"

- STEP1: Type the "Step 1 Command" which described on app's screen and enter

- STEP2: Type the "Step 2 Command" which described on app's screen and enter

- Done, Congrats :) if SuperSU app shows "update su binary" you dont need to do it, and just dont forget that the "Dont reboot your device" otherwise you need to do same steps to get root access as this app will give you the root access temporarily

Enjoy
