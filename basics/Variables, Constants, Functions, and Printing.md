# Variables, Constants, Functions, and Printing.

## Introduction

In general, we are using programming languages to automate and solve problems that would be too difficult for people to solve with pens and paper. Computers excel at doing lots of simple calculations really quickly --- in fact, it's the thing they're best at! We're going to start by making our first program, a process that's traditionally written to output `Hello, world!` at the end.

Our first program can be created by opening the terminal and creating a new directory (or by navigating to the directory we're already in!) and creating a new file. For now, let's assume we're just going to add to this directory. The process looks something like this:

```bash
$ cd ~/PREVIOUS_DIRECTORIES/teachingWithSwift/basics
$ touch helloWorld.swift
```

You can, of course, use your file manager and code editor to do the same thing!

Now that we have an empty file (`helloWorld.swift`) we should fill it with something. Let's think about what we want to accomplish with our program. For now, all we want to do is print the words `Hello, World!` in the terminal when we run the program. For that we'll need to learn about the first inbuilt function swift has: the `print()` function. In this case, the syntax will look like:

```swift
print("Hello, World!")
```

Easy, huh? Let's take this example and go a little more in depth --- we'll use this simple little program to learn about:

1. Variables
2. Constants
3. Types

As it is, the three are a little intertwined, so we'll need to talk about all three at once.

