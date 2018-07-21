# Virtual File System
## What
A small project to try out Multiplatform C++ Development. It's a virtual filesystem for both Linux and Windows. The design of the code was fully thought out by me.  
**[SOURCE CODE](https://github.com/JonasDeM/VirtualFileSystem)**.

## Features
* Works exactly the same on Linux and Windows
* Search any file on your pc.
* Open, read, write to any file the program has access to.
* Search, Read from file in ZIP file (For now only zips with no compression
* Mainly aimed for usage inside another program. But i created a small test program with console commands.

## How
Made in C++, using Preprocessor #defines to only compile the code for the defined platform.

Made use of: Windows API (windows.h), POSIX operating system API (unistd.h) and c++11 features

## Who
On my own

## Acknowledgements:
Teachers [Pieter Vantorre](http://pietervantorre.com/) and [Julien Hamaide](https://www.linkedin.com/in/julienhamaide/) provided the idea to use Preprocessor #defines for multiplatform development.

## All commands
* searchPath
* filesInDir
* extInDir
* mountZip
* open
* openRead
* read
* write
* close
* specifySearch 
* resetSearch
* exit

 Find the barebones demo [here](https://github.com/JonasDeM/VirtualFileSystem/releases)