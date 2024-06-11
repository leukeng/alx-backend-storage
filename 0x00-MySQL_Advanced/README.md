SOLUTION TO 0x00. MySQL advanced


Chapter 12 Functions and Operators
Table of Contents

12.1 Built-In Function and Operator Reference
12.2 Loadable Function Reference
12.3 Type Conversion in Expression Evaluation
12.4 Operators
12.5 Flow Control Functions
12.6 Numeric Functions and Operators
12.7 Date and Time Functions
12.8 String Functions and Operators
12.9 Full-Text Search Functions
12.10 Cast Functions and Operators
12.11 XML Functions
12.12 Bit Functions and Operators
12.13 Encryption and Compression Functions
12.14 Locking Functions
12.15 Information Functions
12.16 Spatial Analysis Functions
12.17 JSON Functions
12.18 Functions Used with Global Transaction Identifiers (GTIDs)
12.19 Aggregate Functions
12.20 Miscellaneous Functions
12.21 Precision Math
Expressions can be used at several points in SQL statements, such as in the ORDER BY or HAVING clauses of SELECT statements, in the WHERE clause of a SELECT, DELETE, or UPDATE statement, or in SET statements. Expressions can be written using values from several sources, such as literal values, column values, NULL, variables, built-in functions and operators, loadable functions, and stored functions (a type of stored object).

This chapter describes the built-in functions and operators that are permitted for writing expressions in MySQL. For information about loadable functions and stored functions, see Section 5.6, “MySQL Server Loadable Functions”, and Section 23.2, “Using Stored Routines”. For the rules describing how the server interprets references to different kinds of functions, see Section 9.2.5, “Function Name Parsing and Resolution”.

An expression that contains NULL always produces a NULL value unless otherwise indicated in the documentation for a particular function or operator.
