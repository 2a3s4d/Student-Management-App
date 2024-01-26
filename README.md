# Student Management App

### 1. Download and Extract Zip
Download the Student-Management-App.zip file and unzip it to a location of your choice

### 2. Install Node.js
Go to the node.js website and install the recommended version here: https://nodejs.org
<font color="green">Make sure to to say <font color="red">**yes**</font> when the setup wizard asks you if you want to install the additional packages.</font>

### 3. Install Electron Packager
Open the terminal (command propmt) then run the command below to install the electron packager. 
```
npm install electron-packager -g
```

### 4. Build App
In the terminal, run the command below to build the app. Replace (app-directory) with the path to the extracted zip file.
```
electron-packager (app-directory) Student_Management_App --platform=win32 --arch=x64
```
If you want to create a shortcut to the app, take note of where it builds to (it may look like this "C:/Users/your-name/Student-Management-App-Win32-x64)

### 5. Create Desktop Shortcut (optional)
To create a desktop shortcut, right click on your desktop and click New>Shortcut.
This will create a prompt asking for the location of the app you are creating a shortcut for. The .exe file you need is in the directory the app was built to and is called "Student_Management_App.exe". Double click this file and create the short cut.
