![Image] (lab1-cd-1.png)  
cd without argument result in the change of directory to home.
The output is expected, so this is not an error.

![Image] (lab1-cd-2.png)  
cd with ".." argument result in changing the current directory to 
its parent directory.The output is expected, so this is not an error.

![Image] (lab1-cd-3.png)  
cd with "SpaceX" argument result in an output error since "SpaceX" is not
in the directory. The output itself is not an error, it outputs the expected.

![Image] (lab1-ls-1.png)  
ls without argument lists the files and folders in the current directory.
The output is not an error, it works as expected.

![Image] (lab1-ls-2.png)  
ls with "/workspaces/" argument list what is in "/workspaces/."
The output is not an error, it works as expected.

![Image] (lab1-ls-3.png)  
ls with "SpaceX" as argument display what file is in "SpaceX."
The output is not an error since the "SpaceX" is a file name within that
section.

![Image] (lab1-cat-1.png)  
cat without arguments result in a waiting for the input argument.
The output is not error because cat command is used to display the contents
of the given path. Without the argument the command is not doing anything.

![Image] (lab1-cat-2.png)  
cat with argument "cse15l-lab-reports" prints an error messaget because
"/workspaces/cse15l-lab-reports/cse15l-lab-reports"does no exist.
The output is not an error since the path does not exist.

![Image] (lab1-cat-3.png)  
cat with argument "SpaceX" prints out the contents in "Spacex" file.
The output is not an error because it prints out the file content. 
