# Assembly Code Test

C vs C++ compiled in assembly. The assembly code can be found in files with extension .s.\
\
The assembly code is generated using:
```
g++ -S $filename
```
\
The executable file is generated using:
```
g++ $filename -o $output
```
\
Tested on September 17, 2021 at 01.04\
System info:
- OS: openSUSE Tumbleweed 20210913 x86_64
- Kernel: Linux 5.14.2
- CPU: i5-10210U x86_64
- Compiler: g++ (gcc) 11.2.1 20210816