
===========================Processes and signals======================================

What is a PID?
A PID (i.e., process identification number) is an identification number that is automatically assigned to each process when it is created on a Unix-like operating system.

What is a Process?
A process can be thought of as an instance of a program in execution. We called this an ‘instance of a program’, because if the same program is run lets say 10 times then there will be 10 corresponding processes.

How to find a process’ PID?
 You can find the PID of a process with the 'top' command which  list the  current processes 
And you can also use the "ps " command to  check  for  the current PID of a process

How to kill a process.
we simply use the kill to  terminate a frozen or otherwise misbehaving program This command makes it possible to end a program that cannot otherwise be stopped except by rebooting

What is a signal?
A signal is an event generated by the UNIX and Linux systems in response to some condition. Upon receipt of a signal, a process may take action.
 And the signal are of two types  
which are:
Maskable: signals which can be changed or ignored by the user (e.g., Ctrl+C).
Non-Maskable: signals which cannot be changed or ignored by the user. These typically occur when the user is signaled for non-recoverable hardware errors

