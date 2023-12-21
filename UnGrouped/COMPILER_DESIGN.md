2023-09-04  ---  18:50
Type : Notes
___
# INTRODUCTION

### The Parts of a Compiler
Compilers are complex programs, as a consequence, they're often broken into several chunks, called <b><i>passes</i></b>, that communicate with one another via temporary files. Here, we define a compiler as <b><i>as a program or group that translates one language into another</i></b>.

### The Lexical Analyzer
A <i>phase</i> is an independent task used in the compilation process. Typically, several phases are combined into a single pass. The <b><i>lexical analyzer</i></b> phase of a compiler (often called a <i>scanner</i> or <i>tokenizer</i>) translates the input into a form that's more useable by the rest of the compiler. The lexical analyzer looks at the stream as a collection of basic language elements called <b><i>tokens</i></b>. That is, a token is an indivisible lexical unit. In C, keywords like <b>while</b> or <b>for</b> are tokens, symbols like >, >=, >>, and >>= are tokens, names and numbers are tokens, and so forth. The original string that comprises the token is called a <b><i>lexeme</i></b>. A lexical analyzer translates <b>lexems</b> into <b>tokens</b>.

---


---
### References

---