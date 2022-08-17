→ Use the new keyword to allocate a specified memory size on the heap in bytes (ex. Int would take 4 bytes of memory)

→ operating systems must then go and find a contiguous block of memory to match the requested variable type and return a pointer to that memory address.

→ With a class, it will determine the size of the class and then find a memory allocation

→ with arrays it will calculate the type of array and multiply by the size of the array. //int * 50 = 200

→ The new keyword not only allocates memory, but also calls the constructor

→ don't forget to use the delete keyword when we use the new keyword.

→ if we use new keyword with array like new int[], use delete keyword like delete[]

→ use placement new to i.e new(b) to choose the location of where the memory is stored

