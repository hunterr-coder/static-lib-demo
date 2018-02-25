# static-lib-demo
A static library is a collection of object files.
 
 Let's create object files

  gcc -c int_maths.cpp

  gcc -c float_maths.cpp

  ar -rs <LIBNAME.a> int_maths.o float_maths.o  //a is the extension to the static library


  gcc -c main.cpp

  g++ -o MAINAPP main.o <LIBNAME.a>
