# Custom-Windows-ISO-Maker
A small project that can allow you to customize a windows ISO by adding programs into or removing programs in the Program Files and Pregram Files (x86) folders.


About:

   The .zip file contains many batch files and when executed in the right order will allow you to get access to the windows installation files.
  
Note: 

  I didn't do a great job explaining.
  
How to Use:
  
   First you will need a Windows ISO. Right click on your iso and click "Mount" in the selection menu. It should bring you to the files on the iso.
  Highlight everything and press ctrl+c.  Now you have to extract the .zip file. Right click it and press "Extract All" from the menu and press "Extact".
  Navigate to the "Install Files" and press ctrl+v.  Hopefully it will copy all files from the ISO to this folder.  Go up 1 folder and run "Start.bat".
  Wait a few seconds and when you get a prompt that says "press any key to continue", press any key.  It will open an explorer window. Now run 
  "Decompress and Mount.bat" as an administator.  Wait a few minutes and wait for the press any key prompt.  
  Then it will open a folder to the files from the installer.  From there you can add anything you want.  
  When you are done, run "Unmount and Compress.bat" as administrator.  
  This batch file takes a while to complete so just wait for the press any key prompt to appear.  When that is done you can navigate to "C:\ESD Workspace"
  and copy the "install.esd" file into the "sources" folder inside of the "Install Files" folder (Make sure you select replace files).  
  That is all I have provided.  You will need software likeIMGBurn to make an ISO out of the files.
