in the following code snippet:
```
int main()
{
  int a = 5;
  int b = a;
}
```
we are copying the content of the variable 'a' into a new variable 'b' in a different memory location, in other word we have now to values in our memory.
but in this example:
```
int main()
{
  int a = 5;
  int* b = &a;
}
```
we are only copying the address of 'a' instead of its content which is more memory efficient. it's better to avoid copying as much as possible.
