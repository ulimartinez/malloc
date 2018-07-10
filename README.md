# malloc
This is my own implementation of malloc in C. It can use a first fit allocation scheme or a next fit allocation.

There are two different testers as some implementations of printf
call malloc to allocate buffer space. This causes test1 to behave
improperly as it uses myAllocator as a malloc replacement. In this
case myAllocatorTest1 will function correctly. The only difference
between the programs is that test1 uses myAllocator as a malloc
replacement and myAllocatorTest1 uses myAllocator directly.

Makefile: a fairly portable "makefile", targets "all" and "clean"

To compile: 
 `$ make `
To clean:
 `$ make clean`

