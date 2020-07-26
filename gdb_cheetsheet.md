## GDB CheetSheet

### Как подготовить файл для GDB

#### Для C/C++
        gcc -g filename.c -o objname.out
        g++ -g filename.cpp -o objname.out
#### Для Python
        gdb -ex r --args python program_name.py <arguments>


