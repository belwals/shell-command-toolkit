## Shell Command Toolkit
A curated collection of essential shell commands for Linux systems.

## Introduction
This repository provides a comprehensive list of common shell commands, organized for easy reference. These commands can help you automate tasks, troubleshoot issues, and manage your Linux system efficiently.

## Basic Commands
* Navigation:
    ``` Bash
        cd <directory>  # Change directory
        cd ..           # Go to parent directory
        pwd            # Print working directory
    ```

* File Operations:
    ``` Bash
        ls              # List files and directories
        mkdir <directory>  # Create a directory
        touch <file>        # Create a file
        rm <file>          # Remove a file
        rm -r <directory>   # Remove a directory recursively
        cp <source> <destination>  # Copy a file or directory
        mv <source> <destination>  # Move a file or directory
    ```

* Viewing File Contents:
    ``` Bash
        cat <file>  # Display the entire file
        head <file>  # Display the first few lines
        tail <file>  # Display the last few lines
    ```

## Advanced Commands
* Searching and Filtering:
    ``` Bash
        grep <pattern> <file>  # Search for a pattern in a file
        find <directory> -name "*.txt"  # Find files with a specific extension
    ```

* Text Manipulation:
    ``` Bash
        sed 's/old_text/new_text/g' <file>  # Replace text in a file
        awk '{print $2}' <file>  # Extract specific fields from a file
    ```

* Process Management:
    ``` Bash
        ps aux  # List running processes
        kill <PID>  # Kill a process
    ```

* Remote Access:
    ``` Bash
        ssh <user>@<host>  # Connect to a remote host
        scp <file> <user>@<host>:<destination>  # Copy a file to a remote host
    ```


## Tips and Tricks
* Use wildcards: * matches any character sequence, ? matches a single character.
* Combine commands with pipes: command1 | command2 sends the output of command1 as input to command2.
* Use redirection: command > file redirects output to a file, command >> file appends output to a file.
* Explore shell scripting: Automate repetitive tasks with scripts.


## Contributing
Feel free to contribute to this repository by adding new commands, improving existing ones, or fixing issues.

### Happy scripting!