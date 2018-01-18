# notes

# Flowchart Notes 
- circles are used to connect logic 
- Use ms word

# Chapter 1 - 


# Chapter 2 - 


# Chapter 3 -

- 3.1 Expressions - 
- # Expressions - sequence of operators and operands, evaluate down to a single value 
  - operator - syntax token that requires an action to be taken 
  - operand - object on which an operator is performed 
  - ## Binary operator - a + b 
    - a and b are operands, + is an operator 
    - Reduce down to a single value 
  - ## Ternary operator - (a > b) ? printf("Option one"); : printf("Option 2"); 
- # Postfix vs prefix operator 
  - Postfix - operator comes after operand - a++
    - operand must be variable 
    - a = a + 1 = a++
    - x = a++; 
      - Suppose a = 15; x = a++; - 15 is assigned to x, and then a is incremented. printf(x) = 15!!
      - value of expression is a 
      - value of a is incremented by 1 
      - evaluated after the expression it is in 
  - Prefix - operator comes before operand - ++a 
    - x = ++a; 
    - x will be equal to a + 1; 
    - Suppose a = 15; x = ++a; printf("%d", x); - returns 16!!!
  - int i = 0, j = 0; 
  - j = i++ + ++i; 
  - Precedence operators 
    - pre increment - 1
    - post increment - 2
    - arithmetic operator - 3
    - assignment operator - 4
      - ++i, then i++ + ++i - equals to two 
