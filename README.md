# SimpleYaccLexExample
A simple example of lexical  analysis and parsing of C language using Yacc and lex

# the ANSI C grammar in yacc & lex was written by Jeff Lee
here is the Original source:
http://www.lysator.liu.se/c/


http://www.lysator.liu.se/c/ANSI-C-grammar-y.html


http://www.lysator.liu.se/c/ANSI-C-grammar-l.html



### Usage
1.Compile lexical file


 lex Cgrammar.l
 
 
2.Complie grammar file


 yacc Cgrammar.y -dv
 
 
3.build your target


 cc lex.yy.c y.tab.c -ll
 
 
4.run it!


./a.out

