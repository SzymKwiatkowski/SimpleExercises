# Cmake exercise
In this exercise you must make project in which:
- after using cmake you will be able to compile program with source files in /src directory and /inc 
- color class must be having r, g, b private variables and have the default constructor along with 3 argument uint8_t constructor that will set every color value. Default constructor should set colors to (255,0,0)
- program must display colors in "colors.txt" text file written in format of "(r,g,b)" where as r, g and b are uint8_t variables that have values ranging from 0 to 255
- program can take 3 arguments:
  - "-r": red value
  - "-g": green value
  - "-b": blue value
- when inputs arguments are given you must display every color in "colors.txt" file with value of given argument e.g. when color (255,255,255) and -r 13 is given you must display (13,255,255)
- executable must be called color
---
To build a program you must run:
```bash
cmake -Bbuild
```
That will build cmake files in build/ directory

```
cmake --build build/
```
To compile your project.

Also you should be able to run your project when running:
```
./build/color
```