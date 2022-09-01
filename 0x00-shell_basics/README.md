#!SHELL_BASIC_DESCRIPTION


Task   0:The command line $ "pwd" print working directory.

Task   1:$ ls  list directory contents.

Task   2:The command line $ "cd" changes directory.

Task   3:$ "ls -l" lists out directory contents in long form.

Task   4:$ "ls -la" lists directory contents in long form, including hidden files.

Task   5:The command line $ "ls -lna" to show long lists of information of files and directory's

Task   6:$ "mkdir /tmp/my_first_directory" this command line creates a my_first_directory directory inside the tmp directory.

Task   7:The command line $ "mv /tmp/betty /tmp/my_first_directory" Takes file betty from the tmp directory and moves it to the my_first_directory, which is also in the tmp directory.

Task   8:This command line  $ "rm /tmp/my_first_directory/betty" Deletes the betty file from the tmp/my_first_directory directory.

Task   9:The command line $ "rm -r /tmp/my_first_directory" is intended to delete my_first_directory  located in directory of  tmp

Task 10:$ "cd -" this command line goes back to the directory we were in by changing it.

Task 11:These command line $ "ls -la . .. /boot" List every file and directory from the current directory, the parent of the working directory, and the /boot directory, including hidden files and folders. Multiple directories may be listed with the ls command, separated by spaces.

Task 12:file /tmp/iamafile basically the functionality of this command is that it prints the type of file iamafile.

Task 13:$ "ln -s /bin/ls __ls__" creates a symbolic link with the name "ls".

Task 14:$ "cp -rua *.html ../" all html files should be copied from the current directory to the parent directory, but only those files that didn't already exist in the parent directory or that are newer versions of those that do. The instructional page for the terminal didn't mention the -u option. If the file has a newer version, the -u option transfers it into the directory. The file will copy over if it doesn't already exist in the directory. Although it doesn't check whether the file is a newer version or not, the -n option can be used to copy files that don't exist in the parent directory.

Task 15:The command line $ " mv [[:upper:]]* /tmp/u" starts moving all files with capital letters to "/tmp/u"

Task 16:$ " rm *~ " this command line deletes all files that may have a "~ " at the end in the current directory.

Task 17:$ "mkdir -p welcome/to/school" in the current directory, create the "welcome" directory. Make a directory inside the "welcome" directory. In the directory, create a directory called "school." Any intermediary folders specified in the path argument are created by the "-p" option.

Task 18:The command line $ "ls -map|sort -d" List each file and directory in the current directory, with commas between each entry. Names of directories must finish in "/". With the exception of dot "(.)" or "dot dot (..)," which should be put first, the listing should be in alphabetical order. Any hidden files will be shown with the "-a" option. The "/" symbol is added to the end of directory names by the "-p" option. With the "-m" option, the output is streamed, with commas used to separate each listing.

Task 19: Compared to the previous exercises, this one was very different. I believe that the magic file is used to identify patterns in files and will provide a certain result if the pattern is found to match.  
The command line used  $ " 0 string SCHOOL School data !:mime School. Creates a magic file called school.mgc that can be used with the command file to detect School data files. School data files always contain "SCHOOL" at offset 0.
