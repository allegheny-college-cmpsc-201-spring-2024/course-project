![CMPSC 201: Programming Languages origami fish in various states of structural unmaking](https://github.com/allegheny-college-cmpsc-201-spring-2024/course-materials/assets/1552764/7eef390d-327d-4af6-94ed-e7cc41c97df8)

# CMPSC 201: Golfing the `Lox` interpreter

This project branch brings together skills developed during code golf challenges and weekly lab sessions to "golf" (or minimize the size of) the `Lox`
interpreter. Information important for completing this task includes:

* [Tips for golfing in Java](https://codegolf.stackexchange.com/questions/6671/tips-for-golfing-in-java)
* [_Crafting Interpreters_](https://craftinginterpreters.com/)
* [CMPSC 201: Course slides](https://github.com/allegheny-college-cmpsc-201-spring-2024/course-materials/tree/main/docs)

As mentioned in the larger description, it's possible to _not only "golf" the language_, but to combine this with another project option: reimplementing
the `Lox` interpreter. Students who successfully complete these dual objectives will receive a `10%` course grade bonus.

> How small can someone make the `Lox` interpreter? While this project assumes that students will most likely use the `Java` programming language, this 
> project can be combined with rewriting the interpreter in a new or novel language. With a current codebase size of over 59K bytes, there's quite a bit
> of progress to be made.
> 
> This project will be evaluated by its ability to run a novel program written in the `Lox` language in addition to assessing the amount of code removed.
> `50%` of the project relies on execution and `50%` on the reduction schedule below:
>
> |Codebase size reduction | Score impact |
> |:-----------------------|:-------------|
> |20K                      | +10%         |
> |22K                      | +20%         |
> |25K                      | +30%         |
> |30K                      | +40%         |
> |35k+                     | +50%         |

## Requirements

* projects must remove at least `20K` bytes to count as an attempt
* (if golfing in `Java`) revise the language in `interpreter/main/java/com/interpreter/lox`
* the final program must run the novel program contained in the `src/test/resources/` folder
* documentation must be complete
