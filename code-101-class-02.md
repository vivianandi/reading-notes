# The Coder’s Computer

## Choosing A Text Editor – The Older Coder 

1. Introduction to Text Editors:
- Text editor is essential for web development
- Personal preference plays a crucial role in choosing a text editor 
- Features such as code completion, syntax highlighting, themes, and extensions are important

2. Key Features to Look For:
- Code Completion: provides suggestions while typing code
- Syntax Highlighting: colorizes text for easier readability
- Themes: customize background and text colors
- Extensions: add functionality to the text editor

3. Using Default Computer Text Editors:
- Mac: "Text Edit," Windows: "Notepad," Linux: varies
- Limited features; lacks code completion, syntax highlighting, themes, and extensions

4. Third-Party Options:
- Notepad++ (Windows)
- BB Edit (Mac)
- Visual Studio Code
- Atom
- Brackets
- Sublime Text 3

5. Difference Between Text Editors and IDEs:
- Text Editor: edits and manages text and files
- IDE (Integrated Development Environment): comprehensive suite with a text editor, file manager, compiler, and debugger

## The Command Line
- The command line is the terminal - a text based interface to the system --> enter commands by typing them on the keyboard and feedback will be given to you similarly as text
- **Shell** - within the command line,  part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you

## Navigation
- This section provides an overview of fundamental commands for navigating and understanding the file system

### Print Working Directory (`pwd`)
- `pwd`: prints the current working directory

### List Contents (`ls`)
- `ls`: lists the contents of the current directory

### Paths
- Absolute paths start from the root directory (`/`), while relative paths are in relation to the current location

### Path Building Blocks
- `~` (tilde): represents the home directory
- `.` (dot): refers to the current directory
- `..` (dotdot): refers to the parent directory

### Change Directory (`cd`)
- `cd [location]`: changes the current directory
- Running `cd` without arguments returns to the home directory

## More About Files - Everything is a File
- In Linux, all entities, including text files, directories, keyboards, and monitors, are treated as files
- This concept is foundational for effective file and directory management
- Distinguish between uppercase and lowercase letters in file and directory names

## Q&A
What are four important features to look for in a text editor?
What do the following commands do?
- pwd - (print working directory) displays the current working directory's full path
- ls - lists the contents of the current directory
- cd - (change directory) changes the current working directory
- mkdir - (make directory) creates a new directory
- touch - creates an empty file or updates the access and modification times of an existing file

Can you explain what is happening in the following scenario if these commands and arguments are entered into the command line? (Arguments are extra instructions given to a command.)
- cd projects - changes the current directory to "projects"
- mkdir new-project - creates a new directory named "new-project"
- touch new-project/newfile.md - creates a new empty file named "newfile.md"
- cd .. - moves back one level in the directory hierarchy
- ls projects/new-project - lists the contents of the "new-project" directory within the "projects" directory
