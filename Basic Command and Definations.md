#Basic Commands

### 1. **cd** :
- The `cd` command stands for change directory. It is a command used to change the current working directory in various operating systems.
- The `cd` command can nbe used in various way. 
*For example:* 
`cd..` is used to move the directory back in one directory.
`cd\` command takes it back to the root directory of the current drive.

### 2. **mkdir**:
- `mkdir` is make directory command to create directory in cmd.
- The `mkdir` command is is used to create new directories. A directory, referred to as a folder in some operating systems, appears to the user as a container for other directories and files.
*The simplest way to create a new directory is as follows:*
`mkdir<foldername>`

### 3. **cp**:
- The `cp` command is a command-line utility for copying files and directories.
- It supports moving one or more files or folders with options for taking backups and preserving attributes.
- Multiple files and multiple directories can be copied using `cp` command. 
*How to use `cp` command:*
To copy a file pass the name of the file and then the destination.
`cp file 1.txt file 2.txt` This command using cp will copy file 1 to file 2.

To copy multiple files using the `cp` command pass the names of files followed by the destination directory to the `cp` command.

`tree -F
.
├── bar.txt
├── baz.txt
├── foo/
└── foo.txt
cp foo.txt bar.txt baz.txt foo/
tree .
.
├── bar.txt
├── baz.txt
├── foo
│   ├── bar.txt
│   ├── baz.txt
│   └── foo.txt
└── foo.txt`

### 4. **pwd:**
- The `pwd` command stands for *print working directory*. It prints the path of the working directory, starting from the root.
*For example:*
`pwd/home/rohit`

### 5. **Is:**
- `Is` stands for Input secondary. It writes results to standard output. The ls command supports showing a variety of information about files, sorting on a range of options and recursive listing.
- The ls command can be used to show all of the files and folders from the specified path downwards.

*The syntax for the ls command is as follows:*
`ls [OPTIONS] [FILES]`

### 6. **mv:**
- `mv` stands for move. It is a Unix command that moves one or more files or directories from one place to another.
- The `mv` command is used to rename and move files and directories. If two file names are provided as arguments, mv renames the first as the second.

*For Example:*
Let us consider a 3 files named `abc.txt`, `def.txt`, `xyz.txt`. To rename the file `abc.txt` to `lmn.txt` which doesnt exist, the following command is given:

`$ Is
abc.txt def.txt xyz.txt
$ mv abc.txt lmn.txt
$Is
def.txt xyz.txt lmn.txt`

If the destination file doesn’t exist, it will be created. In the above command mv simply replaces the source filename in the directory with the destination filename(new name)

### 7. **rm:**
- The rm command is a UNIX and Linux command line utility for removing files or directories on a Linux system.

- In computing, rm (short for remove) is a basic command on Unix and Unix-like operating systems used to remove objects such as computer files, directories and symbolic links from file systems and also special files such as device nodes, pipes and sockets, similar to the del command in MS-DOS, OS/2, and Microsoft Windows.

– List the directory contents
– Enter a command to delete file
– View if the file has been deleted
– Enter another command to delete file
– Confirm if your file has been deleted

*For example:*
Lets delete the file with the name xyz.txt
`rm xyz.txt`

### 8. **History:**
- In computing various shells maintain a record of the command issued by the user during the current session.
- Since most current history commands are shell built-ins, details depend on the choice of shell.
- The historical reference begins with an exclamation mark (at the beginning of the command). The characters typed immediately after the exclamation mark identify the event you wish to refer to. 

*Here are the four most common ways you can tell the system to reference your history list:*
*for Example:*
`!11 --> Repeat event 11`
`!! --> Repeat command`
`!v --> Repeat the most recent command beginning with `ma``

### 9. **Home directory:**
- A home directory is the directory or folder commonly given to a user on a network or Unix or Linux variant operating system.

- A standard subdirectory of the root directory, `/home` has the sole purpose of containing users home directories. The root directory, which is designated by a forward slash ( / ), is the directory that contains all other directories and their subdirectories as well as all files on the system.
1. Click Start, point to Programs, point to Administrative Tools, and then click Active Directory Users and Computers.
2. In the console tree, click Users.
3. In the Details pane, right-click the user account, and then click Properties.
4. In the Properties dialog box, click Profile.
5. Under the Home folder, type the folder information. To do this, follow these steps:
 - To assign a home folder on a network server, click Connect, and then specify a drive letter.
  - In the To box, type a path. This path can be any one of the following types:
    - Network path, for example:
`\\server\users\tester`
     - You can substitute username for the last subfolder in the path, for example:
`\\server\users\username`
6.Note In these examples, server is the name of the file server housing the home folders, and users is the shared folder.
7.Click OK.

### 10. **File paths in linux:**
- PATH is an environmental variable in Linux and other Unix-like operating systems that tells the shell which directories to search for executable files (i.e., ready-to-run programs)
- In Linux, the PATH environment variable stores the names of paths that will be searched for the executable files of any commands typed in the command line. The value of the PATH environment variable is a string containing a series of pathnames, each delimited by a colon. For instance, the default PATH on a typical system might look like this:
`/usr/local/bin:/usr/bin:/bin:/usr/local/games:/usr/games`

### 11. **Using the `tab` to complete the file path:**
- Using the `TAB` key will automatically fill in the rest or show you the available options you can type. Any other operating system that uses the Bash shell will work the same.
- Generally `tab` keys is used for the user to auto complete its command thus avoiding the mistakes.
- It is generally used to complete the file path whioe writing the code to save time.

### 12. *Using up and down arrow for history:**
- The up and down arrow are used to repeat the command which was recently inserted.
- These arrows are generally used to give the same command or open the same directory which was opened recently. It thus gives a complete feedback to all the directories which has been opened to avoid any errors.






