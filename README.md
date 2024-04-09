![CMPSC 201: Programming Languages origami fish in various states of structural unmaking](https://github.com/allegheny-college-cmpsc-201-spring-2024/course-materials/assets/1552764/7eef390d-327d-4af6-94ed-e7cc41c97df8)

# CMPSC 201: Course Project

This cumulative and summative course project contemplates three potential paths for students to take, as defined in the
course syllabus:
> * Students may choose to implement the Lox interpreter in a language other than Java which implements one additional significant feature not present in the current Lox implementation
> * Students may choose to develop a "code golfing" language which solves the golfing challenges undertaken during the semester<sup>†</sup>
> * Students may choose to develop a "golfed" version of the `jlox` interpreter

<sup>†</sup> Additional holes released _after_ the project has been assigned will be provided by the instructor on the appropriate branch(es)

## Rules

* you may only choose `1` of the projects to complete
* projects and relevant documentation must be completed and `push`ed to GitHub by `12:00 PM, 6 May, 2024`
* projects and relevant documentation must be completed on the appropriate branch of this reposistory

## Evaluation

Project evaluation derives from the individual project chosen. Each branch contains its own evaluation via the `gatorgrade` platform, as each
considers dramatically different approaches to course topics. Common to all projects:

* a programmatic outcome (i.e. ability to execute a novel program successfully)
* accompanying documentation exploring application of technical concepts

For transparency's sake, the remainder of this document will describe each project in moderate detail.

### Reimplementing `Lox` in another language

This course implemented the `Lox` language using Java, the key word in the sentence being _implemented_; `Lox` proposes a set of rules that can
be implemented in many other languages. Java is the choice that our textbook's author made. Readers of _Crafting Interpreters_ [have ported the language
to a wide variety of other languages](https://github.com/munificent/craftinginterpreters/wiki/Lox-implementations) -- even `Lox` itself!

Students are invited to tacle this challenge by choosing a language in which they'd like to implement `Lox`, including those in which there're already
implementations. However, for an extra challenge, students might consider using:

* Aya
* Jactl
* Lark

or any other language in which there's not currently an active implementation. If students complete an implementation in an unrepresented language,
they might earn an entry on the `Lox` wiki!

This project will be evaluated by its ability to run a novel program written in the `Lox` language.

### Developing a code golfing language

Much in the tradition of languages such as `CJam`, `Jelly`, `J`, `APL`, and others! [Discussion of desirable features](https://codegolf.stackexchange.com/questions/2070/choosing-languages-for-golfing) 
may help students pursing this path to determine the predominate features they'd like to include in their language. The true test: can your language
solve all of the holes that we've completed as part of our ACGA challenge?

To successfully complete this project, students' language must solve all of the code golf challenges provided throughout the semester.

### Golfing the `Lox` interpreter

How small can someone make the `Lox` interpreter? While this project assumes that students will most likely use the `Java` programming language, this 
project can be combined with rewriting the interpreter in a new or novel language. With a current codebase size of over 59K bytes, there's quite a bit
of progress to be made.

This project will be evaluated by its ability to run a novel program written in the `Lox` language in addition to assessing the amount of code removed.
`50%` of the project relies on execution and `50%` on the reduction schedule below:

|Codebase size reduction | Score impact |
|:-----------------------|:-------------|
|2K                      | +10%         |
|4K                      | +20%         |
|6K                      | +30%         |
|10K                     | +40%         |
|12.5k+                  | +50%         |
