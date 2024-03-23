# Reading-Notes

## Command Line Interface "CLI" Basics

A command line is a text-based interface where commands are entered to perform various tasks. It interacts with the operating system to execute commands and receive results as text output. Commonly used in Unix-like systems, a shell program like BASH facilitates command line interactions.

### Basic Navigation

- **PWD**: Displays the current working directory.
- Paths: Can be absolute (starting from the root directory, '/') or relative (relative to the current directory).

### File System Basics

- **Everything is a file**: Devices and resources like keyboards, monitors are represented as files.
- **Extensionless System**: Linux ignores file extensions to determine file types.
- **Case Sensitivity**: Linux file system is case-sensitive.
- **Handling Spaces in Names**: Enclose names with spaces in double quotes or use escape characters.
- **Hidden Files**: Files starting with a dot ('.') are hidden.

### Manual Pages

- Manual pages provide guidance on command usage and available arguments.
- Two types of arguments: short (single dash + letter) and long (double dash + word).

### File Manipulation

- **mkdir**: Creates directories. Supports options like -p (create parent directories) and -v (verbose).
- **rmdir**: Removes directories. Requires empty directories. Supports options like -v (verbose) and -p (create parent directories).
- **touch**: Creates or updates file timestamps. Can create a blank file.
- **cp**: Copies files or directories. Supports options like -r (recursive copying).
- **mv**: Moves or renames files/directories. Can effectively rename within the same directory.
- **rm**: Removes files or directories. Supports options like -r (recursive removal).

### Summary

- **Navigation**: Use PWD to check the current directory. Paths can be absolute or relative.
- **File System**: Everything is a file, Linux is extensionless and case-sensitive.
- **Manual Pages**: Provide command usage details. Arguments can be short or long.
- **File Manipulation**: mkdir for creating directories, rmdir for removing, touch for timestamps, cp for copying, mv for moving/renaming, and rm for removing files/directories.

---

[Back](DB.md) / [Next Page](MS.md)
