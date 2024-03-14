# Download VSCode on Windows
download Visual Studio Code from the main website: https://code.visualstudio.com/docs/?dv=win64user


# Download_GCC file
1. Download mingw-w64 (x86_64-posix-seh) file from this link : https://sourceforge.net/projects/mingw-w64/files/mingw-w64/
2. Extract the file from the downloaded zip file
3. Open up the downloaded mingw-w64 file and go into the file called 'bin' and copy the path address of bin folder
4. Search for 'edit the system environment variables' on Window Search feature
5. Go to 'Advanced' tab and click on 'Environment Variables..' button
6. Click on 'Path' under User Variables and click the 'Edit' button
7. Add a new path and paste the copied bin folder link
8. Click 'OK' and exit the properties pop ups


## To check if the GCC is properly installed
1. Open up VS Code application and click on 'Terminal' on the top left tabs, click on 'Configure Default Build Task'
2. If the search task bar auto pops up something like "C/C++ : gcc.exe build active file ......", click on that
3. A tasks.json file will appear on screen, as well on the left side of the application
4. You may close the tab of the j.son as the aplication is now connected to the GCC file

### Check through the Command Prompt application
1. Open up Command Prompt application by searching on Window Search feature
2. enter "g++ --version" and click enter
3. If it shows up the g++ file name, it means the GCC has been correctly installed on the hardware
