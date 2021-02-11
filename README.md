# tcalc

This program finds a suitable equation & calculates the requested property of the triangle using it using known properties of the triangle.
This program is in stable currently as all known bugs fixed (report any as an issue) and all wanted functionality implemented (more may come later).  

### Downloads:  
Instead of compiling you can download a pre-made binaries from /binaries.
If you don't know what instruction set your computer used download the corresponding x86 file for your OS.

============================================================================================================
| Source OS | Target OS | Target architecture | Prerequisites | Command                                    |
============================================================================================================
|  Linux    |  Linux    |  x86                |  g++          |  g++ -m32 main.cpp -o tcalc-Linux_x86      |
|           |           |----------------------------------------------------------------------------------|
|           |           |  x86-64             |  g++          |  g++ -m64 main.cpp -o tcalc-Linux_x86-64   |
|           |           |----------------------------------------------------------------------------------|
|           |           |  ARM                |  g++          |                                            |
|           |           |----------------------------------------------------------------------------------|
|           |           |  RISC               |  g++          |                                            |
|           |           |----------------------------------------------------------------------------------|
|           |  Windows  |  x86                |  g++          |                                            |
|           |           |----------------------------------------------------------------------------------|
|           |           |  x86-64             |  g++          |                                            |
|           |           |----------------------------------------------------------------------------------|
|           |           |  ARM                |               |                                            |
|           |           |----------------------------------------------------------------------------------|
|           |           |  RISC               |               |                                            |
|           |           |----------------------------------------------------------------------------------|
|           |  MacOS    |  x86                |               |                                            |
|           |           |----------------------------------------------------------------------------------|
|           |           |  x86-64             |               |                                            |
|           |           |----------------------------------------------------------------------------------|
|           |           |  ARM                |               |                                            |
|           |           |----------------------------------------------------------------------------------|
|           |           |  RISC               |               |                                            |
|           |           |----------------------------------------------------------------------------------|
|  Windows  |  Linux    |  x86                |               |                                            |
|           |           |----------------------------------------------------------------------------------|
|           |           |  x86-64             |               |                                            |
|           |           |----------------------------------------------------------------------------------|
|           |           |  ARM                |               |                                            |
|           |           |----------------------------------------------------------------------------------|
|           |           |  RISC               |               |                                            |
|           |           |----------------------------------------------------------------------------------|
|  MacOS

### Use:  
When the program load's enter in any known value's for angle's or side's on the triangle as well the side or angle to be calculated. If it is possible based off of that information it will calculate the side or angle specified by working out the equation to use and then entering value's into the formula.  
Versions of the code compiled for linux accept arguments, use -h when running the program to print out a help file.  

Note - This program cannot calculate the value of a side or angle that is required to have the right information to calculate the requested side or angle.
