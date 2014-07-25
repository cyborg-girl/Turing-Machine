Turing-Machine
==============

A simple Turing Machine using Python

<b>method __str__(self)</b> is defined for the class Tape. 
<b>__str__(self)</b> is called by <b>str()</b> function and the print function uses it to calculate the "informal" string representation of an object, the tape of the Turing Machine. 
The print function in the method <b>show_tape()</b> of our class TuringMachine makes uses it. 

<b>__getitem__()</b> method is udes to form a reading access to the tape via indices. 

<b>__setitem_()</b>  method also provides writing access.
<b>self.__tape[self.__head_position] = y[1] </b> of our class TuringMachine implementation" 

<b>The class TuringMachine:</b> We define the method <b>__str__(self)</b>, which is called by the <b>str()</b> function and by print statement to compute the "informal" string representation of an object, the string representation of a tape.

