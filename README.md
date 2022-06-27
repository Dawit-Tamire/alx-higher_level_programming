
lenovo@DESKTOP-KIQPCB1 MINGW32 ~
$ ssh 0375ae25d622@0375ae25d622.9b101674.alx-cod.online
0375ae25d622@0375ae25d622.9b101674.alx-cod.online's password:
root@0375ae25d622:/# git clone https://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@github.com/Dawit-Tamire/alx-higher_level_programming.git
Cloning into 'alx-higher_level_programming'...
warning: You appear to have cloned an empty repository.
root@0375ae25d622:/# ls
0x12-singly_linked_lists       Betty  lib     opt     simple_shell    tmp
alx-higher_level_programming   bin    lib32   printf  simple_shell_2  usr
alx-low_level_programming      boot   lib64   proc    srv             var
alx-pre_course                 dev    libx32  root    sys             zero_day
alx-system_engineering-devops  etc    media   run     Test_files
alx-zero_day                   home   mnt     sbin    Test_files_2
root@0375ae25d622:/# cat > README.md
alx-higher_level_programming
root@0375ae25d622:/# mv README.md /alx-higher_level_programming
root@0375ae25d622:/# cd /alx-higher_level_programming
root@0375ae25d622:/alx-higher_level_programming# ls
README.md
root@0375ae25d622:/alx-higher_level_programming# git clone https://github.com/j-tyler/holbertonschool-higher_level_programming
Cloning into 'holbertonschool-higher_level_programming'...
remote: Enumerating objects: 1141, done.
remote: Total 1141 (delta 0), reused 0 (delta 0), pack-reused 1141
Receiving objects: 100% (1141/1141), 182.36 KiB | 1.67 MiB/s, done.
Resolving deltas: 100% (636/636), done.
root@0375ae25d622:/alx-higher_level_programming# ls
holbertonschool-higher_level_programming  README.md
root@0375ae25d622:/alx-higher_level_programming# cp ^C
root@0375ae25d622:/alx-higher_level_programming# cp /holbertonschool-higher_level_programming/* .
cp: cannot stat '/holbertonschool-higher_level_programming/*': No such file or directory
root@0375ae25d622:/alx-higher_level_programming# Connection reset by 44.202.46.43 port 22

