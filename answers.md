Subroutines - A set of Instructions which are used repeatedly in a program can be referred to as Subroutine. Only one copy of this Instruction is stored in the memory. When a Subroutine is required it can be called many times during the Execution of a Particular program. A call Subroutine Instruction calls the Subroutine. Care Should be taken while returning a Subroutine as Subroutine can be called from a different place from the memory.

Bitwise Operation AND/OR - If in a AND situation where there is a lower and higher number the lower number is the result and with OR vice versa. Otherwise if the numbers are the same the result will be the same.

Binary to Hexadecimal conversion - To convert Binary to Hexadecimal Conversion either use solution A or B.

A: binary_string = "1010"
   decimal_representation = int(binary_string, 2)
   hexadecimal_string = hex(decimal_representation)

   print(hexadecimal_string)

B: binary_string = "1010010101"
   First you must separate the string into quadrants of fours [10][1001][0101]
   Second starting from the first number set each number to the power of 2 starting at 8 and dropping after each number 
   [0(8)0(4)1(2)0(1)]
   [1(8)0(4)0(2)1(1)]
   [0(8)1(4)0(2)1(1)]
   Third once you have the results of the equation you take the results of each power and add them to a combined digit anything above 9 is a letter
   Fourth concatenate the results and that is your hexadecimal conversion.