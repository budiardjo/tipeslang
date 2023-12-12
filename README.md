## Design Decision tipes language 

### Parsing 
let's first decide we gonna using parsing generator or hand written. based on The Design and Evolution of C++, 1994 by bjarne stroustup 
> Al Aho and Steve Johnson were in the Computer Science Research Center and they, primarily Steve, convinced me that writing a parser by hand was most old-fashioned, would be an inefficient use of my time, would almost certainly result in a hard-to-understand and hard-to-maintain parser, and would be prone to unsystematic and therefore unreliable error recovery. The right way was to use an LALR(l) parser generator, so I used Al and Steve's YACC [Aho,1986].

so what? it is on 1986 and advice from god tier alfred aho so let just jump design it with parser generator recursive descent parser. but what if we want a hand written parsers is it true after 30 years no one using hand written parser anymore?, there is a good blog written in here [parser survey](https://notes.eatonphil.com/parser-generators-vs-handwritten-parsers-survey-2021.html) a tool like bison and yacc had a drawback for generate a language and end up being "hacky" things.
   



















### Example 

### Parser
- https://github.com/ziglang/zig/blob/master/lib/std/zig/Parse.zig
- https://github.com/apple/swift/blob/main/include/swift/Parse/Parser.h 

### Implementation
- https://github.com/drh/lcc
- https://github.com/munificent/craftinginterpreters

### Source, Books, Papers
- SSA-based Compiler Design by Fabrice Rastello
- Modern Compiler Implementation in C by Andrew W.Appel
- Compilers: Principles, Techniques, and Tools, by Alfred V. Aho
- Retargetable C Compiler by David Hanson
- [Crafting Interpreters](craftinginterpreters.com)
