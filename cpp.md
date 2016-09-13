#Important c++ points
Good Links
(Learncpp) [http://www.learncpp.com]
##Header Files
-----------------------------------------------------
###1. Header Guard
Disallows re-inclusion of the same header file from the same file
```
// This is start of the header guard.  ADD_H can be any unique name.  By convention, we use the name of the header file.
#ifndef ADD_H
#define ADD_H
 
// This is the content of the .h file, which is where the declarations go
int add(int x, int y); // function prototype for add.h -- don't forget the semicolon!
 
// This is the end of the header guard
#endif
```
