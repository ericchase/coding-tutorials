**Handling data a line at a time may give us a chance to modularize our code.**

#### Headers
This time, we'll use a [vector](http://www.cplusplus.com/reference/vector/vector/) for storing data.

![Imgur](https://i.imgur.com/mY7q1uj.png)

#### Structure the Data
For this program, the goal is to validate lines of data in a file. A valid line contains a string, an integer, and another string. First off, we write a structure to hold data from a valid line.

![Imgur](https://i.imgur.com/IInqp1l.png)

#### Input File
We've got a simple file with 3 valid lines of data and 1 bad line.

![Imgur](https://i.imgur.com/TDLcuKB.png)

#### Read the File
This function is a bit of a leap from the last, but it's just a combination of what we learned before. We use the vector to save up lines of data until the file is fully read. Then the vector full of valid data is returned.

![Imgur](https://i.imgur.com/7u4cuje.png)

#### Using the Data
Finally, a for each loop iterates the vector of valid data, printing it out to the console.

![Imgur](https://i.imgur.com/ktkbM2T.png)

#### Sample
Altogether.

![Imgur](https://i.imgur.com/FwJW2RU.png)

<br>

Next: .

