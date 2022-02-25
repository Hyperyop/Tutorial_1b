# Some potential issues:
- we allocate memory from heap that are never freed.
- To solve this problem an approach would be to make a local variable in pointer.c and copy the instance from the heap to it then freeing it.