# OS-Tasks
Task - 1
Create directory in your home directory named Top Secret.
Because directory name has a white space, it must be esacped with "\", so full parameter for command should be like: "Top\ Secret", also when accessing this folder, you must escape whitespace "cd Top\ Secret"
Save the content of /bin directory to text file named bin.txt
Make hidden copy of bin.txt and move it to Top Secret directory.
Hidden file can be made appending "." prefix to it's name, for example if file's name is "abc.txt", it must be renamed to ".abc.txt"
Hidden file will not be shown in "ls", unless "-a" is provided
Hidden file can still be accessed and modified, for example, to read a hidden file, following command can be used: "cat .abc.txt

Task - 2
Write script that calculates and writes the multiplication of two numbers result and writes to file.
Write script that outputs the n-th text line of text file.
Write script that outputs the lines of text file starting with the n-th line, ending with the m-th line.
Write script that removes the n-th text line from the text file.

Task - 3
User enters two names of files. Write a script that checks which file has more lines.
User enters two names of directories. Write a script that checks which directory has more files.

Task - 4
Write a script that:
lists all directories in working directory;
determines which file is the largest one in the current directory;
determines which folder has the highest amount of files.
