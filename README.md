# Triple_seC
Cyber C programming Course (CCC) to introduce programming to those who are cyber inclined. The main focus of this course is the use of the C programming language, though many of the lessons here will be useful to those of any programming language. Overall the point of these lessons is to provide a form of guidance to those learning programming, with no intention of covering a particularly wide breadth or depth of knowledge. It's encouraged to take what is discussed here and explore further as needed and chase your interests.

At this point, these lessons are very much a work in progress. For suggestions, feedback, and any errors detected, please reach out to the point of contact:
Scott Manifold <shm.qed@gmail.com>

## Table of Contents
The current overview of the course should match up to the following structure.
1. Introduction (In Progress)
	- Basic Git
	- Basic Compiling
	- Basic Make
 	- Basic CMake
   	- Coding Style
2. Core C functionality (In Progress)
    - Datatypes and Arrays
    - Conditionals and Switches
    - Loop Control
    - Functions
    - Input/Output
    - Files and Reading/Writing
    - Pointers
    - Memory Management
    - Structs and Enums
    - Basic Testing and Error Handling
Part 1 Practicals (In Progress)
	- Terminal ACFT Calculator
	- Brute Force Passwords
3. Introduction to Data Structures (In Progress)
   	- Multidimensional Arrays
   	- Stacks and Queues
   	- Linked Lists
   	- Trees
   	- HashSets and HashMaps
   	- Heaps
4. Basic Algorithm Examples (In Progress)
    - Recursion
    - Searching
    - Spanning Trees and Networks
    - Bit Manipulation
    - Dynamic Programming
Part 2 Practicals (In Progress)
	- Path Finding a Maze
	- Building a LRU Cache
5. More Advanced Concepts (In Progress)
    - Socket Programming
    - Asynchronous Programming
    - Threaded Programming with pthreads
    - Threaded Programming with C11 threads
    - Threaded Programming Considerations
6. Programming Ecosystem (In Progress)
    - Regular Expressions
    - Debugging
    - Linters
    - Commenting and Documenting Code
    - Testing Code
    - Popular Linux Libraries
    - CMake (part 2)
Part 3 Practicals (In Progress)
	- Threaded Web Server
	- ???
Final Project (In Progress)
Side Modules (In Progress)
	- Basic SQL with SQLite
	- Integration with Assembly
	- Integration with C++
	- Integration with Python
	- Cross-Compiling

## Prerequisites
To get started with these lessons we need to set up a text editor, a compiler, and a build system. There is also an implicit assumption that these lessons are conducted using a Linux based system. That said, almost everything should carry over to other systems with little difficulty. 
The choice of text editor is a personal choice and as long as you can edit your files, any choice is valid. For those who are new and struggling to make a choice, something like Visual Studio Code is a great choice for beginners.
For the choice of compiler, there is a great degree of flexibility, the main thing is that it should implement C11 standards to make sure we can build a more modern C code base. For those who are new and unsure, you can expect `gcc` or `clang` to be solid choices. 
As for build systems with C, there are a variety of choices out there. And for our simple examples, one can get by using straightforward terminal commands. However for the sake of learning and experience, there is a goal using simple make and cmake commands throughout some of the lessons. Therefore it is encouraged to get these tools.
The following commands should provide the minimum necessary to get working on these lessons on a debian-based linux system.
```bash
sudo apt install git make cmake build-essential vim
```
TODO: In the future there is a goal to provide a docker file to set up a basic development environment.
