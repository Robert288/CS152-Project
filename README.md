## Phase 1
For this first part of the class project, I used the flex tool to generate a lexical analyzer for a high-level source code language called "MINI-L". The lexical analyzer should take as input a MINI-L program, parse it, and output the sequence of lexical tokens associated with the program.

## Phase 2
In this phase of the class project, I created a parser using the bison tool that will check to see whether the identified sequence of tokens adheres to the specified grammar of MINI-L. The output of my parser will be the list of productions used during the parsing process. If any syntax errors are encountered during parsing, my parser emits appropriate error messages.

## Phase 3
In this phase of the class project, I took a syntactically-correct MINI-L program (a program that can be parsed without any syntax errors), verified that it has no semantic errors, and then generated its corresponding intermediate code. The intermediate code I generated is called "MIL" code. I used an interpreter called mil_run that can be used to execute the MIL code. The output of my code generator will be a file containing the generated MIL code. If any semantic errors are encountered by the code generator, then appropriate error messages will be emitted and no other output will be produced.
