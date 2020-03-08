# Ideal-village
|asdf|asdf|
|-|-|
|dfas|asdf|

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
  dateFormat  YYYY-MM-DD
  title Adding GANTT diagram to mermaid

  section A section
  Completed task            :done,    des1, 2014-01-06,2014-01-08
  Active task               :active,  des2, 2014-01-09, 3d
  Future task               :         des3, after des2, 5d
  Future task2               :         des4, after des3, 5d

  section Critical tasks
  Completed task in the critical line :crit, done, 2014-01-06,24h
  Implement parser and jison          :crit, done, after des1, 2d
  Create tests for parser             :crit, active, 3d
  Future task in critical line        :crit, 5d
  Create tests for renderer           :2d
  Add to mermaid                      :1d

  section Documentation
  Describe gantt syntax               :active, a1, after des1, 3d
  Add gantt diagram to demo page      :after a1  , 20h
  Add another diagram to demo page    :doc1, after a1  , 48h

  section Last section
  Describe gantt syntax               :after doc1, 3d
  Add gantt diagram to demo page      : 20h
  Add another diagram to demo page    : 48h

```mermaid
graph TD
A[模块A] -->|A1| B(模块B)
B -->|A1| C{判断条件C}
C -->|条件C1| D[模块D]
C -->|条件C2| E[模块E]
C -->|条件C3| F[模块F]
```
