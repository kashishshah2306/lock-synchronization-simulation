Lock Synchronization Simulation

A browser-based Operating Systems project that visually demonstrates how synchronization mechanisms work in multithreaded environments.

This simulator helps users understand concepts like mutual exclusion, critical sections, race conditions, starvation, and priority inversion through real-time thread visualization and interactive execution.

Features
Mutex Lock Simulation
Semaphore Simulation
Spinlock Simulation
Read-Write Lock Simulation
Peterson’s Algorithm Simulation
Race Condition Demonstration
Thread Activity Timeline
Lock Visualizer
Wait Queue Visualization
Shared Counter Tracking
Event Logs and Statistics Panel
Adjustable Thread Count and Speed
Technologies Used
HTML5
CSS3
JavaScript
Canvas API
Async/Await for concurrency simulation
Operating System Concepts Covered
Mutual Exclusion
Critical Section Problem
Race Conditions
Busy Waiting
Context Switching
Deadlock Concepts
Starvation
Priority Inversion
Thread Synchronization
Project Architecture

The project is divided into multiple layers:

Frontend/UI Layer
Thread Arena
Lock Visualizer
Timeline
Event Logs
Statistics Panel
Simulation Engine
Thread Management
State Updates
Queue Management
Visualization Updates
Synchronization Layer
Mutex
Semaphore
Spinlock
Read-Write Lock
Peterson’s Algorithm
Shared Resource Layer
Shared Counter
Lock State
Wait Queue
Algorithms Implemented
Mutex

Allows only one thread inside the critical section at a time.

Semaphore

Allows multiple threads to access shared resources depending on semaphore count.

Spinlock

Uses busy waiting where threads continuously check for lock availability.

Read-Write Lock

Allows multiple readers but only one writer at a time.

Peterson’s Algorithm

A software-based mutual exclusion algorithm for two threads.

How to Run
Clone the repository
git clone <your-repository-link>
Open the project folder
Run using Live Server or open index.html directly in the browser
Educational Purpose

This project was created to make Operating System synchronization concepts easier to understand through visualization and interaction instead of only theoretical explanations.

Future Enhancements
Deadlock Simulation
Monitor and Barrier Synchronization
Multi-Core CPU Simulation
Real-Time Performance Analytics
Process Scheduling Visualization

