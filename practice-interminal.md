### The Command Line

* Here's your first shortcut. When you enter commands, they are actually stored in a history. You can traverse this history using the up and down arrow keys. So don't bother re-typing out commands you have previously entered, you can usually just hit the up arrow a few times. You can also edit these commands using the left and right arrow keys to move the cursor where you want.

* I'm already familiar with the command line and I used it alot in the previous courses.

### Basic Navigation

* The cd command will help me to navigate to between directories

### More About Files

* pwd-Print Working Directory - ie. Where are we currently.

* ls-List the contents of a directory.

* cd-Change Directories - ie. move to another directory.

* Everything is a file under Linux

- Even directories.

* Linux is an extensionless system

- Files can have any extension they like or none at all.

* Linux is case sensitive

- Beware of silly typos.

* file

- obtain information about what type of file a file or directory is.

* ls -a

- List the contents of a directory, including hidden files.

### Manual Pages

* man <command>

- Look up the manual page for a particular command.

* man -k <search term>

- Do a keyword search for all manual pages containing the given search term.

* /<term>

- Within a manual page, perform a search for 'term'

* n

- After performing a search within a manual page, select the next found item.

### File Manipulation

* mkdir

- Make Directory - ie. Create a directory.

* rmdir

- Remove Directory - ie. Delete a directory.

* touch

- Create a blank file.

* cp

- Copy - ie. Copy a file or directory.

* mv

- Move - ie. Move a file or directory (can also be used to rename).

* rm

- Remove - ie. Delete a file.

* No undo

- The Linux command line does not have an undo feature. Perform destructive actions carefully.

* Command line options

- Most commands have many useful command line options. Make sure you skim the man page for new commands so you are familiar with what they can do and what is available.

### Vi Text Editor

* vi

- Edit a file.

* cat

- View a file.

* less

- Convenient for viewing large files.

### Wildcards

* Anywhere in any path

- Wildcards may be used at any part of a path.

* Wherever a path is used

- Because wildcard substitution is done by the system, not the command, they may be used wherever a path is used.

### Permissions

* chmod

- Change permissions on a file or directory.

* ls -ld

- View the permissions for a specific directory.

### Filters

* head

- View the first n lines of data.

* tail

- View the last n lines of data.

* sort

- Organise the data into order.

* nl

- Print line numbers before data.

* wc

- Print a count of lines, words and characters.

* cut

- Cut the data into fields and only display the specified fields.

* sed

- Do a search and replace on the data.

* uniq

- Remove duplicate lines.

* tac

- Print the data in reverse order.

### Grep and Regular Expressions

* egrep

- View lines of data which match a particular pattern.

* Regular Expressions

- A powerful way to identify particular pieces of information.

### Piping and Redirection

* >

- Save output to a file.

* >>

- Append output to a file.

* <

- Read input from a file.

* 2>

- Redirect error messages.

* |

- Send the output from one program as input to another program.

* Streams

- Every program you may run on the command line has 3 streams, STDIN, STDOUT and STDERR.

### Process Management

* top

- View real-time data about processes running on the system.

* ps

- Get a listing of processes running on the system.

* kill

- End the running of a process.

* jobs

- Display a list of current jobs running in the background.

* fg

- Move a background process into the foreground.

* ctrl + z

- Pause the current foreground process and move it into the background.

### Scripting

* Behaves the same

- Anything you may do on the command line you may do in a script and it will behave exactly the same.

* Formatting

- Bash scripts are particularly picky when it comes to formatting. Make sure spaces are put where they are needed and not put when they are not needed.

### Cheat Sheet

* This [CheatSheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)will be helpful if I forgot any of these commands 