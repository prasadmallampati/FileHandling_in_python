# FileHandling_in_python
File handling refers to the process of performing operations on a file such as creating, opening, reading, writing and closing it, through a programming interface. It involves managing the data flow between the program and the file system on the storage device, ensuring that data is handled safely and efficiently.

File handling in python  essential for task involving  reading from or writing to files 


modes in file handling


In Python, the open function supports several file modes that determine how the file will be opened. Here are the most commonly used modes:

'x': Exclusive creation mode - Creates a new file and opens it for writing. If the file already exists, the operation fails.

'r': Read mode - Opens a file for reading. If the file does not exist, it raises a FileNotFoundError.
'w': Write mode - Opens a file for writing. If the file already exists, it truncates the file. If the file does not exist, it creates a new file.

'a': Append mode - Opens a file for appending. If the file does not exist, it creates a new file. Data is added to the end of the file without truncating it.


'b': Binary mode - Opens a file in binary mode. This mode is used for non-text files like images or executable files. It is used in conjunction with other modes (e.g., 'rb', 'wb', 'ab').

't': Text mode - Opens a file in text mode. This is the default mode if none is specified. It can also be used in conjunction with other modes (e.g., 'rt', 'wt', 'at').

'+': Update mode - Opens a file for updating (both reading and writing). It is used in conjunction with other modes (e.g., 'r+', 'w+', 'a+').

![image.png](attachment:image.png)

Methods

Reading a File

Writing to a File

Closing a File

Handling Exceptions When Closing a File
