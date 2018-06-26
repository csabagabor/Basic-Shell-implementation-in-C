# Basic-Shell-implementation-in-C
Basic Shell implementation in C  
Feautures:  
-piped commands(more than 1 pipe allowed)  
-asyncronous commands(more than 2 asyncronous commands allowed)  
-redirect output of command to file  
-append output of command to file  
-redirect file to input of a command  
-supports some internal commands such as cd, echo, pwd, though it does not support them all  

**Some examples**  
It has a bultin help asseccible by the typing 'help'
![bandicam 2018-06-26 13-29-20-004](https://user-images.githubusercontent.com/37183688/41937889-696b75b6-7946-11e8-818e-a32b9da75f51.jpg)

Output redirection:  
![bandicam 2018-06-26 13-33-47-147](https://user-images.githubusercontent.com/37183688/41937883-6878094e-7946-11e8-86e4-e0652572e8bb.jpg)  
Append output to file:  
![bandicam 2018-06-26 13-34-10-542](https://user-images.githubusercontent.com/37183688/41937884-68a55ae8-7946-11e8-8a52-ef56965d11af.jpg)  
Input redirection:   
![bandicam 2018-06-26 13-34-44-556](https://user-images.githubusercontent.com/37183688/41937886-68d47b20-7946-11e8-9177-37c94651e3a4.jpg)  
pwd works as expected:  
![bandicam 2018-06-26 13-35-02-608](https://user-images.githubusercontent.com/37183688/41937887-690768aa-7946-11e8-8f9f-79f45096bc43.jpg)  
To exit the program, type 'exit'..  
![bandicam 2018-06-26 13-35-09-015](https://user-images.githubusercontent.com/37183688/41937888-69352308-7946-11e8-9789-487eeb79b041.jpg)  
Simple external command:  
![bandicam 2018-06-26 13-29-44-909](https://user-images.githubusercontent.com/37183688/41937890-69d40522-7946-11e8-88e7-a86003d17fd3.jpg)  
Basic example with 2 piped commands:  
![bandicam 2018-06-26 13-30-08-132](https://user-images.githubusercontent.com/37183688/41937893-6a000cf8-7946-11e8-95bd-0e8792d62875.jpg)  
2 Asyncronous commands:  
![bandicam 2018-06-26 13-31-02-726](https://user-images.githubusercontent.com/37183688/41937895-6a8615b4-7946-11e8-9790-cc0bcc5a59b6.jpg)  
Usage of cd :  
![bandicam 2018-06-26 13-31-22-979](https://user-images.githubusercontent.com/37183688/41937896-6ab5cb38-7946-11e8-8bd3-2989c5e63e1c.jpg)  
Creating files and directories and deleting them works as well:  
![bandicam 2018-06-26 13-32-27-818](https://user-images.githubusercontent.com/37183688/41937897-6ae5c202-7946-11e8-9d8a-d73172213974.jpg)  
![bandicam 2018-06-26 13-32-58-506](https://user-images.githubusercontent.com/37183688/41937898-6b1c5cf4-7946-11e8-9cce-2eaec36bfa80.jpg)  
