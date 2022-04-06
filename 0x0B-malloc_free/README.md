
Malloc function is used to allocate a certain amount of memory from the heap. If the request is granted, the operating system will reserve the requested amount of memory and malloc will return a pointer to the reserved space.

when the amount of memory is not needed anymore, you must return it to the operating system by calling the function free

When you declare a variable or when you use strings within double quotes, the program is taking care of all the memory allocation.