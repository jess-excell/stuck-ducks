---
layout: single
title:  "Hello world in C#"
date:   2024-10-04 17:00:44 +0100
categories: csharp
sidebar: 
    nav: c-sharp-docs
---
Hi ducks! Today we are going to learn how to output "Hello World" to your screen using C#.

For this tutorial, I'd recommend you use [programiz][programiz]. This will allow us to practice writing code online, without actually needing to install python.

You should see that the page is made up of 2 parts: on the left, we have `Main.cs` and on the right, we have `Output`. When we click the blue Run button, the code inside `Main.cs` is compiled and executed, and the result will be shown in the output. This out

Programiz gives us some example code to play with in Main.cs, and it's really important we **don't touch most of this default code**. We will be working with the line that starts with `Console.WriteLine` today.

We are going to edit the `Console.WriteLine` line to say:
```c#
Console.WriteLine("Hello world!");
```
So, our code should look something like this:

```c#
using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        Console.WriteLine("Hello world!");
    }
}
```
Don't worry if you have some lines in light grey above "using system". These are comments, and something we will learn more about later.
Now, if you run this program, you should get the following output:

```
Hello world!
```

You can change the text in the quotation marks to whatever you would like, and it should be printed to the screen. We are using the `Console.WriteLine` function, and its purpose is to display text to the user. Once you've got the hang of this, feel free to move onto the next tutorial!

[programiz]: https://www.programiz.com/csharp-programming/online-compiler/