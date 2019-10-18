# PSK - Python Starter Kit-00

###### Why 00? Because we start counting from zero.

(This is a template repo for everyone doing PSK-00. Feel free to edit it!)

# Welcome
> Simple is better than complex.

A lot of Python developers know this line. It's from the [Zen of Python](https://www.python.org/dev/peps/pep-0020/). More on that later.
Python as a language is among the best to start coding with. Why? I think it's the simple to get up to speed with and is versatile (it can be used in many fields)

## Setup
You have two options:

#### Web:

- Get to this [assignment on Repl.it](https://repl.it/teacher/assignments/4141957) to continue.


#### Local: (On a local computer)

- Install Python. Refer to [this gist](https://gist.github.com/NdagiStanley/bf9db623e8a96ef2ab631a28c9a1eba8) depending on your OS.
- <details>
  <summary>Install and run VSCode from [here](https://code.visualstudio.com/). You can use an editor of choice.</summary>

  VSCode is a popular editor.
  
  More on Python in VSCode [here](https://code.visualstudio.com/docs/languages/python).
  
  Install [Python extension on VSCode](https://marketplace.visualstudio.com/items?itemName=ms-python.python) (optional)

  </details>

- Clone this repo or copy the contents of main.py into a local main.py. Being able to clone repos and commit changes from the terminal will be an expected knowledge over time 💪

## Learning

As you can see the file `main.py` has the line:
```
print("Hello World")
```

And the output in the terminal when you run `python main.py` is:
```
Hello World
```

**"Hello World"** is a string. A string is a **data structure**. In python, strings are surrounded by quotes (either single quotes or double quotes). Python is not picky 😃.

All about strings in python can be read [here](https://docs.python.org/3.7/library/string.html).

**print** is an inbuilt function or methods. What's that? That means when you type print, python knows what you mean right off of the bat.

Here's a list of more inbuilt functions: https://docs.python.org/3.7/library/functions.html (Click on print and any other to read more)

A function mostly has () brackets after the word (there's no space in between) i.e print(). What you put in between the brackets is called an argument. Therefore "Hello  World" is the argument in this case: print("Hello  World")

Data structures is a general term in  Computer Science/IT. In Python, strings; called str is one of the standard types.
Other standard types can be an argument for the print function:
- int, float (https://docs.python.org/3.7/library/stdtypes.html#numeric-types-int-float-complex)
- list (https://docs.python.org/3.7/library/stdtypes.html#lists)
- dict (https://docs.python.org/3.7/library/stdtypes.html#dict)
and so on. Find more here: https://docs.python.org/3.7/library/stdtypes.html

INT<br>
Any number on a number line is an int in Python. 
e.g 5

FLOAT<br>
Any number with a point is a float in Python. 
e.g 1.2

LIST<br>
Is a sequence type. It can contain int, float, string, dict and others
e.g [1,2,3] or ['a','b','c']

DICT<br>
Is a mapping type consisting of key-value pairs.
e.g {'A': 'Apple', 'B': 'Boy'} or {1: 1000, 2: 2000} or {'X': 10, 'D': 100, 'L': 500}
We'll touch on these with time.

NB:<br>
Strings are always quoted.
A statement (one line in the editor or Python Shell) does not have a `;` or some other punctuation mark to complete it.

Finally, allow me to introduce what is a variable.

Computer programs run on RAM (Random Access Memory)
So the types and functions are usually stored in RAM when the program is running.

A Variable can be defined as a symbolic name associated with a value. Variables are used to store information to be referenced and manipulated in a computer program.

The BEST definition of a variable is the name of a memory location.
When I type:
`name = "Stan"`, string "Stan" occupies some memory in RAM and when I type `print(name)` Python accesses the value of that memory location and prints it.


## EXERCISE
Submit code that outputs the following:
```
Hello World

My name is Stan.
I am 20+ years of age. Young, right? 😃

The maximum number in this list: [12, 4, 56, 17, 8, 99] is 99.
The mean: [12, 4, 56, 17, 8, 99] is 32.666666666666664

A for Apple
B for Boy
C for Cow
...
Z for Zebra
```

With extensive research and reading, try to output this with elegant code. Elegant code here means code that is using descriptive variable names an the language's types and functions. Go beyond just using strings.

See you next week!

## Submit assignment

- You'll be required to update `main.py` with your code from the code editor on repl.it or your local code editor.

