# Quick n dirty guide to the shell

###First, let's sort out some jargon
The shell refers to your Command Line Interpreter (CLI). Mac users will use terminal as their CLI. Windows standard shell will be either cmd or powershell. You may also hear the shell refered to as bash or just command line. 

###What's it for?
We will use the command line to manage our local directories (fancy word for folders if you ask me). We will also use it to interact with git and our GitHub accounts. You can also use the command line to interact with python via the 'REPL' which is basically just an IDE right at the command line. This is mostly useful for simpler computation. However, if you are using an IDE such as PyCharm or Atom, you will use the command line to run your python scripts that you have written. And finally, you will use the command line for installing new python packages with pip or anaconda.

###Level one: navigating directories and files
When you open your shell, you will be at your 'home directory'. From here, you can display directories, subdirectories, and files. You can enter and exit directories, displaying their contents.
####Mac
`ls` -display the directories and/or files at the home directory level                                                   
`cd example directory` -navigate into the directory. from here, you can repeat your `ls` command to discover what is inside the directory. Etc.                                                                                     
`cd ..` -navigate one level up. essentially taking a step back.                                             
`cd` -go back to your home directory                                                                               
####Windows
`dir`-display the directories and/or files at the home directory level                               
`cd example directory` -navigate into the directory. from here, you can repeat your `ls` command to discover what is inside the directory. Etc.                                                                               
`cd ..` -navigate one level up. essentially taking a step back.                                                 
`cd` -go back to your home directory

###Level two: pip and anaconda installs
`pip install package_name` (might need to use `pip3 install`)                                                             
[Anaconda installs](https://conda.io/docs/using/pkgs.html)

###Level three: git
Check out [Matt's awesome git docs!](https://github.com/mattexx/learn-git)
