# Autopsy deleted files recovery

<h1> This is an exercise provided by the TryHackMe DFIR course </h1>

 
 #### All images and copyrights are protected for TryHackMe

<h2>Description</h2>
Project: Recovering deleted files 
Objective: Find the deleted files and recover the txt file to find what is inside it.

<h2>Tools/ Utilities Used</h2>

- <b> Windows Virtual Machine</b>
- <b>Autopsy forensics tool</b>

Tasks:

1- Find the full name of the "other" xlxs file.

2- Find the name of the text file that was deleted.

3- Recover the deleted text file.
  
 
 Starting Autopsy:
  
  By launching the tool from the desktop. If this is the first time to use it, we will have the second option ( open recent case greyed out). 
  We will Select a New case. First option.
  
  ![Autospy new case](https://github.com/TheRashaSharif/Autospy/assets/98124961/e7442aab-270f-4aed-aa87-a2708989febd)

As any new file is created we will have to select the location to save the case ( I created a folder on the desktop on the spot called Autopsy)
  ![Autospy case naming 1](https://github.com/TheRashaSharif/Autospy/assets/98124961/12434126-3d70-458b-a6d0-8d60ea1edb18)

  Then fill in the case number and basic investigation information. Then click finish.
  
  ![Autospy case creation s](https://github.com/TheRashaSharif/Autospy/assets/98124961/1869a460-87c2-4742-a555-eccc61ecb178)
  
  There is a disk image saved on the desktop to be opened usb.001
  
![Autospy data source disk image](https://github.com/TheRashaSharif/Autospy/assets/98124961/0b213042-2315-42ec-b7e0-673cc727dd38)
  
  De-Select all the configure and inject options as we do not need them for the project.
  
![Autospy deselect all](https://github.com/TheRashaSharif/Autospy/assets/98124961/9f029654-c095-43c1-bc15-4cc258588c00)
  
  Finish selecting the image source.
  ![Autospy finish selecting images](https://github.com/TheRashaSharif/Autospy/assets/98124961/40412201-5a0e-4108-bf77-5079e9d69dec)
  
  
  The tree view on the left side will show the deleted files ( with a red x next to the folder as an indication).
  
  1- TryHackme.xlsx
  
  By right-clicking on a deleted file we can select extract files - to recover
  or
  export selects rows to CVS if we need to view it in EZ viewer.
  
  to answer task #1 the name of the xlsx is TryHackme.xlsx
  ![Autospy recover](https://github.com/TheRashaSharif/Autospy/assets/98124961/b02e2490-1992-4e91-a150-9227c85867c8)

  2- TryHackMe2.txt is the name of the txt file that was deleted.
 ![Autospy txt](https://github.com/TheRashaSharif/Autospy/assets/98124961/a86439a9-a13b-413e-bded-32ee3a6dba8f)

  3- TryHackMe2.txt
  
  to recover it, right-click and select extract file(s) it will be recovered and saved in a desired location.

![Autospy txt2](https://github.com/TheRashaSharif/Autospy/assets/98124961/c803edc3-18fc-4bf8-b094-79128e606f1a)

  If we opened it the text inside it is:
  
  ![Autospy text](https://github.com/TheRashaSharif/Autospy/assets/98124961/de872c42-7e5e-42fc-9c6f-bbf95953b3c3)

  
 this completes  task# 3 
