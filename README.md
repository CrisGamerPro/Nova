!["Nova"](./images/Nova.png "Logo")
# Nova Interpreter
A simple and fast interpreted code language for learning and testing.

## How it works?
Nova is an interpreted language just like python, lua, php, etc. Because of that, to get a nova script running you’ll need to download the interpreter (currently only available for Windows). This interpreter is coded on python and it’s designed to read and execute line by line the script, the syntax it’s simple but kinda strict (just a bit).

> For starters it shouldn’t be confusing at all.

## Code examples (Syntax)
**Setting up a variable**

To create a new variable, Nova uses `set`, now you need to specify a name to that variable, on this case ‘test’ -> `set test`, after that, you set a value to it: `set test "hello world"`. And you just created a variable!

**Printing to console**

`print` on nova is not hard, you use `print` and specify a string or a variable like this: `print test` and the output is: `hello world`.

**Running a bash command**

`run` allows you to run bash commands easily by typing `run "Your command"` like this: `run java --version`.


**Full random sample (from v1.0.0)**

`// Let’s get a Minecraft server running!
set command "java -Xmx2G -jar server.jar nogui"
print "Now starting up the server…"
run command
`
