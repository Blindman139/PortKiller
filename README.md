# PortKiller
Simple Program to kill Port by name , PID , Address or substring of same in windows OS

Greeting Human,

If you are tired of closing the legendary :8080 port while web development, then this might help someone...

This JAR contains...

1) Class : Named PortKiller under application package
2) Method : KillThePort(String port) {The murderer}

**Usage:**

**Method (1)**

Import the class and then call the method.

Example:

import application.PortKiller;

public static void main(String[] args){
    PortKiller.KillThePort("8080");
    /*
    * Do other stuff here
    * Add your application logic
    */
}



**Method (2)**

Create executable file provide port Id as argument.

Example :

Provide port id 8080 as first argument to exe
///////////////////////////////////////////////////
//////////////////////////////////////////////////
**EXTRA**
Don't get limited to 8080. You can provide any substring of the address to terminate it.

Example :

For Processes
  Proto  Local Address          Foreign Address        State           PID
  TCP    0.0.0.0:135            0.0.0.0:0              LISTENING       1000
  TCP    0.0.0.0:445            0.0.0.0:0              LISTENING       4
  TCP    127.0.0.1:28390        0.0.0.0:0              LISTENING       4368
  
  You can pass "127.0.0.1:28390" to terminate PID 4368
  You can even pass PID itself to terminate.
  
  **Danger : Never try to pass LISTENING**
  (I never tried but if you ever pass it then tell me what happens afterwards. Contact is given below)
  
  Mac, Linux and other OS guys... Sorry this is not for you. But it can be. So, Contact is given below.
  
Parth Vaghani
parth395006vpj@gmail.com
(Blindman)

