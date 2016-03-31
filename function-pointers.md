# function-pointers

Type of pointer is the return type, then the name of the pointer and
then the ARGUMENT TYPES.

int (* func) (int, double);

Is a function pointer called func returning an int and taking arguments of
type int and double.

You don’t need to take the memory address or dereference functions,
because you can only call a function or take it’s address again.

int func(int x) { return x; };

int (* pointer_to_func) (int) = func; // & not necessary

pointer_to_func(5); // * not necessary
