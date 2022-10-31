# CS50's Introduction to Computer Science
## HarvardX - CS50x
### Week 2 Problem Set - Hello.c
<hr>


### Assignment and Requirements:
Write and execute the program that prompts the user for their name and then prints ```hello, so-and-so```, where so-and-so is their actual name.


#### Hello.c:

```get_string``` from ```cs50.h``` can be used to store its return value in a variable called ```name``` of type ```string```.

```C
string name = get_string("What's your name? ");
```

To use ```get_string```, ```cs50.h``` should be included (in which get_string is declared) atop a file, as with:

```C
#include <cs50.h>
```

```printf``` can be used to format a string.
```C
printf("hello, %s\n", name);
```

#### Compiling And Execution:

Before execution of the hello.c program, it must be compiled with a compiler, translating it from source code into machine code.\
Execute the command below in the Command Line to do that:

```C
make hello
```

Execute the program by executing the below:
```C
./hello
```
