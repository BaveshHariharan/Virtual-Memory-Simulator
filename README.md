# Virtual-Memory-Simulator
C program simulating virtual memory with LRU page replacement
This project simulates a simple virtual memory management system using C. It models processes, page tables,
and a small RAM with local and global Least Recently Used (LRU) page replacement policies. The program reads 
process requests from an input file, loads and evicts pages accordingly, and prints final page tables and RAM states to an output file.

WHAT THE PROGRAM DOES: 
  Simulates 4 processes with their own page tables.
  Manages RAM as 16 memory slots divided into 8 frames.
  Implements local and global LRU page replacement to handle page faults.
  Reads process requests from in.txt and outputs page tables and RAM contents to out.txt.

SKILLS AND KNOWLEDGE DEMONSTRATED: 
  Proficient in C structures, pointers, and arrays.
  Implementation of page replacement algorithms (LRU).
  Understanding of virtual memory, paging, and process simulation.
  File I/O handling and formatted output.
