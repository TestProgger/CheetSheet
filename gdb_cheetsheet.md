## GDB CheetSheet

### Как подготовить файл для GDB

#### Для C/C++
        gcc -g filename.c -o objname.out
        g++ -g filename.cpp -o objname.out
#### Для Python
        gdb -ex r --args python program_name.py <arguments>


### Использование GDB

        **list** - выводит исходный код программы и нумерует строчки
        
        **b(break) <arg>** - устанавливает точку останова на строчку под номером <arg> или на функцию под именем <arg>