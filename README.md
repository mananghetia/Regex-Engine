# Regex-Engine

Custom regular expression engine in Scala, leveraging NFA-based matching, recursive descent parsing, and algorithmic optimizations to improve performance and accuracy.

Regular expression language will support:

'.' : Match any character

'|' : Match abc or cde

'+' : Match one or more of the previous pattern

'*' : Match 0 or more of the previous pattern

'(' and ')' for grouping

Evaluate regular expressions in 3 phases:

- Parse the regular expression into a syntax tree
- Convert the syntax tree into a state machine
- Evaluate the state machine against our string
