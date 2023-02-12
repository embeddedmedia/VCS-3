# VCS-3
<img align="right" src=https://www.sundance.com/wp-content/uploads/docs/sundance_logo_105.png>
This repository stores the VCS-3 source code and documentation.

# Directory structure
[See the repository structure](https://github.com/SundanceMultiprocessorTechnology/VCS-3/blob/master/directorySctructure.md)

## VCS-3 documentation
All the pdf documents can be found in the [Documents](https://github.com/SundanceMultiprocessorTechnology/VCS-3/tree/main/Documents) folder. There is also relevant information inside each one of the repository folder and in the [wiki](https://github.com/SundanceMultiprocessorTechnology/VCS-3/wiki).

# Managing the Repository
## Meeting the requirements
```
$ sudo apt update
$ sudo apt upgrade -y
$ sudo apt install tree git -y
$ mkdir -p $HOME/Development
```
## Clone
using https
```
$ cd $HOME/Development
$ git clone https://github.com/SundanceMultiprocessorTechnology/VCS-3.git
```

OR using ssh
```
$ cd $HOME/Development
$ git clone git@github.com:SundanceMultiprocessorTechnology/VCS-3.git
```

## update
```
$ cd $HOME/Development/VCS-3
$ git pull
```

## commit (only available to authorised users)
```
$ cd $HOME/Development/VCS-3
$ ./push.sh
```


2023 (c) GPLv3 - Sundance Multiprocessor Technology Ltd.
