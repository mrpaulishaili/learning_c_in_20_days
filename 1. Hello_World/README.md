# An Introduction to the C Programming language

## An Hello World Program.

In getting started, we are writing a simple Hello World program.

```c
#include <stdio.h>

int main()
{
    printf("Hello World!");
    return 0;
}

```

From the code above, we can see thatthe structure is very easy to figure out and pretty straight forward (😎 or do I thought). Now let me explain.

## Structure of the C program

![C Program Code Structure](https://media.geeksforgeeks.org/wp-content/uploads/20221219163357/Structure-of-C-Program.png)

The structure of a basic C Program code consists of the Header and the Body. To explain futher,

### The Header

This is the part that consists of all the header files inclusions, an example of this in our **Hello World** code is the `#include <stdio.h>`. This line of code here means that we are including a header file, indicated by the **.h** file extension, with the name **stdio**. In adding this line, we have made all the function declarations and macro definitions in that file to now be accessible for our use in our program coding.

> Do you understand?

We will be seeing, exploring and using many more header files as we continue.

### The Body

Yes, everything else apart from the head (this time, header). In thi C program, all codes that comes after the last line of the header files inclusion is part of the body.

The body can consist of various components: variable declarations, functions, statements etc. Most importantly, in a basic C program, our Hello World, there must be a `int main() {}`. This is the entry point for any C program and execution typically starts here.

The curly braces in that line of code contains the statement
that needs to be executed by the C program. In our case, we need our C program to print **Hello World**, therefore, our entry point function became:

```c

int main()
{
    printf("Hello World!");
    return 0;
}

```

The `return 0` is to indicate to the interpreter that our function ran successfully.

## Write and Compile C

🤔 Right now! You too want to write and compile your Hello World Program? Don't worry, I have got you!

There are a number of online IDEs that are available for free that you can use to start writing your C program without installing a compiller. An example of this is [GeeksforGeeksIDE](https://ide.geeksforgeeks.org/).

For windows users, there are many IDEs available. Th most popular of them are CodeBlocks and Dev-CPP. [CodeBlocks](http://www.codeblocks.org/downloads/26) has strongly been recommended by the netizen community for development in C.

> Don't know what Netizen is? 🤔 It's the Internet Community.

Linux users, GCC compiler comes bundled with Linux which compiles C programs and generates executables for us to run, and [CodeBlocks](http://www.codeblocks.org/downloads/26) can also be used with Linux.

🤓 Mac users, macOS already has a built-in text editor where you can just simply write the code and save it with a “.c” extension.

My favourite code editor is the VsCode editor. I write more on our to download and setup on Mac, and possibly on Windows for development in the C language.

## Share your thoughts and comments

I am critically open for your constructive criticisms. Enjoy
as you explore the world of programming in C.

✌🏾 Peace.

**Paul Ishaili C.**
