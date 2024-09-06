# Terminal Commands

This project provides a basic understanding of terminal commands, covering a range of topics from navigation to file management, along with different shells used in operating systems. The guide is designed to help users navigate and interact with their system's terminal effectively.

## What is a Terminal?

A terminal is a text-based input and output environment where users can run commands to perform tasks. It is an essential tool for interacting with an operating system, especially for developers and system administrators.

## Key Terms

### 1. **Command Line**
   Any interface that allows users to enter textual commands (generally Windows-centric).

### 2. **Terminal**
   A command-line interface (CLI), commonly used on Mac.

### 3. **Console**
   Another CLI used for interacting with your computer's system.

### 4. **Shell**
   A program that runs in the terminal, allowing users to input commands. Different systems may use different shells.

## Types of Shells

1. **Bash** - A popular shell used on Mac OS and Linux systems.
2. **Z-Shell (Zsh)** - Another shell, which is the default on modern macOS.
3. **Windows PowerShell** - A popular shell used on Windows.

## Basic Commands

1. **ls** - List files in the current directory.
2. **pwd** - Print working directory (displays the current directory path).
3. **clear** - Clear the terminal screen.

## Navigation Commands

1. **cd** - Change directory.
    - **cd directoryName** - Go to a specific directory.
    - **cd ..** - Move back to the previous directory.
    
## Paths

1. **Relative Path**:  
   `cd Desktop/CSS` (Navigate to the Desktop's CSS directory).
   
2. **Absolute Path**:  
   `cd /Users/UserName/Desktop/CSS` (Navigate using the full path).
   
3. `/` - Root directory.  
4. `~` - Home directory.

## Creating Directories

1. **mkdir directoryName** - Create a new directory or folder.

## Flags

Flags are additional characters passed with commands to modify their behavior.

### Example Commands with Flags

1. **man commandName** - Show the manual for a specific command.
    - `man ls` - Information about the `ls` command.
    - `man mkdir` - Information about the `mkdir` command.
    
2. **ls -l** - Show additional information for listed files.
3. **ls -a** - Show hidden files.
4. **ls -la** - Show hidden files along with detailed information.

## Creating Files

1. **touch filename** - Create a new file.
   - Example: `touch index.html` creates an HTML file.
   - Example: `touch style.css` creates a CSS file.

## Deleting Files and Folders

1. **rm filename** - Delete a file.
2. **rmdir directoryName** - Remove an empty directory.
3. **rm -rf directoryName** - Remove a directory and all of its contents forcefully.

## Conclusion

This repository provides a useful collection of terminal commands, helping users perform essential tasks such as file management, navigation, and system monitoring efficiently. Whether you are using Linux, macOS, or Windows, these commands will allow you to leverage the power of the terminal for various operations.