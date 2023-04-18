# Calculator_language

VAMSI KRISHNA UNNAM  vunnam1@stevens.edu

https://github.com/Vk4140/Calculator_language


I have worked around 55-60 hours on this project from the last week.

I have tested the code with the samples provided from canvas and dynamic sample expressions on own by providing them as an variable or giving as an user input through the terminal, run few samples and tested using the vscode and pycharm IDE and then uploaded into autograder, resolved issues in which the test cases were failed.

# bugs and issues

The bugs and issues of the project that I have faced are related to the tokenization part and the lexing part, and while adding the extensions for multi-line commenting and regular built in function the code is working and giving the output properly but in the whole made wit functions and implementing it throwing out errors.

# resolved issue

The lexer function contains the token of numerals instead of the variables, that has been resolved. Need to get the edge cases of the sqrt function and log function, for multi-line commenting the test cases have been taken care.







The 4 extensions that I have implemeented are:

1 - Op-equals
2 - Relational operatons
3 - Boolean Operations
4 - Multi-line commenting
and few regular built-in functions like minimum, maximum, ceil, sqrt, etc





It can handle arithmetic operations, comparison operators, and logical operators. You can also evaluate expressions involving variables. This code consists of three main parts:
A lexer, an infix to postfix converter, and a postfix evaluator.

The lexer function tokenizes the input expression and returns a list of tokens. It handles numbers, variables, parentheses, arithmetic operators, comparison operators, and logical operators. Each token is represented by an object of the Token class with two attributes:
type and value.

The infix_to_postfix function converts an infix expression to a postfix expression using the marshalling yard algorithm. Takes a list of tokens as input and returns a list of postfix tokens. Use a precedence dictionary to determine operator precedence.

A postfix evaluation function evaluates a postfix expression and returns the result. Takes a list of postfix tokens as input and returns the result of an expression. Use the stack to keep track of intermediate results and operands.  



