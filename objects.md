to create an object of a class we can either create it in the stack or the heap, but we should know that the stack is much faster than the heap. why?
because each time we try to allocate something in the heap. the OS will have to search for a proper location and a proper size for the object we're trying
to create. ex: if we want to allocate an object that needs 8bytes the OS will have to search for a continues block of memory in that has 8bytes and allocate it.
also in the heap you are responsible for the memory, after you allocate it you have to free it. whereas in the stack, at the end of each scope all the allocated memory will be freed automatically.
