CG-scanConverter
================

Produce a working scan converter

* The API calls are in rend.cpp

* Each pixel is interpolated for Z and do Z-buffer testing before writing on to the Display

* The result images are made into a 256x256 window to save disk space.

-------------------------------------------------------------------------------

- Gz.h : Global definitions 

- Application2.cpp : new application that calls for your rend.cpp functions 

- rend.cpp : new skeleton file with API definition and comments 

- pot4.screen.asc : the Utah teapot triangle data transformed for scan conversion 

- pot4.ppm : the result of running "app2 <pot4.screen.asc >pot4.ppm"  

-------------------------------------------------------------------------------