lenovo@DESKTOP-KIQPCB1 MINGW32 ~
$ ssh 0375ae25d622@0375ae25d622.9b101674.alx-cod.online
0375ae25d622@0375ae25d622.9b101674.alx-cod.online's password:
root@0375ae25d622:/# ls
0x12-singly_linked_lists       Betty  lib     opt     simple_shell    tmp
alx-higher_level_programming   bin    lib32   printf  simple_shell_2  usr
alx-low_level_programming      boot   lib64   proc    srv             var
alx-pre_course                 dev    libx32  root    sys             zero_day
alx-system_engineering-devops  etc    media   run     Test_files
alx-zero_day                   home   mnt     sbin    Test_files_2
root@0375ae25d622:/# cd /alx-higher_level_programming
root@0375ae25d622:/alx-higher_level_programming# ls
holbertonschool-higher_level_programming  README.md
root@0375ae25d622:/alx-higher_level_programming# cp /holbertonschool-higher_level_programming/ .
cp: cannot stat '/holbertonschool-higher_level_programming/': No such file or directory
root@0375ae25d622:/alx-higher_level_programming# cp holbertonschool-higher_level_programming/ .
cp: -r not specified; omitting directory 'holbertonschool-higher_level_programming/'
root@0375ae25d622:/alx-higher_level_programming# cp -r holbertonschool-higher_level_programming/ .
cp: 'holbertonschool-higher_level_programming/' and './holbertonschool-higher_level_programming' are the same file
root@0375ae25d622:/alx-higher_level_programming# cd holbertonschool-higher_level_programming
root@0375ae25d622:/alx-higher_level_programming/holbertonschool-higher_level_programming# cp * ../alx-higher_level_programming
cp: target '../alx-higher_level_programming' is not a directory
root@0375ae25d622:/alx-higher_level_programming/holbertonschool-higher_level_programming# cp * ../alx-higher_level_programming/
cp: target '../alx-higher_level_programming/' is not a directory
root@0375ae25d622:/alx-higher_level_programming/holbertonschool-higher_level_programming# cp * ../
cp: -r not specified; omitting directory '0x00-python-hello_world'
cp: -r not specified; omitting directory '0x01-python-if_else_loops_functions'
cp: -r not specified; omitting directory '0x02-python-import_modules'
cp: -r not specified; omitting directory '0x03-python-data_structures'
cp: -r not specified; omitting directory '0x04-python-more_data_structures'
cp: -r not specified; omitting directory '0x05-python-exceptions'
cp: -r not specified; omitting directory '0x06-python-test_driven_development'
cp: -r not specified; omitting directory '0x07-python-classes'
cp: -r not specified; omitting directory '0x08-python-more_classes'
cp: -r not specified; omitting directory '0x09-python-everything_is_object'
cp: -r not specified; omitting directory '0x0A-python-inheritance'
cp: -r not specified; omitting directory '0x0B-python-input_output'
cp: -r not specified; omitting directory '0x0C-SQL_introduction'
cp: -r not specified; omitting directory '0x0D-SQL_more_queries'
cp: -r not specified; omitting directory '0x0E-python-object_relational_mapping'
root@0375ae25d622:/alx-higher_level_programming/holbertonschool-higher_level_programming# cp -r * ../
root@0375ae25d622:/alx-higher_level_programming/holbertonschool-higher_level_programming# cd ..
root@0375ae25d622:/alx-higher_level_programming# ls
0x00-python-hello_world              0x09-python-everything_is_object
0x01-python-if_else_loops_functions  0x0A-python-inheritance
0x02-python-import_modules           0x0B-python-input_output
0x03-python-data_structures          0x0C-SQL_introduction
0x04-python-more_data_structures     0x0D-SQL_more_queries
0x05-python-exceptions               0x0E-python-object_relational_mapping
0x06-python-test_driven_development  holbertonschool-higher_level_programming
0x07-python-classes                  README.md
0x08-python-more_classes
root@0375ae25d622:/alx-higher_level_programming# rm -rf holbertonschool-higher_level_programming/
root@0375ae25d622:/alx-higher_level_programming# ls
0x00-python-hello_world              0x08-python-more_classes
0x01-python-if_else_loops_functions  0x09-python-everything_is_object
0x02-python-import_modules           0x0A-python-inheritance
0x03-python-data_structures          0x0B-python-input_output
0x04-python-more_data_structures     0x0C-SQL_introduction
0x05-python-exceptions               0x0D-SQL_more_queries
0x06-python-test_driven_development  0x0E-python-object_relational_mapping
0x07-python-classes                  README.md
root@0375ae25d622:/alx-higher_level_programming# cat README.md
<img src="https://www.holbertonschool.com/assets/holberton-logo-1cc451260ca3cd297def53f2250a9794810667c7ca7b5fa5879a569a457bf16f.png" alt="Holberton logo">
# Assignment Solutions from [Justin Marsh](https://twitter.com/dogonthecircuit)

**Welcome to High-Level Programming!**

This repository holds my assignment solutions from the high-level programming
track at [Holberton School](https://www.holbertonschool.com).

**Whats in here?**

Each directory contains my code as I progressed through the Holberton program.
Folders contain assignments on a given topic, each with different specifications.
These assignments were mostly small-scale, with one day completion times for each folder.
As such, the code here are samples of my work as time progressed. If
you are interested in my work in larger-scale complete programs,
see any of these week long projects that I have worked on:

[AirBnB Clone](https://github.com/j-tyler/AirBnB_clone)

root@0375ae25d622:/alx-higher_level_programming# cat > README.md
alx-higher_level_programming
