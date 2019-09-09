# CPE 1040 - Introduction to Computer Engeneering

## Assignment: First Microbit Program in Blocks

### 1. Summary

This assignment asks you to "write" your first micro:bit program in Blocks, and introduces you to working with Github.

### 2. Requirements

1. You need to write the program yourself. _**Note:** It is very important that you take the time to do that, without copying other programs, following step-by-step tutorials or guides, or flipping back and forth between an already written program while writing your own._

2. The program doesn't have to be very complicated, but it also shouldn't be basic. It should have:
   - input (buttons, motion sensor, temperature, or GPIO pin resistance)
   - output (5x5 LED matrix)
   - some computation (you should take some data and process it)
   - looping (do something repeatedly, including but not limited to a "forever" loop)

3. Look at the [resources](#resources) for ideas.

4. Test your program on your micro:bit until you are satisfied.

### 3. Working with Github Classroom

1. [Github](https://github.com) is a collaborative environment for software projects, and is built on top of the version-control system [Git](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F).

2. Follow the [Github Installation](#github-installation) instructions for your operating system.

3. For each assignment from Github Classroom, you will receive an invitation to join it. _**Note:** The assignments are required work, so, if you want to submit an assignment, joining is not optional._

4. From the repository of the assignment, copy the _clone URL_ (green button top right). _**Note:** Will demonstrate and practice in class the week of Sep 2._

5. Open your Git terminal and type 'git clone [URL]' you just copied, to _clone_ the repository in your local development environment. This creates a directory with the name of the repository. Change into this directory. _**Note:** Will demonstrate and practice in class the week of Sep 2._

6. Copy the '.hex' file of your program from the [Requirements](#requirements) into the assignment repository clone directory (the one in (5)).

7. Type 'git status' to verify that the Git system has recognized the new file. _**Note:** Will demonstrate and practice in class the week of Sep 2._

8. Type 'git add [name-of-file.hex]' to add the new file to version control by Git. _**Note:** Will demonstrate and practice in class the week of Sep 2._

9. Type 'git commit -m "Some informative message about the changes"'. The message can be "Initial commit", "Assignment completed", or whatever. The point is that, when you read it later, you will recall what you did and the purpose of the commit. _**Note:** Will demonstrate and practice in class the week of Sep 2._

10. Type 'git push' to submit your assignment. _**Note:** Will demonstrate and practice in class the week of Sep 2._

11. Go to the assignment webpage and refresh, if necessary. Your '.hex' file will show in the repository. _**Note:** Will demonstrate and practice in class the week of Sep 2._

12. Create a new file, called 'description.md'. 'md' is a file extension which means "Markdown". It is the same kind of file as the one you are reading. Markdown is a very simple markup language, which adds HTML-style formatting to your content without the burden of HTML syntax.

13. Write a short description of your micro:bit program. Use some markdown formatting, to practice. Here is the [Github Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## Resources

1. [micro:bit lessons](https://makecode.microbit.org/lessons).

2. [micro:bit ideas](https://microbit.org/ideas/).

3. A list of some more [advanced projects](https://www.itpro.co.uk/desktop-hardware/26289/13-top-bbc-micro-bit-projects).

4. The [projects](https://www.itpro.co.uk/desktop-hardware/26289/13-top-bbc-micro-bit-projects) at the [awesome micro:bit list](https://github.com/carlosperate/awesome-microbit).

## Github Installation

1. On Linux or MacOS, you probably already have 'git' installed. Type 'which git' in a terminal to verify. If not, download and install from the [Git website](https://git-scm.com/) (it will recognize your OS and will offer you to download the appropriate installer package).

2. For windows, to the [Git website](https://git-scm.com/) (it will recognize your OS and will offer you to download the appropriate installer program).
