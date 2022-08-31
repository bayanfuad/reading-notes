# The Command Line!
Linux has a graphical user interface and it works pretty much like the GUI's on other systems such as Windows and OSX
The command line is an interesting beast, we can have several command lines open and doing different tasks in each at the same time. We can also easily jump back to the GUI when it suits us.
A command line, or terminal, is a text based interface to the system,Within a terminal you have what is known as a shell. This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands.
# Basic Navigation!
The first command is pwd which stands for Print Working Directory.It tells you what your current or present working directory is.
The second command is ls to see what is inside the present directory.
Runnibng ls with a single command line option ( -l ) which indicates we are going to do a long listing. A long listing has the following:
-First character indicates whether it is a normal file ( - ) or directory ( d )
-Next 9 characters are permissions for the file or directory (we'll learn more about them in section 6).
-The next field is the number of blocks (don't worry too much about this).
-The next field is the owner of the file or directory (ryan in this case).
-The next field is the group the file or directory belongs to (users in this case).
-Following this is the file size.
-Next up is the file modification time.
-Finally we have the actual name of the file or directory.
Running ls with a command line argument ( /etc ). When we do this it tells ls not to list our current directory but instead to list that directories contents.
Running ls with both a command line option and argument. As such it did a long listing of the directory /etc.
## Absolute and Relative Paths
Absolute paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )

Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.
cd command: to navigate through files.


