# Intro to Git and Github

This is the companion notes to the slides. Sometimes it is better for the all of the information in one neat document.

Outline
- Install git and create a Github account
- What is Git
- Basic Bash Commands
- Using Git
- Using Github
- Advanced Workflows
- Quality of Life Hacks

# Install Git and Create a Github Account

## Installing Git:
- Linux:  sudo apt-get install git
- Mac:  http://git-scm.com/download/mac (probably already installed)
- Windows: http://git-scm.com/download/win 

If you are using Windows, you will be interacting with Git via the Git Bash application ![alt text](images/git-bash-logo.png)

If you are using Mac OS or Linux, use the terminal. Ensure that you can run `git --version` without any errors.

## Setting up Git


Run the following commands:

```sh
git config --global user.name <your name>
git config --global user.email <your email address>
git config --global --add color.ui true
git config --list
```
Replace `<your name` and `your email address as appropiate`.

## Create a Github Account

- Github is a code hosting platform for version control and collaboration
- Share code and collaborate on coding projects
- Create a free account at www.github.com

## Text Editor

Recommended editors (non-exhaustive)
- Sublime Text: https://www.sublimetext.com
- VSCode: https://code.visualstudio.com

# Basic Bash Commands

Here are some common and useful bash commands, most of which deal with file and directory manipulation:
- `ls`: Show directory contents, lists names of files.
    - `ls -la`: Show directory contents (hidden files included) with extra info 
- `mkdir`: Creates a directory of the specified name.
    - `mkdir foo` creates a directory called "foo".
- `cat`: Display contents of a file.
    - `cat hello.txt`: display contents of `hello.txt`  
- `cd`: Change directory. Change to certain directory name if provided.
    - `cd foo` takes you to the directory foo.
    - `cd` Changes to home directory if no directory specified.
    - `cd ..` takes you up one directory
    - `cd ../..` to go up tw
- `pwd`: Displays the name of the working directory.
- `touch`: Creates a blank file with a specified name.
    - `touch file.txt`: Creates blank file with name `file.txt`
- `less`: View contents of specified file, page by page.
    - `less <filenname>`
- `head`/tail: Displays the first/ last 10 lines of a file.
    - `head <filename>`
- `rm`: Removes a specified file. This action is PERMANENT. There is no recycle bin.
    - `rm <filename>`: remove file
    - `rm -r <folder>`: remove folder
- `rmdir`: Removes a directory.
- `history`: Display a listing of the last commands you've run.
- `cp`: Copy specified file to a new named file. Use -r flag to copy a directory.
    - `cp file1.txt file_copy.txt` copy `file1.txt` and paste as `file_copy.txt`
- `mv`: Rename a specified file or directory.
    - `mv foo.txt bar.txt` renames `foo.txt` as `bar.txt`
- `Ctrl-c`: cancel everything (use this when in doubt)

To learn more: https://www.unr.edu/research-computing/the-grid/using-the-grid/bash-commands
