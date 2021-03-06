Programming Practice
====================

Python
------

#### Learn an editor

Personally, I like Vim. This is a pretty powerful editor and with plugins can be
just as powerful as an enterprise-grade IDE. To learn Vim, start by running
`vimtutor` on the command-line. Complete the tutorial to get comfortable to use
it for the following assignments.

#### Hello World

It's customary when learning a new programming language to create a "hello
world" program. This is usually just a simple program that prints "hello world".
The assignment is to create a python module which simply prints "hello world".

Requirements:

* I should be able to verify it by running `python3 hello_world.py`
* The output of the program should be `hello world`
* There is a function called `main` which is executed to print the message

Functions are defined via `def <function name>(<parameters>):`. If I wanted to
define a function called `foobar` with no parameters, I would write it as:

```python
# function definition
def foobar():
  # inner logic here...

# call foobar here
foobar()
```

#### Fun with functions

Define a function that reads `input` and converts the received input to a
numerical object (e.g. `float`).

Define a function that computes the sum of two numerical values.

Define a function that loops infinitely and constantly appends your input
to some value that will keep growing. Don't forget to `print` the value
as it grows, so that you know it's growing. You could use a `while True:`
loop to achieve this. Furthermore, you may want to create a "phrase" that
will `break` you out of the loop.

Define a "main" function that combines the functions above to write an
`adder.py` program.

**Note**: Each function should have a "docstring" explaining what each parameter
to the function is and what the function does.
