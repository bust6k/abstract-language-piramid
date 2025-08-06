# abstract-language-piramid: greetings
The abstract pyramid of languages is a pyramid that allows you to determine how close a language is to hardware (i.e. how high-level it is) by the number of abstractions provided to the language. The pyramid has a simple structure, so you can easily determine how close a language is to hardware, without complex criteria.

# abstract-language-piramid: structure
as was said, the structure of the abstract pyramid of languages is not complicated, so in a couple of dozen words you will learn how to impose a language on the pyramid, and understand how high-level it is:

### abstract-language-piramid:  Pyramid struct:
The abstract language pyramid has 5 levels of high-level language. Here is a brief description:

- machine code (0 abstractions). This is the level where the programmer literally controls every bit of the program.
commercial applications are not written in machine code, because it requires deep knowledge, and a lot of patience. Example: Machine code in   Hex format, Machine code in Binary format


- Assembler level (1 abstraction). This is the level where the programmer still writes each processor instruction by hand, but the programmers write not raw bytes, but at least somewhat understandable text. Commercial applications are not written in languages of this level these days, as it still requires deep engineering knowledge of the computer. Examples: Nasm,Fasm,Masm


- low-level languages (2-10 abstractions) is the level at which the language already starts doing the work for the programmer, even the dirtiest work. The programmer does the rest. This is the first level of languages, from which commercial applications are still written. Examples: C/C++,HolyC,Rust


- High-level languages (11-50 abstractions) are the level at which the language not only does the dirty work, but also tries to hide the most complexities of low-level languages. For example, pointers. Despite this, the programmer still has basic control over his program. Commercial applications are most often written in languages of this level.  Examples: Go,Java,C#,Fortran,Cobol


- very high-level languages (50+ abstractions) are the level at which the language tries to do all the main work of the programmer with the hardware, abstracting the programmer from the bits as much as possible. Languages of this level forgive many mistakes, as if this is a letter for a person and not instructions for a processor.  Examples : Python,Js,Php

### abstract-language-piramid: how to put tongue on pyramid
it is quite easy to understand how high-level a language is, you just have to look at how human-friendly the language is. Here are some examples of reasoning:

- the language requires the deepest knowledge of computer since, as well as excellent brain memory. This language makes you write every bit (or byte). So, it is more likely that this language is at the machine code level


- the language still requires deep knowledge of computer since, but gives the indulgence of not writing every bit (or byte) and also allows you to write comments to the code so as not to forget. Most likely, this is a language at the level of assembly languages

- the language still requires direct work with pointers, data structures, but allows writing more or less like a human? most likely these are low-level languages

- the language does not require deep knowledge of computer since, but it makes you at least in theory, in the general picture, understand the basics of computer since? the language can be read as a human letter from a person who does not know the language well (for example, English)? most likely it is a high-level language

- does the language require only knowledge of English and a little patience to understand the keywords of the language? does it not require working with pointers and static arrays? most likely it is a very high level language
