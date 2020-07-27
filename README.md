# Working_with_XV6
 For the reference we have implemented few features (system call cps() , system call clear() , system call shutdown() , sytem call foo(), system call nice()) for our own practical knowledge . Our team has designed a new scheduling algortihm for XV6 operating system . Instead of
default ROUND-ROBIN algorithm , our algorithm will allow the user to change the priority of the process according to his requirement . The state of the process which is currently in runnable state can be changed to running state as per the user requirement . The user can assign a default priority to any
process . The user can make any process go to sleep too . 
