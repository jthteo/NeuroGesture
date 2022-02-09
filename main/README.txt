|---------------------------------|
| Neuro Gesture using Leap Motion |
|     ALPHA VERSION 4 Apr 2014    |
|---------------------------------|

Designed by Dr James Teo
Contact: jthteo@gmail.com
Copyright 2014
version 0.22

----------------------------------------------------------------
DO NOT DISTRIBUTE WITHOUT THE EXPRESS PERMISSION OF THE CREATORS
----------------------------------------------------------------

This software is an Alpha version. 

--------------------
 Instructions on use
--------------------

1) Unzip the folder.

2) The prototype collects data via NodeJS server. Therefore, the machine that runs this software needs to have NodeJS installed. Go to http://nodejs.org to download and install.

3) Open the index.html webpage in tremorDetect_PC_NHNN/main folder

4) To collect data, one should first run the node server before open the webpages, with this command line in Terminal or Command Prompt:
> cd /tremorDetect/main (to the directory where node.js is located)

> node.exe Postural.js for Postural tremor task
> node.exe Bradykinesia.js for Bradykinesia task
> node.exe Diadochokinesia.js Diadochokinesia task
> node.exe Action1.js for Action task 1
> node.exe Action2.js for Action task 2
> node.exe Action3.js for Action task 3
> node.exe Action4.js for Action task 4

5) Data would be recorded once user click the "start" button on each task page.

6) Remember to type "control+C" at the terminal to stop the node server and restart again every time you wish to re-collect data. Otherwise the new data would only be copied to the original file after the previous data instead of erase it.

7) Data is recorded in CSV files in the tremorDetecttremorDetect_PC_NHNN/main/Data folder. 


Analytics is not within the scope of this Alpha version, and is being developed by Dr James Teo.

