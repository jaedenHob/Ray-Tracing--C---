# Ray Tracer (C++)

## General Info
I have a interest in things relating to computer graphics. Ray tracing is a topic of interest to me for a while. I'm working on 
something covering raytracing but to be implemented via Webgl, but there are issues due to not having a GPU that can handle 
the current workload. So until I can better understand how I can optimize it, this project is to follow along the tutorial and learn
the concepts and math behind.

## Setup
first compile the code to then create an executable. I usually call the executable main.\
Then run the executable with ./[executable_name].\
By default running this the program will create an image file called image.png and will always overwrite it if one already exists\
You can also direct output to create a ppm file with `./main >> file_name.ppm` and then google a ppm viewer to see it that way.

```
$ g++ main.cpp -o main
$ ./main >> file_name.ppm
```

## Gallery

### lambertian sphere
![image](https://github.com/jaedenHob/Ray-Tracing--C---/assets/92416232/50ca0583-1850-49f4-8272-039be98a846e)

### removed shadow acne
![image](https://github.com/jaedenHob/Ray-Tracing--C---/assets/92416232/c17361ee-f44a-4c57-b777-15078e760669)

### metal with a slightly rough surface
![image](https://github.com/jaedenHob/Ray-Tracing--C---/assets/92416232/bbbf8f59-4b11-467b-b37a-fc60ffde8d7b)

### glass sphere
![image](https://github.com/jaedenHob/Ray-Tracing--C---/assets/92416232/f419b2de-2a3e-44bd-a135-6152dac48253)

### final render
![image](https://github.com/jaedenHob/Ray-Tracing--C---/assets/92416232/9e1c3173-f7e2-467e-b138-2f7d0582f98c)
