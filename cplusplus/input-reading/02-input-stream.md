**The simplest input stream readily available for use is `cin`.**

##### Headers
The [``iostream``](http://www.cplusplus.com/reference/istream/iostream/) header file is necessary for using `cout` and `cin`.  
The [``string``](http://www.cplusplus.com/reference/string/string/) header file allows us to use string objects instead of character arrays.
```c++
#include <iostream>
#include <string>
```

**Note**  
Some people may have led you to believe that `using namespace std;` is common practice; but this is not the case for professional quality code. I personally do not outright condemn its usage, as the feature exists for a reason. In general, if you don't know **why** you should 
use something, then you probably don't need to use it. Being adventurous is fun, but save it for experimental projects only. Be weary of copying what someone else does without knowing why.

```c++
string user_input;
std::cout << "Please enter your name:" << std::endl;
std::cin >> user_input;
```
