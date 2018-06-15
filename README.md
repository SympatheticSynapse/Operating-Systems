# Operating Systems

# Purpose
Personal notes and code on operating system concepts

## Virtualization
* Virtualization - Time sharing the CPU
* Mechanisms:
  * Policies
    * Scheduling Policy 

### Process
#### Elements of a process
* Address Space - Memory the process can access
* CPU registers 
  * PC/IP - Program Counter/Instruction Pointer
  * SP/FP - Stack Pointer/Frame Pointer

#### Process API
* Create - Create a new process
* Destroy - Destroy a process forcefully
* Wait - Wait for another process to stop running before continuing 
* Status - Obtain status about the process

#### Process States
* Initial - Potential state of process during creation
* Running - Process is running on a processor core 
* Ready - The process is ready to run
* Blocked - The process is waiting on an external action
* Zombie/Final - Potential state of process when exiting 

## Scheduling

## Task/Context Switching

## Memory Management

## Interrupts

## Semaphores

## Inter Process Communication

## Terms
  * PID - Process Identifier
  * Process - Running program

## Reference
* http://pages.cs.wisc.edu/~remzi/OSTEP/
