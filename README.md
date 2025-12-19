# Assignment-1
Dev-ops assignment 1 Operating systems basics

# Linux Commands Assignment

Name: Atharva Shelar  
Enrollment Number: 202303103510404  
Subject: Operating System / Linux  


==================================================

1. Creating and Renaming Files/Directories

mkdir test_dir  
touch test_dir/example.txt  
mv test_dir/example.txt test_dir/renamed_example.txt  

Explanation  
The `mkdir` command is used to create a new directory named test_dir in the current working directory.  
The `touch` command creates an empty file named example.txt inside the test_dir directory without adding any content to it.  
The `mv` command is used to rename the file example.txt to renamed_example.txt within the same directory.


==================================================

2. Viewing File Contents

cat /etc/passwd  
head -n 5 /etc/passwd  
tail -n 5 /etc/passwd  

Explanation  
The `cat` command displays the complete contents of the /etc/passwd file, which contains information about user accounts in the system.  
The `head -n 5` command displays only the first five lines of the file, which is useful for quickly viewing the beginning of large files.  
The `tail -n 5` command displays the last five lines of the file, commonly used to check recent entries or changes.

==================================================

3. Searching for Patterns

grep "root" /etc/passwd  

Explanation  
The `grep` command searches through the /etc/passwd file and displays all lines that contain the word "root".  
This command is useful for finding specific users or patterns within large text files.

==================================================

4. Zipping and Unzipping Files

zip -r test_dir.zip test_dir  
unzip test_dir.zip -d unzipped_dir  

Explanation  
The `zip -r` command compresses the entire test_dir directory and all its contents into a single zip file named test_dir.zip.  
The `unzip` command extracts the contents of test_dir.zip into a new directory named unzipped_dir.

==================================================

5. Downloading Files

wget https://example.com/sample.txt  

Explanation  
The `wget` command is used to download files from the internet using a URL.  
In this case, it downloads the file sample.txt from the specified website and saves it in the current directory.

==================================================

6. Changing File Permissions

touch secure.txt  
chmod 444 secure.txt  

Explanation  
The `touch` command creates an empty file named secure.txt.  
The `chmod 444` command changes the file permissions so that the file is read-only for the owner, group, and other users, preventing any modifications.

==================================================

7. Working with Environment Variables

export MY_VAR="Hello, Linux!"  
echo $MY_VAR  

Explanation  
The `export` command creates an environment variable named MY_VAR and assigns it the value "Hello, Linux!".  
The `echo` command displays the value stored in the MY_VAR environment variable, confirming that it has been set successfully.

==================================================

GitHub Repository Link:  
https://github.com/your-username/linux-commands-assignment
