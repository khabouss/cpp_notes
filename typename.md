typename is a keyword that used to tell the compiler that the name next to it is a data type not a value, in some situation the compiler think that a name is a value which in fact is not.
Following is the quote from Josuttis book:

The keyword typename was introduced to specify that the identifier that follows is a type. Consider the following example:
```
template <class T>
Class MyClass
{
  typename T::SubType * ptr;
  ...
};
```
Here, typename is used to clarify that SubType is a type of class T. Thus, ptr is a pointer to the type T::SubType. Without typename, SubType would be considered a static member. Thus

T::SubType * ptr
would be a multiplication of value SubType of type T with ptr.
