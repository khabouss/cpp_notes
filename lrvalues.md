lvalue has two components 1) value 2) address
rvalue has only 1) value

On right hand side of assignment
1. As rvalue only has value, it's value is used
2. As lvalue has both value and address, what gets used depends on left hand side expression

On left hand side of assignment
1. Only address part of lvalue is used
2. As rvalue doesn't have address, it cannot be used

rvalue reference is just an optimization hack.


example:
```
int a = 42;
  --^.   ^---- 
 lvalue       rvalue
 ```
