Download Link: https://assignmentchef.com/product/solved-605-202-project0-implement-a-decimal-to-binary-converter-with-a-stack
<br>
Implement a decimal to binary converter with a stack.

Changing the base of numbers is a common operation in digital computing systems.  Human input is generally in base-10, but most common computers operate in base-2.

A standard technique for converting base-10 numbers to base-2 numbers is to divide the base-10 number by 2 repeatedly, saving the remainder and result in separate areas.  When the remainder vanishes, the results are reversed in sequence to produce the base-2 (binary) answer.

Example:  If a base-10 (decimal) number = 12, then the base-2 (binary) number = 1100.




12/ 2 = 6 rem 0   6 / 2 = 3 rem 0

3 / 2 = 1 rem 1

1 / 2 = 0 rem 1




Reverse 0, 0, 1, 1 to get 12 [decimal] = 1100 [binary]




The student will implement a conversion routine that will convert an unsigned decimal integer into a binary number that can fit into a 32-bit CPU register.  The program is expected to gracefully handle negative integers and decimal numbers that are too large for representation by 32 bits.

<table>

 <tbody>

  <tr>

   <td width="48"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>




In your Analysis consider the possible use of recursion.




Input for the program will be a simple text file.  Each line of the text file will be a simple decimal number.  The input file must fully exercises possible evaluation sequences and input errors.




Output for the program will be a text file that contains three items in sequence:        —  A line for each decimal number in the input file.  The output for           each line will be a numerical 32-bit representation of the decimal      number or an error message that describes the problem.  The

32-bits will be divided into groups of four bits, with leading            zeros.

—  A report of the total number of conversions successfully done.  —  A list of metrics, for use in the Analysis.




Required Input:

2

3

5

10

100

1000000

1000000000

10000000000104420