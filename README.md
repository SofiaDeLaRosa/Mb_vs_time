<h1 align="center" style="color:red;"> Distributed Computing2022 </h1>

# Mb_vs_time

Second Exam of the Distributed Computing 2022-2 class, taught by [Dr. Victor de la Luz](https://github.com/itztli) (<vdelaluz@enesmorelia.unam.mx>) at *[Universidad Nacional Autónoma de México](https://www.unam.mx/)* (National Autonomous University of Mexico | UNAM) [http://www.gicc.unam.mx/](http://www.gicc.unam.mx/), in its *[Escuela Nacional de Estudios Superiores, Unidad Morelia](https://www.enesmorelia.unam.mx/)* (National School of Superior-Level Studies, *Morelia* Campus | ENES).
 
 GNU/GPL License 3.0
 
 Author: 
 [Sofia De La Rosa](https://github.com/SofiaDeLaRosa) (<chapatulita@gmail.com>)
 
 ## Introduction

The *[subprocess](https://www.bogotobogo.com/python/python_subprocess_module.php)* module allows spawn new processes, connect to their input/output/error pipes and obtain their return codes. It offers a higher-level interface than other modules, and is intended to replace the following functions:

- os.system()
- os.spawn*()
- os.popen*()
- popen2.*()
- commands.*()
 
 ## Metodology

 We calculate the latency between with WEB SERVER and DATA SERVER and then, We graph it: x-axis = size(Mb) and y-axis = time(s).
 
Libraries

- [Python3](https://www.python.org/downloads/)
- [Matplotlib](https://matplotlib.org/)

 ## Requeriments

- We did SSH key authentication with WEB SERVER and DATA SERVER. <br>
- We calculate the latency between with WEB SERVER and DATA SERVER. <br>
- We use scp to copy files from one server to another. <br>
- We put the last bit in a buffer. <br>
- We graph the latency: x-axis = size(Mb) and y-axis = time(s).
 
 ## Running
 
We have to clone the repository, create a commit, make a pull request. The code is in the filles called pingmb.py and testpingmb.py.
To execute them, we it we must do the following instructions from a Linux terminal: 

pingmb.py <ip_end> <Mb>

and
 
testpingmb.py <Mb_begin> <Mb_end> <Mb_jump> <ip_end>
 
 ## Results
 
- We did SSH key authentication with WEB SERVER and DATA SERVER. <br
                                                                     
 ![alt text][(https://github.com/SofiaDeLaRosa/Mb_vs_time/blob/main/3074.jpg?raw=true) <br>
 ![alt text][(https://github.com/SofiaDeLaRosa/Mb_vs_time/blob/main/3075.jpg?raw=true) <br>
 
- We calculate the latency between with WEB SERVER and DATA SERVER. <br>
- We use scp to copy files from one server to another. <br>
- We put the last bit in a buffer. <br>
 
 ![alt text][(https://github.com/SofiaDeLaRosa/Mb_vs_time/blob/main/3076.jpg?raw=true) <br>
 ![alt text][(https://github.com/SofiaDeLaRosa/Mb_vs_time/blob/main/3077.jpg?raw=true) <br>
 ![alt text][(https://github.com/SofiaDeLaRosa/Mb_vs_time/blob/main/3078.jpg?raw=true) <br>
 ![alt text][(https://github.com/SofiaDeLaRosa/Mb_vs_time/blob/main/3079.jpg?raw=true) <br>
 
- We graph the latency: x-axis = size(Mb) and y-axis = time(s). <br>
 
  ![alt text](https://github.com/SofiaDeLaRosa/Mb_vs_time/blob/main/latency.png) 
 
 ## References 
https://docs.python.org/3/library/subprocess.html
https://classroom.google.com/u/0/c/NDY4ODc2ODY4MTA2?hl=es
https://www.bogotobogo.com/python/python_subprocess_module.php
https://recursospython.com/guias-y-manuales/subprocess-creacion-y-comunicacion-con-procesos/
