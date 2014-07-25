Turing-Machine
==============

A simple Turing Machine using Python

method __str__(self) is defined for the class Tape. 
__str__(self) is called by str() function and the print function uses it to calculate the "informal" string representation of an object, the tape of the Turing Machine. 
The print function in the method show_tape() of our class TuringMachine makes uses it. 

__getitem__() method is udes to form a reading access to the tape via indices. 

__setitem_()  method also provides writing access.
self.__tape[self.__head_position] = y[1] of our class TuringMachine implementation" 

The class TuringMachine: We define the method __str__(self), which is called by the str() function and by print statement to compute the "informal" string representation of an object, the string representation of a tape.

