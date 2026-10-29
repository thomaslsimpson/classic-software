# Command Line

These are very simple programs which use the command line on any operating 
system to take input and then they produce output.

## Hello World
This is the first program that a software developer should write and whenever you 
start a new programming language, write Hello World in that new language as well.

It will tech you how to make sure the development environment is set up and make
sure you can build software with it for the operating system you are working with.

It will also teach you to do simple output to stdout.

**Instructions:**
Write a program that prints "Hello World!" with a newline at the end to stdout.

## Trivial Shell Script

Programmers should know how to use the command shell and how to run shell scripts
because these will come in handy often.

**Instructions:**
Write a shell script that will echo back whatever you write on the command line.

If you name the script "shelltest.sh" then you should be able to run it like this:

```
> ./shelltest.sh foo blah -buzz
```

... and get this output:


```
foo blah -buzz
```

If you get the AI Agent to write this for you, be sure that you fully understand
what is going on in the script. If you do not, take a minute and go learn how it 
all works. This is very helpful to understand.


## Greeting
This program will output the following format:

```
Hi {firstname} {lastname}!
```

The program will accept command line arguments for first name and last name like:

```
> ./greeting -first John -last Smith
Hi John Smith
```


## Calculator
Build a command line calculator that reads postfix input and then outputs the 
correct answer (addition, subtraction, multiplication, division)

Postfix (Reverse Polish Notation) reads the input left to right and solving like:

```
54+ -> 5 + 4 -> 9
12+34+* -> (12+)(34+)* -> (1 + 2) * (3 + 4) -> 21
123*+ -> (1 + (2 * 3)) -> 7

```
> ./postfix 34+
7

> ./postfix 456\*+
34

> ./postfix 453\*+5+
19
```

Now make a prefix one that works like this

```
> ./prefix +34
7
```


## Unit Converter

Convert units between gigabtyes, megabytes, kilobytes, bytes.

Convert 5 gigabytes to megabytes
```
> ./uconv -iG -oM 5
```

Use -iG, -iM, -iK, -iB to set the input type and the -oG, -oM, -oK, -oB for 
the output type.


## Line Filter


## Simple Text Processor


## Guess A Number

