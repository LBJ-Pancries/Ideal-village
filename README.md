# Ideal-village
```mermaid
  flowchat
  st=>start: Start
  e=>end: End
  op1=>operation: Operation
  sub1=>subroutine: Subroutine
  cond=>condition: yes or no ?
  io=>inputoutput: proceess something...
  st->op1->cond`
  cond(yes)->io->e`
  cond(no)->sub1(right)->op1
​```


graph TD
  B[bname]
  C(cname)
  D((dname))
  E>ename]
  F{fname}


graph TD
  A1==TEXT===B1
  A2-->|text|B2
  A3..-B3

gantt
　　　dateFormat　YYYY-MM-DD
　　　title Adding GANTT diagram functionality to mermaid
　　　section A section
　　　Completed task　　:done, des1, 2014-01-06,2014-01-08
　　　Active task 　　　　:active, des2, 2014-01-09, 3d
　　　future task 　　　　:　　　  des3, after des2, 5d
　　　future task2　　　　:　　　  des4, after des3, 5d
　　　section Critical tasks
　　　Completed task in the critical line　:crit, done, 2014-01-06,24h
　　　Implement parser and json　　　　　　:crit, done, after des1, 2d
　　　Create tests for parser　　　　　　　:crit, active, 3d
　　　Future task in critical line　　　　　:crit, 5d
　　　Create tests for renderer　　　　　　:2d
　　　Add to ,mermaid　　　　　　　　　　　:1d
