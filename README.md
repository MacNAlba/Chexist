ABOUT

A simple bash script to check if files or directories exist.

HOW TO USE

Save the file to a folder and cd to it, then execute with 

./chexist

The script needs arguments to run, each argument should be
the location of a file or directory you want to confirm the
existence of.

The script can accept many arguments and are separated by a space.
For example:

./chexist file1 file2 ~/Documents/ /etc/file4

The script will then return each item on a new line with a
message declaring whether the file exists or not, i.e.,:

The file file1 exists
file2 does not exist
The directory ~/Documents/ exists
/etc/file4 does not exist

The script can be added to a directory in the system PATH so
that it can be executed from anywhere and by simply typing:
chexist arg1 arg2 arg3
