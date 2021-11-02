# Python Regular Expression
##  Regular Expressions, often shortened as regex, are a sequence of characters used to check whether a pattern exists in a given text (string) or not.
##  In  used search engines, search and replace tools of word processors and text editors.
### They are used at the server side to validate the format of email addresses or passwords during registration, used for parsing text data files to find, replace, or delete certain string.
### They help in manipulating textual data, which is often a prerequisite for data science projects involving text mining.
- [x] In Python, regular expressions are supported by the re module.  
- [x]  re library in Python provides several functions that make it a skill worth mastering.
- [x]  The match() function returns a match object if the text matches the pattern. Otherwise, it returns None.
- [x]  With the search function, you scan through the given string/sequence, looking for the first location where the regular expression produces a match.
- [x]  The group function returns the string matched by the re. You will see both these functions in more detail later.


# shutil — High-level File Operations
## The shutil module includes high-level file operations such as copying and archiving.
## copyfile() copies the contents of the source to the destination and raises IOError if it does not have permission to write to the destination file.
### The implementation of copyfile() uses the lower-level function copyfileobj().
###  While the arguments to copyfile() are filenames, the arguments to copyfileobj() are open file handles. The optional third argument is a buffer length to use for reading in blocks.
- [x]  By default when a new file is created under Unix, it receives permissions based on the umask of the current user. To copy the permissions from one file to another, use copymode().
- [x]  shutil includes three functions for working with directory trees. 
- [x]  To copy a directory from one place to another, use copytree(). It recurses through the source directory tree, copying files to the destination. 
- [x]  The which() function scans a search path looking for a named file. 
- [x]  The typical use case is to find an executable program on the shell’s search path defined in the environment variable PATH.