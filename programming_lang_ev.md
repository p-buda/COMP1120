## Programming Languages
[S]oftware developers create software using one of several programming languages. A programming language is an artificial language that provides a way for a programmer to create structured code to communicate logic in a format that can be executed by the computer hardware. Over the past few decades, many different types of programming languages have evolved to meet many different needs. One way to characterize programming languages is by their “generation.”
### Generations of Programming Languages
Early languages were specific to the type of hardware that had to be programmed; each type of computer hardware had a different low-level programming language (in fact, even today there are differences at the lower level, though they are now obscured by higher-level programming languages). In these early languages, very specific instructions had to be entered line by line – a tedious process.

First-generation languages are called machine code. In machine code, programming is done by directly setting actual ones and zeroes (the bits) in the program using binary code. Here is an example program that adds 1234 and 4321 using machine language:

10111001 00000000

11010010 10100001

00000100 00000000

10001001 00000000

00001110 10001011

00000000 00011110

00000000 00011110

00000000 00000010

10111001 00000000

11100001 00000011

00010000 11000011

10001001 10100011

00001110 00000100

00000010 00000000

Assembly language is the second-generation language. Assembly language gives english-like phrases to the machine-code instructions, making it easier to program. An assembly-language program must be run through an assembler, which converts it into machine code. Here is an example program that adds 1234 and 4321 using assembly language:

MOV CX,1234

MOV DS:[0],CX

MOV CX,4321

MOV AX,DS:[0]

MOV BX,DS:[2]

ADD AX,BX

MOV DS:[4],AX

Third-generation languages are not specific to the type of hardware on which they run and are much more like spoken languages. Most third-generation languages must be compiled, a process that converts them into machine code. Well-known third-generation languages include BASIC, C, Pascal, and Java. Here is an example using BASIC:

A=1234

B=4321

C=A+B

END


Fourth-generation languages are a class of programming tools that enable fast application development using intuitive interfaces and environments. Many times, a fourth-generation language has a very specific purpose, such as database interaction or report-writing. These tools can be used by those with very little formal training in programming and allow for the quick development of applications and/or functionality. Examples of fourth-generation languages include: Clipper, FOCUS, FoxPro, SQL, and SPSS.

Why would anyone want to program in a lower-level language when they require so much more work? The answer is similar to why some prefer to drive stick-shift automobiles instead of automatic transmission: control and efficiency. Lower-level languages, such as assembly language, are much more efficient and execute much more quickly. You have finer control over the hardware as well. Sometimes, a combination of higher- and lower-level languages are mixed together to get the best of both worlds: the programmer will create the overall structure and interface using a higher-level language but will use lower-level languages for the parts of the program that are used many times or require more precision.

![Programming Languages Spectrum](COMP1120/image/Programming-Languages-Spectrum.png  "The programming language spectrum")

The programming language spectrum

---
This page was copied and modified from [Information Systems for Business and Beyond](https://bus206.pressbooks.com/chapter/chapter-10-information-systems-development/) by David T. Bourgeois, Ph.D. and is licensed under [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/)
