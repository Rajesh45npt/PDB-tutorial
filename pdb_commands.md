|Commands|Explanation|
|:----|:-----|
__import pdb; pdb.set_trace()__ or __python -m pdb main.py__ | Incorporating pdb in main.py file.
l(ist) | Displays 11 lines around the current line or continue the previous listing.
s(tep) | Execute the current line, stop at the first possible occasion.
n(ext) | Continue execution until the next line in the current function is reached or it returns.
b(reak) | Set a breakpoint(depending on the argument provided). b without arguments prints the list of the breakpoints
r(eturn) | Continue execution until the current function returns
c(continue) | Executes the program and only stops if it encounters a break point!
h(help) | Prints the list of available commands. With a command as an argument, print help about that command
h(elp) l(ist) | Prints the help page for list
ll(long list) | shows source code for the current function or frame
cl(ear) | followed by breakpoint number will clear the breakpoint with that number as shown in __b(reak)__ command
__dir()__| inbuilt function in Python3 which returns the list of the arributes and methods of any object
exit() or CTRL+D or q(quit) | exit pdb
! | lets pdb know that the following statement will be a Python command and not a pdb command