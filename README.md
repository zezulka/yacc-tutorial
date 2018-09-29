Steps to build the library:
1. Install the ```yacc``` package (tested on the byacc package)
2. ```yacc -d calc.y``` - this will generate the parser
3. ```lex calc.l``` - this will generate the lexer
4. ```gcc lex.yy.c y.tab.c -o calc``` - the executable should be generated
