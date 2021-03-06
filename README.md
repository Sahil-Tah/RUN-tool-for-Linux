# RUN Tool for Linux

A simple tool for beginners to directly 'compile' and 'run' their programs by directly running this script. 

Currently supports:
* C/C++
* Java
* Python (2 and 3 both) 
* Bash/Shell
* FLEX - Fast Lexical Analyzer Generator
 

## Getting Started

These instructions will get you a copy of the script up and running on your local machine for personal use.


### Installing

Follow the given step by step guide:

Download the repo first:
```
> git clone https://github.com/Sahil-Tah/RUN-tool-for-Linux.git
```

Change directory to the downloaded folder:
```
> cd RUN-tool-for-Linux/ 
```

Make script file executable: 
```
> chmod +x run
```

Now, copy the script in the path:
```
> sudo cp run /usr/bin/  
```

For mac users:
```
> sudo cp run /usr/local/bin/
```

You're all done! Run the command by typing:
```
> run <filename>
```

You need not have to type the whole filename, type the initial letter and then tab will handle the rest ;)

Have Fun!

### Edit

Now you can work with Python 2 and Python 3 altogether. By default it will run Python 3 but for python 2, simply add "-2" after the filename.
```
> run <filename> -2
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
