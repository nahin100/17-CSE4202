
# Setup

## 1.  Windows ##

   * ### Download glfw libray from https://www.glfw.org/download.html. Download *64-bit Windows binaries* from *Windows pre-compiled binaries*. ###  
   * ### Create **build** and **lib** folder in Code Repo. Put *glfw3.dll* from *lib-mingw-w64* folder of glfw library to **build** and **lib** folder.  ###
   * ### For C++ compiler and make, Download MSYS2 Package Manager from https://www.msys2.org/ . ###  
   * ### Run following commands in MSYS2 terminal: ```pacman -S base-devel``` and ```pacman -S gcc``` . ### 
   * ### add your bin folder (which includes g++.exe and make.exe) PATH (C:\msys64\usr\bin) of msys64 installation directory in your environment variable.
   * ### Run ```make win``` in Terminal. ###
   * ### ```.exe``` file will be in **build** folder. ###
   * ### if your code does not run, then you have to check openGL version by installing GLview from http://www.realtech-vr.com/home/glview . If your openGL version is below 3.3, then update windows. ### 
   * ### ***if compiler says it cannot find khrplatform.h, then put this file https://github.com/nahin100/17-CSE4202/blob/main/Lab0/include/khrplatform.h in *include* folder. Also, change header file statement from ```#include <KHR/khrplatform.h>``` to ```#include "khrplatform.h"``` in *glad.h* file in include folder*** ### 
   
​
## 2. Linux ##

   * ### Run following command in Terminal:  ```sudo apt-get install libglfw3-dev``` ###  
   * ### Create **build** and **lib** folder in Code Repo. ###
   * ### Run ```make linux``` in terminal. ###
   * ### executable file will be in **build** folder. ###
