**The easiest way to read from a file is via input redirection.**

#### Headers
No new header files are required.

![Imgur](https://i.imgur.com/scSZgyF.png)

#### Redirection
Input redirection is handled by the console and system. Essentially the process takes data from inside a file and sends it to the input stream, ready to be accessed via cin. It is far easier than using file streams if your program only requires one file for input.

The syntax looks like this: `program < file`.

For this program, we need a string object to store user input and a while loop to get data from the file. The data will be printed to the console with no further processing. For the condition, we keep testing that the end-of-file bit (eof) is false. When the eof bit is set to true, the loop will stop and the program will end.

![Imgur](https://i.imgur.com/PqfL95a.png)

The program simply prints out each word or number within the input file and places commas between them. As far as I know, this can be done on every major operating system. The full process looks like this:

![Imgur](https://i.imgur.com/7BMAv44.png)

#### Sample

![Imgur](https://i.imgur.com/jtbs0vw.png)

<br>

Next: Reading files [line by line](05-line-by-line.md) may prove to be useful.

