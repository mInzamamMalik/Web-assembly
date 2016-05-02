# Web-assembly Hello World Program

###yahhooo i have compiled my first Web-Assembly program :-)


###Step 1:
goto here https://s3.amazonaws.com/mozilla-games/emscripten/releases/emsdk-1.12.0-full-32bit.exe and download emscripten and install omn your computer


###Step 2:
After Installation just create a folder any where in your pc and make a file named filename.cpp and write some C-Language code in it e.g:
```
// helloworld.cpp
  #include <stdio.h>
  int main() {
    printf("hello, world!\n");
    return 0;
  }

```

###Step 3:
open Command prmpt in same folder and write following command:

```
emcc filename.cpp -o output.html
```

###Step 4:
after executing this command you can see output.html file in your folder, just open this file with any latest browser like chrome or firefox

##you will see you C-Language code running in your browser :-)


dont forget to hit star button

Thank You <br> 
Inzamam Malik



