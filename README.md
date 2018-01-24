# Description
Deadlocked Processes Simulator is a C++ program that simulates the execution of 3 processes that will forever be stuck in a deadlock. Each process is looking for a particular person, but each process also can release a person another process is looking for. This program is purposely set up so that none of the processes will be able to ever find the person that another process could release theoretically, thereby creating a deadlock. This program creates an infinite loop on purpose to demonstrate what happens when multiple processes are deadlocked. Therefore, the only way to exit the program in a Linux environment is to press ctrl+c. This program is made-from-scratch and does not utilize the C++ Standard Template Library (STL).

# Compilation and Execution
* Compile: g++ deadlocked-processes-simulator.cpp
* Run Program: ./a.out

# Program Commands
* ctrl+c: Exits the program

# Technologies Used
* C++
* Linux
* PuTTY
* WinSCP

# Notes
* This program should be compiled and executed in a Linux Operating System environment.
* The only way to exit this program, when being run in Linux, is to press ctrl+c.