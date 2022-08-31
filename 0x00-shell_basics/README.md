pwd for printing absolute pathname of present working directory
ls for printing content list of current working directory
cd ~ for changing working directory to home directory
ls -l for displaying current working directory in a long list format
ls -la for displaying content of a directory including hidden files
ls -lan for displaying content of  directory in long format with user and group IDs displayed numerically also including hidden files
mkdir //tmp/my_first_directory to create a directory named my_first_directory in tmp directory
mv //tmp/betty //tmp/my_first_directory to move file betty in tmp to my_first directory in tmp
rm //tmp/my_first_directory/betty to remove file betty from my_first_directory in tmp directory
rmdir //tmp/my_first_directory to remove my_first_directory from tmp directory
cd - to move from current directory to previous one
ls -la . .. /boot to show hidden files even ones starting with period and in long format from working directory through parent directory to /boot
file /tmp/iamafile to show the type of file named iamafile in tmp directory
ln -s /bin/ls __ls__ Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
cp -u *.html .. Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
mv [[:upper:]]* /tmp/u Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.


