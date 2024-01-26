# Student Management App

### 1. Download and Extract Zip
Download the Student-Management-App.zip file and unzip it to a location of your choice

### 2. Install Node.js
Go to the node.js website and install the recommended version here: https://nodejs.org

---> Make sure to say **yes** when the setup wizard asks if you want to install the additional packages. <---

### 3. Install Electron Packager
Open the terminal (command prompt) then run the command below to install the electron packager. 
```
npm install electron-packager -g
```

### 4. Build App
In the terminal, run the command below to build the app. Replace (app-directory) with the path to the extracted zip file (may look like "C:/Users/your-name/Downloads/Student-Management-App/WebApp-Copy")
```
electron-packager (app-directory) Student_Management_App --platform=win32 --arch=x64
```
If you want to create a shortcut to the app, take note of where it builds to (it may look like this "C:/Users/your-name/Student-Management-App-Win32-x64")

### 5. Create Desktop Shortcut (optional)
To create a desktop shortcut, right click on your desktop and click New>Shortcut.
You will be prompted for the location of the app's .exe file (it may look like this "C:/Users/your-name/Student-Management-App-Win32-x64/"). Scroll down and selcect the "Student-Management-App.exe" file. 

![image](https://github.com/2a3s4d/Student-Management-App/assets/84204533/89d4077b-ecce-48ae-87f1-79ca669f7683)
