*Sebastian Brumm*
*Assignment 1*
*3/18/22*

*How to run:
*Compile with bnfc -m -haskell Cpp.cf
*and then make
*and then run either the test suite or a custom script

*Notes:
*There are 4 shift/reduce conflicts and no reduce/reduce conflicts. The shift/reduce conflicts are mainly cases of there being additions to statements, such as if/else and just if, that leads to ambiguous grammar. This is unavoidable due to the nature of these statements and will not result in any errors in parsing due to the additional keywords associated with them. The other conflicts are due to custom types that I created to make the grammar easier to understand, the name and dec types, and to allow for easy implementation of structures.
