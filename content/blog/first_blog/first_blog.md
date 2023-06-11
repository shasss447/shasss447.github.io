---
title: 'Exploring the Stream:  Itinerarium Aedificationis Software'
date: "6/6/23"
draft: false
comments: true
socialShare: true
toc: true
cover:
  src: /first_blog_cover.jpg
tags:
  - developmet
  - c++
---

Recently, I have finished building my first C++ project and it was total fun. As someone who has worked on developing websites using [React](https://react.dev/) and various other technologies, venturing into software development with C++ presented a whole new world of possibilities. In this blog post, I want to share some of the basic principles and amazing features of C++ that I discovered during the development of this project. 
<!--more-->

Let's start with the STREAM system of C++. Stream in C++ is stream of data, from consoles, files or strings. This system provides a consistent and unified approach to handle input and output operations, all thanks to the concept of Buffers. 
In C++, there are two broad classes of streams: Input Streams and Output Streams. 
Input Streams are used for reading data, acting as a source from which the program can extract values. On the other hand, Output Streams are used for writing data, providing a destination where the program can send output values.

Initially, my acquaintance with streams was limited to iostream. Being the first line in almost every C++ program, ``#include<iostream>``, I had been using it without fully understanding the whole world behind it. The first thing I understood about ``iostream`` is that you can't perform input or output functions without this stream flowing through your program. I'm talking about the most usable input and output functions, "std::cin" and "std::cout" respectively. There's another set of input and output functions which i came across during making of this project, which I'm gonna talk about in other section. Firstly let's dive into some of the different functions and streams, I found out.
 
First up, as I briefed a little, we have 'iostream'. This stream contains the declarations of the standard input/output streams and related functionality. "std::cin", an object of type ``std::istream`` that represents the standard input stream. It allows us to read input from the user. Similarly, "std::cout" is an object of type ``std::ostream`` that represents the standard output stream, enabling us to write output to the console.

The next stream that made its way into my project was ``fstream``. It opened up a pathway for handling input and output to files. With fstream, you can read from and write to different files using the functions provided by the stream. It introduced me to three main classes for file input/output: 

``std::ifstream`` for reading data from files, ``std::ofstream`` for writing data to files, and ``std::fstream`` for both input and output operations. These classes empower you to perform operations such as reading data, managing file positions and many more. To open a file, you can use the "open()" function with different modes like ``std::ios::in`` for input and ``std::ios::out`` for output. Once you've performed the required operations, remember to call the "close()" function to close the file gracefully.

While working on my project, I stumbled upon another stream called ``sstream``. It provided invaluable functionality for manipulating strings as input/output streams. The standout class in this context is ``std::stringstream``, accompanied by related classes like ``std::istringstream`` and ``std::ostringstream``. I found myself using stringstream extensively, as it simplified many tasks. Key features and operations offered by ``std::stringstream`` include the ">>" operator for reading values from a string as if it were an input stream, the "getline()" function for extracting lines from a string, and the "<<" operator for writing values to a string as if it were an output stream

Lastly, let's talk about Buffering. In the context of streams, buffering refers to the process of temporarily storing data in memory before it is read from or written to the actual input/output device. This process significantly improves efficiency and performance by reducing the number of system calls or disk accesses. Every stream has an associated buffer—an internal memory area that holds data before it is transferred. When data is written to a stream, it first goes into the buffer, and once the buffer is full or the stream is explicitly flushed, the data is transferred to the output device. Buffering offers advantages such as efficiency (reading or writing data in larger chunks) and reduced I/O operations (combining multiple operations into a single larger one). To control buffering behavior, C++ provides various built-in functions and manipulators. One common example is "std::endl", which flushes the buffer associated with the output stream and inserts a newline character.

In conclusion, my journey with C++ and this project has been nothing short of exciting. I've explored the STREAM system, worked with different streams like iostream, fstream, and sstream and also buffered for many hours.I hope this blog post serves as a helpful introduction to these C++ concepts and features.

To know more about this project check this [out](/projects#bank-management-app)!!

Felix codificatio!