# CPE 1040 - Introduction to Computer Engeneering

## Assignment: Migrating micro:bit Programming from Blocks to JavaScript

### 1. Summary

This assignment asks you to go through a [Intro to CS course with Blocks](https://makecode.microbit.org/courses/csintro) for the micro:bit, and write parallel programs using the JavaScript equivalent of the code in the course modules. This assignment is submitted through Github.

### 2. Requirements

#### 2.1 Section programs

1. The CS course is broken down into thematic sections. There are 5 sections + 1 midterm project + 5 sections + final project.

2. You need to write a _working_ JavaScript (JS) program for the micro:bit for each of these sections/projects, for a total of 12.  

3. For the non-project sections, you are required to use the JS equivalent of the material from the section. _**Note:** For these programs, you are allowed to look at the JS translation of Blocks programs._

4. For the midterm project, you are required to use the JS equivalent of the material from all 5 preceding sections.  _**Note:** For this project, you are NOT allowed to look at the JS translation of Blocks programs._ (An aside: if you don't know how to read a statement like "you are not allowed to", the intended and preferred interpretation is "you can do whatever you want and won't be penalized by me, but, if you want to learn most effectively, I suggest that you do not resort to...".)

5. For the final project, you are required to use the JS equivalent of the material from all 10 preceding non-project sections. _**Note:** For this project, you are NOT allowed to look at the JS translation of Blocks programs._

#### 2.2 Github commits & tags

1. You need to commit the changes and additions to your assignment for each section or project. This means that there should be _at least_ 12 commits pushed to your remote assignment repository on Github when you are done. I advise you to have more than that, to get used to it.

2. You need to **tag** the final commit for each section. Tags are under _releases_ in the repository bar on the Github page of the assignment repository. The tag should be one of the following `v0.1`, `v0.2`, ..., `v0.12`, for each section, respectively. (Terminology clarification: The `git` command is `git tag`, but tags are counted as _releases_ on Github.)

3. You need to update the assignment repository [README.md](README.md) (this document, in the section [Tags](#tags)) with a short description of your section program or project, **before** you tag.


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

TODO: JavaScript/TypeScript references

1. [micro:bit lessons](https://makecode.microbit.org/lessons).

2. [micro:bit ideas](https://microbit.org/ideas/).

3. A list of some more [advanced projects](https://www.itpro.co.uk/desktop-hardware/26289/13-top-bbc-micro-bit-projects).

4. The [projects](https://www.itpro.co.uk/desktop-hardware/26289/13-top-bbc-micro-bit-projects) at the [awesome micro:bit list](https://github.com/carlosperate/awesome-microbit).

## Github

Github Tutorial for Beginners ([webpage](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)).
Github Basics for Mac and Windows ([video](https://www.youtube.com/watch?v=0fKg7e37bQE)).
git & Github Crash Course for Beginners ([video](https://www.youtube.com/watch?v=SWYqp7iY_Tc)).
Introduction to Github for Beginners ([video](https://www.youtube.com/watch?v=fQLK8Ib_SKk)).
About `git` ([webpage](https://git-scm.com/about)).
`git` [documentation](https://git-scm.com/doc) (webpage, book, videos, reference manual).

## Tags

_**Note:** Add your program descriptions below._

### v0.1

**[your description here, linking to the JavaScript [file](example.js)**]
