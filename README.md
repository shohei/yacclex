```sh
% yacc -dv mycalc.y 
% lex mycalc.l     
% cc -o mycalc y.tab.c lex.yy.c 
# or 
# bison mycalc.y
# cc -o mybcalc mycalc.tab.c lex.yy.c
```
