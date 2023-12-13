# openGl-configuration

Note: if you have installed g++ and cant find its location then 
open command terminal
type: where g++           // this command will show location of g++

Step 1:
download glfw
download glew from sourceforge
download msys64

Step 1:
extract all folder and put in c:\\ drive   //don't put in any folder of c:\\ drive put in root folder of c:\\




Step 2:
install msys64 \n
add this path in environment variable: C:\msys64\ucrt64\bin

step 3:
type this command in msys terminal: 
$ pacman -Suy
then type :
$ pacman -S --needed base-devel mingw-w64-x86_64-toolchain

install everything default              // for default install Press Y

step 4:
create a folder in workspace vscode and put name : .vscode
put all three files except setts.json from my repository to .vscode folder


Step 4:
then go to folder location: C:\glfw-3.3.8.bin.WIN64\glfw-3.3.8.bin.WIN64\lib-mingw-w64
select and copy all files 

then paste all files in folder: C:\msys64\mingw64\lib 
also paste all files in folder: C:\msys64\ucrt64\lib


Step 4:  after doing above all process create 
