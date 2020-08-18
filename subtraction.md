# Subtraction

Scenario: Subtraction of two Positive numbers
  
  Given :Calculator turned ON

  When  :We type 2 positive integers
  
  Then  :Display the subtraction of two integers

Scenario: Subtraction of positive and negative numbers
  
  Given :Calculator turned ON
  
  When  :One operand is positive and other negative
  
  Then  :Perform subtraction with sign of result

  of greater number
  
 Scenario: Subtraction of two decimal numbers
  
  Given :Calculator turned ON
  
  When  :We type two decimal numbers
  
  Then  :Display the final decimal result
  
Scenario: Typing operator more than once
  
  Given Calculator turned ON

  When we type operator more than

  Then Override the previous operators

  And consider the latest operator

Scenario: Invalid input 6--*
  
  Given Calculator turned ON

  When we type operand

  And then operators

  Then 'Display Syntax Error'

Scenario: Identify operation
  
  Given Calculator turned ON

  When we type operand

  ANd then 'minus'

  And then '0'
  
  Then Result would be the Operand

Scenario: Subtraction of two negative numbers
  
  Given Calculator turned ON

  When we type first negative operand
  
  'minus' second negative operand

  Then perform subtraction of two operands with

  result sign of greater number

Scenario: Subtraction of Integer and Fraction
  
  Given Calculator turned ON

  When we type first Integer operand
  
  'minus' second Fractional operand  

  Then Result would be Fraction

Scenario: Subtraction of more than two numbers
  
  Given Calculator turned ON

  When we input 3 Integer operands
  
  Then perform subtraction of 3 integers from

  left to right
