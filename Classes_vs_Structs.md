There is no difference between 'struct' and 'class' keywords they mean the same thing and behave in the same way.
the only difference is that by default member variables and member function in a Class are private unless specified otherwise; for example:
```
class A {
  int x, y;
};

struct B {
  int x, y;
 }
 ```
 in class A, x and y are private by default, but in the struct B they are public.
