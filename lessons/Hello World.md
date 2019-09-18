# Hello World
###### Topics: Python Installation, Python, Hello World Example, Operating System Concept

###### Sources:
---
- [Windows Version Check ](https://support.microsoft.com/en-us/help/13443/windows-which-version-am-i-running)
- [Python Install tutorial](https://realpython.com/installing-python/#step-1-download-the-python-3-installer)

---

### Overview
Congratulations on taking a great step forward as you learn programming! The goal of this lesson is to install Python on your computer (a laptop or desktop will work). Then, we're going to write a `Hello World` program.

---
_A "Hello, World!" program generally is a computer program that outputs or displays the message "Hello, World!". Such a program is very simple in most programming languages, and is often used to illustrate the basic syntax of a programming language. It is often the first program written by people learning to code._

---
Source: [Wikipedia Article about Helloworld](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program)


There are different instructions for different operating systems. We'll detail Windows, below, but another site we found has a much more inclusive installation step for other operating systems.

### Python Install Steps for Windows
1. Navigate to the download page for Python: https://www.python.org/downloads/ and chose your operating system. Python is a programming language. There are many programming languages, but we've chosen Python since it has a fairly accessible syntax. Also, it works well with a lot of other tools that will be useful for you in the future.

2. Choose Python 3.6.7 for the operating system (OS) of your computer. These introductory lessons are based around Python 3.6.7 In the future, a different version of Python might be available. In that case, use a later version of Python if you want to live life on the edge (sometimes that happens in programming, and your learning so it's alright to try it out). If the later version of Python doesn't work, we suggest uninstalling it and installing Python 3.6.7.

3. Scroll to the bottom of the page and select either __Windows x86-64 executable__ installer for 64-bit or __Windows x86 executable installer__ for 32-bit. (See below.)

  If you're running a Windows machine, you might need to view [this](https://support.microsoft.com/en-us/help/13443/windows-which-version-am-i-running) page to see whether you have a 32-bit system or a 64-bit system.

  [This](https://realpython.com/installing-python/#step-1-download-the-python-3-installer) page might also help you. too, if you get stuck.

4. Run the Installer

  Important: You want to be sure to check the box that says __Add Python 3.x to PATH__ as shown to ensure that the interpreter will be placed in your execution path.

### Python Install Steps for another OS

[This](https://realpython.com/installing-python/#step-1-download-the-python-3-installer) page should guide you through the installation steps. `Ctrl-F` (Find in page) your operating system name to see the steps for your OS.

### Your First Program
1. Open a terminal (Linux/Mac) or command prompt (Windows)

  Note: Close the terminal by typing `exit`

2. Type `python3` (Note: you might need to type a varient of this; `python3.6` or something linke that). Hit enter, and the Python interpreter will open.

  Note: Close the interpreter by typing `exit()`

3. You should see something like this:
  ```
  >>>
  ```

4. Type `print('Hello World')`:
  ```
  >>> print('Hello World')
  ```

  Result:
  ```
  >>> print('Hello World')
  Hello World
  ```
5. Congratulations! You've written a 'Hello World' program in Python. Now's it time to become a better programmer! The next lesson is [Install an IDE](https://github.com/omegahorizontech/introductory-programming/blob/master/lessons/Install%20An%20IDE.md). From here on out, we're going to be less verbose in our instructions so that you get the hang using the Internet to answer other questions we might miss.

---

### Recap
- We learned about the notion of an operating system.
- We discovered that a programming language like Python might need different configuration steps based on the computer's OS.
- We installed Python on our computer.
- We learned how to open the Python interpreter
- We learned how to write a program inside of the interpreter.
