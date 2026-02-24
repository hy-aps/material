---
title: Starting the course
slug: starting
---

# Starting the course

This course is based on programming exercises where your task is to design efficient algorithms and implement them in the C++ programming language.

The course exercises are available in [CSES](TODO).

## Solving exercises

To participate in the course, you need a text editor to write code and a C++ compiler. The recommended compiler is g++, which is also used in CSES.

As an example, consider the first course exercise [Weird Algorithm](TODO). Here is a C++ program that solves the problem:

```cpp
#include <iostream>

using namespace std;

int main() {
    long n;
    cin >> n;
    cout << n << " ";
    while (n != 1) {
        if (n % 2 == 0) {
            n = n / 2;
        } else {
            n = 3 * n + 1;
        }
        cout << n << " ";
    }
    cout << "\n";
}
```

The following commands compile and run the above program in a Linux environment:

```
$ g++ test.cpp -o test -O2 -Wall
$ ./test
7
7 22 11 34 17 52 26 13 40 20 10 5 16 8 4 2 1
```

Here, the source code of the program is in the file `test.cpp`, and it is compiled into a binary file called `test`. The flag `-O2` enables standard optimizations when compiling the code, and the flag `Wall` tells the compiler to show all warnings.

## Learning C++

If you have not used C++ before, you need to learn basics of the language during the course. Note that C++ is a very complex language, and many advanced topics, such as object-oriented programming and templates, are only briefly covered in the course.

The first chapter of the course material is an introduction to C++. The [C++ tutorial](https://tie.koodariksi.fi/cppe/) at Tie koodariksi can also be a useful resource.

## Using Sources and AI

You can use any sources for learning C++ for the course. For example, if you don't know how to use priority queues in C++, you can freely search for information about them using any tools you like.

However, it is not allowed to search for information about how to solve a particular course exercise. It is a very bad idea to "solve" a course exercise by searching for a ready-made solution on the internet. The purpose of the course is that you learn problem solving, not information retrieval.

The above also applies to AI tools. You can use AI tools to learn C++, but it is not allowed to use them to solve problems. You can't use prompts like "can you help me with this exercise" in the course.
