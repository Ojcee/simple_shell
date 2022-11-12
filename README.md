This folder/directory displays all the under-pinnings of a Simple Shell in C programming language



/****** Task 0 *******/



In this task, a Manual Page (man page using the groff format) for the simple shell, as well as a Readme file explaining the entire project should be made available. Also a file that lists all the names of the authors is very much required for the completion of this task.



/****** Task 1 *******/



In this task, all file must pass through all the checks of the Betty Linter. The task is considered completed when all files meets the Betty requirements.



/****** Task 2 *******/



A shell script is written to display prompt and execute one-word command lines (commands without arguments and options). The shell script also handles error.



/****** Task 3 *******/



A shell script is written to display prompt and execute command lines with arguments and options. The shell script also handles error.



/****** Task 4 *******/



An updated shell script from task 3 to handle the PATH, and dosen't call fork if the file dosen't exist.



/****** Task 5 *******/



An updated shell script from task 4 that implements the exit and dosen't handle any exit built-in arguments.



/****** Task 6 *******/



An updated shell script from task 5 that implements the ENV built-in which prints the current environment



/****** Task 7 *******/



In this task, a blog post describing step by step what happens when you type ls -l *.c and hit Enter in a shell must be written and publlished. It should also be posted on LinkedIn and other social media platforms.



/****** Task 8 *******/



A group class work that should be tested in a single respository with every team contributing to the repository.



/****** Task 9 *******/



An updated shell script from task 6 that impliments the getline function.



/****** Task 10 *******/



An updated shell script from task 9 that does not use strtok.



/****** Task 11 *******/



An updated shell script from task 10 that handles arguments for the built-in exit. Usage: exit status, where status is an integer used to exit the shell.



/****** Task 12 *******/



An updated shell script from task 11 that handles Ctrl+C, the shell should not quit when the user inputs ^C.



/****** Task 13 *******/



An updated shell script from task 12 that 1mplement the setenv and unsetenv builtin commands.



/****** Task 14 *******/



An updated shell script from task 13 that implement the builtin command cd which changes the current directory of the process. Command syntax: cd [DIRECTORY]. If no argument is given to cd the command must be interpreted like cd $HOME.It also has to handle the command cd -. You have to update the environment variable PWD when you change directory.



/****** Task 15 *******/



An updated shell script from task 14 that handles the commands separator.



/****** Task 16 *******/



An updated shell script from task 15 handles the && and || shell logical operators.



/****** Task 17 *******/



An updated shell script from task 16 that implements the alias builtin command.



Usage: alias [name[='value'] ...] alias: Prints a list of all aliases, one per line, in the form name='value' alias name [name2 ...]: Prints the aliases name, name2, etc 1 per line, in the form name='value'. alias name='value' [...]: Defines an alias for each namewhosevalueis given. Ifnameis already an alias, replaces its value withvalue`.



/****** Task 18 *******/



An updated shell script from task 17 that handles variables replacement, and also handles the $? variable and the $$ variable.



/****** Task 19 *******/



An updated shell script from task 18 that handles comments (#).



/****** Task 20 *******/



An updated shell script from task 19 that implements the help built-in. Usage: help [BUILTIN].



/****** Task 21 *******/



An updated shell script from task 20 that implements the history built-in, without any argument. The history built-in displays the history list, one command by line, preceded with line numbers (starting at 0) On exit, write the entire history, without line numbers, to a file named .simple_shell_history in the directory $HOME. When the shell starts, read the file .simple_shell_history in the directory $HOME if it exists, and set the first line number to the total number of lines in the file modulo 4096.



/****** Task 22 *******/



An updated shell script from task 21 that implements files input. Usage: simple_shell [filename] Your shell can take a file as a command line argument The file contains all the commands that your shell should run before exiting The file should contain one command per line In this mode, the shell should not print a prompt and should not read from stdin.



