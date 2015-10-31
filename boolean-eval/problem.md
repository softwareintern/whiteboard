# boolean evaluation
Given a boolean expression consisting of the symbols 0 (false), 1 (true), & (and), | (or), ^ (xor),
and a desired boolean result value `result`, implement a function to count the number of ways of parenthesizing the expression such that it evaluates to result. The expression should be fully parenthesized (1)^(0) but not extraneously ((0))^((1)).

examples
  - countEval("1^0|0|1", false) returns 2
  - countEval("0&0&0&1^1|0", true) returns 10
  
## sources
  - CTCI 8.14 pg.
