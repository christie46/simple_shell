<h1>Simple Shell</h1>

<h3>Background Context</h3>

<p>The Simple Shell is the creation of a UNIX command interpreter, which allows us to know in detail its execution from a system of own created functions.</p>
<hr/>
<h3>Learning Objectives</h3>

<li>How does a shell work</li>
<li>How does a pid and a ppid work</li>
<li>How to manipulate the environment of the current process</li>
<li>How to create processes</li>
<li>How does the shell use the PATH to find the programs</li>
<li>How to execute another program with the execve system call</li>
<li>How to suspend the execution of a process until one of its children terminates</li>
<li>EOF implementation / end of file </li>
<hr/>
<h3>Description of the files</h3>

<p>The following table describes each file exposed in the simple shell repository</p>

| FILE | SPECIAL FEATURE |
| :---: | --- |
| **main_shell.c** | Main function of simple shell | 
|**functions.c** | File containing the own functions, to be used according to the call of the main_shell |
| **shell.h** | Header file, contains the direct declarations or function prototypes |
| **free_function.c** | Own function, it is used to unassign the memory assigned by the functions malloc , calloc etc |
| **getline** | It reads the command line input stored in a buffer |
| **print_env.c** | Own function that prints the current environment |
| **_putchar.c** | Own function, writes the character c to stdout |
| **child.c** | Function that creates the child process |
| **prompt.c** | Function that prints the prompt line |
| **_atoi.c** | Convert a string to an integer |
| **_strcmp.c** | Own function that compare two string and return cero on success |
| **sp_string.c** | Own function that split a string with strtok function |
| **_strcat.c** | Own function that concatenate two string |
| **_strdup.c** | Own function that copy a string |
| **_strlen.c** | Own function that return the length of a string |
| **print_errors.c** | Own function that print errors of the program |
| **print_integer.c** | call a recursion function with an iterator |
| **recursion_int.c** | print and return amount of digits of the number n |
| **print_env.c** | function that prints environ |
| **free_arraybid.c** | free a array bidimentional |
| **_isdigit.c** | Own function that checks for a digit cero through nine |
| **manage_signal** | Own function that manage the signal CTRL + C |
| **exit_cmd.c** | Own outputs function in the program according to the data of the array in position one |
<hr/>
<h3>Installation and use </h3>
