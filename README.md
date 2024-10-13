# Get Next Line

**Get Next Line** is a project designed to deepen your understanding of file handling in C. The objective is to implement a function that reads a line from a file descriptor, efficiently handling multiple file descriptors and buffering data. This function will allow you to read any text line-by-line, regardless of the file or input source.

## Features
- 📄 **Read from Files**: Supports reading from any file via its file descriptor.
- 🖥️ **Read from Standard Input**: Can also read lines from the standard input (`stdin`), making it versatile for interactive programs.
- 🔀 **Multiple File Descriptors**: Handles multiple file descriptors at once, ensuring the state of each file descriptor is maintained separately.
- 💾 **Efficient Buffering**: Reads are buffered, reducing the number of system calls for better performance.

## Function Prototype
```
  char *get_next_line(int fd);
```
## USAGE:
1. **Clone the Repository**
```
  git clone https://github.com/Rmehadje/Get_next_line.git
```
2. **Accessing the cloned Repository**
```
   cd Get_next_line
```
3. **Compile and run the project**
   Don't forget to add a main function for testing 😉


## ACKNOWLEDGEMENT 
I would like to thank 42 and the community for the help and support to give me an opportunity to work on this project.
