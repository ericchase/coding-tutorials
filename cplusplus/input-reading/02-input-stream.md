**The simplest input stream readily available for use is `cin`.**

#### Headers
The [``iostream``](http://www.cplusplus.com/reference/istream/iostream/) header file is necessary for using `cout` and `cin`.  
The [``string``](http://www.cplusplus.com/reference/string/string/) header file allows us to use string objects instead of character arrays.

![Imgur](https://i.imgur.com/scSZgyF.png)

#### Simple Example
First, we need some sort of object to hold the data we want to retrieve from the user. I **always** opt for a string object, because the input stream can store *anything* as a string. After all, everything we type is just characters. Next, take a look at the syntax used for writing to the console and reading from it. Correct syntax is required. Attention to detail is also important to make a good impression on your user. Notice the space between the `:` and the `"`. Asking the user to enter some data is called *prompting*.

![Imgur](https://i.imgur.com/EJKIjsA.png)

Now that we have some data from the user, it's time to do something with that data. One option is to simply print it back out for the user to see.

![Imgur](https://i.imgur.com/y89A7Is.png)

Finally, an interaction that might occur with a user named Greg:

![Imgur](https://i.imgur.com/XCECpZy.png)

#### Sample
As promised, a working program that uses the *cin* input stream and *cout* output stream to produce the console interaction seen above, could be written as follows.

![Imgur](https://i.imgur.com/MPASmL7.png)

<br>

Next: Let's look at some options when it comes to [data conversion](./03-data-conversion.md).

