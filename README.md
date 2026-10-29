# Classic Software Development Projects

This is a set of classic software development projects that help teach the 
process of software development.

We have AI Agent tools now which help us with all of our programming tasks, and 
this is not going to change. While the way we work with them and how we alter
the process based on how well they work and what they do and do not do well is 
going to change, they are here to stay. However, just like in other areas that
a person is learning, having the AI Agent jump to the top is not going to help 
you develop what it takes to climb mountains. Most of the learning and all of 
the muscle memory is found in struggling with the problem itself.

What I'm including here are problems that a software developer ought to work 
through. I'm trying to do them roughly in order of how I think one ought to do
them, but I'm sure that is debatable.

The key here is to learn how the problem ought to be solved. It is not a matter
of getting to the end. No one is grading you. Telling an Agent to do it for you 
will not get you anywhere - however - feel free to have the Agent help you with
the problem. 

For example, you might have a conversation with your AI Agent about how to plan 
the process. Determine the way you will approach the problem and what the issues
you should think about in the project are going to be and how you will wan to 
get around them.

Consider the first program any software developer should write: Hello World! If
you complete it, you learn several things:

- How to set up and use your software development system
- How to write code that will build into a working program
- How to use the output (stdout) system in your particular system

Those are important things to know. An Agent could do this in seconds. In this 
case, that is fine. Have the Agent write the code and help you get everything
set up, but then you make sure that you know what is going on at each step and 
rather than having the AI Agent do it for you, make sure that you have the Agent
tell you what to do and then you go do it yourself.

Why bother? Because this is developing the muscle memory. Later you're going
to want to have a full understanding of what is going on so you can direct the 
Agent properly and troubleshoot issues. You also need to be able to explain 
what you want clearly and if you don't know what to do you can't ask for what
you really want.


## Basics
This is a simple collection of basic programming tasks that any good programmer
should have actually done and be able to do without any assistance. Most of them 
should not take very long and some are only a few minutes. If you are finding 
that it is taking you longer than that, then as long as you're learning something
from the process, then that's the point. 


### Command Line
- [ ] Hello World: basic setup, stdout
- [ ] Command Line Greeting: command line args, usage messages, boolean logic, simple formatted output
- [ ] Calculator (pre and post fix): stdin, tokenization, arithmetic, variables, stacks, loops, error handling, EOF. 
- [ ] Unit Converter (takes input and flags and converts units): functions, floats, input validation
- [ ] Line Filter
  - reads lines of input from stdin, filters based on a regex, outputs matching lines
  - regex, buffering, unicode
- [ ] Simple Text Processor
  - reads lines of text, counting the number of times each word occurs, with a switch to ignore case
  - dictionary, comparison, 
- [ ] Guess A Number
  - interactive game, prompts user to guess a number between two random numbers at least 10 digits apart
  - random numbers, loops, interactive command line

### Simple Processing
- [ ] Copy a File
  - takes filenames on the command line and uses the file system API to copy, handling problems
  - teaches how to use the system APIs, error handling
- [ ] CSV Reader and Validator
  - read a CSV file in validate that is it in CSV format, print the total columns and rows
  - teachs text parsing and processing, CSV format, input and output
- [ ] Sorter: sorts a list on stdin to stdout, takes a switch for sorting options
- [ ] Contacts: command line contact manager uses a JSON file, CRUD
- [ ] Bindump: open a binary file and dump the contexts as binary, octal, of hex based on command line switch
- [ ] Expression evaluator: takes math expressions like "(2 * (2 + 4) / 3)" and outputs the result

### Simple OS and Env 
- [ ] Filesystem Search: find a regex expression on the file system
- [ ] Dumpenv: dumps the current operating system environment, including env vars, running processes, user info, etc
- [ ] Forkrace: fork N processes that each print "Hello World! [N]"
- [ ] Signalhandler: starts a program that will count seconds and output signals it gets until it gracefully terminates
- [ ] Shell: make a simple shell that starts processes, has commands, stdin/stdout redirection, pipes, file descriptors, signals
- [ ] Memplay: interactively allocate different RAM, exit gracefully, demonstrates how the stack and heap allocate and release RAM
- [ ] Filelocker: spawn processes that update the same file with different information to demonstrate race conditions
- [ ] Parenting: start child processes with logging, monitor, restart, etc
- [ ] TCP Echo Server: write a TCP server that will echo whatever you send it, use telnet to test
- [ ] Netchat: client server command line chat program
- [ ] Pinger: make a UDP ping program
- [ ] Whodis: do a DNS and host info lookup


## Minimal Requirements
These are a bit more advanced but still on the basics list.

### Networking
- [ ] Simple HTTP Server: make the smallest HTTP server that will give a response to a web browser
- [ ] REST Client: a REST client that can ping a public API
- [ ] REST API Server
- [ ] File Download Server: has a virtual root and allows clients to download files
- [ ] TLS Client: connect to a HTTPS server and validate certificate

### Database
- [ ] SQLite Contact: write a basic contact manager that uses SQLite
- [ ] Relational Task Tracker: has users, projects, tasks and understand the relationships
- [ ] Money Journal: moves money between accounts, transactions, ACID, rollbacks
- [ ] Docsearch: index a folder of text documents based on word contents and search them
- [ ] keystore: persistant key/val store with append only log, crash recovery

### Concurrency
- [ ] BadThread: demonstrate thread race conditions failing in various ways
- [ ] Queues: demonstrate producer/consumer queues
- [ ] Jobqueue: get a list of items and a counter for concurrent processing (worker pool)
- [ ] Asyncfetch: spawn multiple HTTP clients to get documents at the same time while monitoring progress
- [ ] TCP Server: spawn a thread for each connection and echo back, manage disconnects, persist, shutdown gracefully


## Advanced
I'll do these later

