**More often than not, your program will require numberic data instead of simple text.**

#### Headers
#include<iostream>
#include<string>
#include<sstream>

#### String to Int
Strings are nice, but things get more interesting when numbers are involved. As mentioned before, I *always* use a string object to get input from the user. If you try to store data into a variable that cannot handle it, then the input stream will enter an error state and stop working. It's easier to check what kind of data you have *after* storing it into a string object.

![Imgur](https://i.imgur.com/z5Ki04J.png)

Create the `stringstream` and `int` object variables. A stringstream is like an input stream with slightly different functionality. For primative data types, stringstreams are easy to use for data conversion.

![Imgur](https://i.imgur.com/OxPa1RG.png)

The user's input is stored in the 'user_input' variable, so the next step is moving that data into the stringstream object and then into the integer object. The stringstream object will does the conversion itself.

![Imgur](https://i.imgur.com/cOb5p0S.png)

Finally, if the user entered an integer, it should now be stored inside the 'number' variable. However, if the data was not a valid integer, the conversion process may have failed. If that's the case, 'number' will simply contain 0. To check if the conversion failed, test the `fail` and `bad` functions of the stringstream object. `number % 2 == 0` is one way to check if the integer is even.

![Imgur](https://i.imgur.com/8fMY1m4.png)

Possible interactions:

![Imgur](https://i.imgur.com/tq0rK5F.png)

![Imgur](https://i.imgur.com/5LzB52q.png)

![Imgur](https://i.imgur.com/ySnSylf.png)

#### Sample

![Imgur](https://i.imgur.com/zCzy721.png)

<br>

Next: Reading from a [file](./03-file.md) can be done with little to no extra effort.

