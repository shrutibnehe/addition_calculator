# Addition

Scenario: Addition of two Positive numbers
  
  Given :Calculator turned ON

  When  :We type 2 positive integers
  
  Then  :Display the addition of two integers

Scenario: Addition of positive and negative numbers
  
  Given :Calculator turned ON
  
  When  :Positive number greater than negative number
  
  Then  :Negative number subtracted from positive number
  
 Scenario: Addition of two decimal numbers
  
  Given :Calculator turned ON
  
  When  :We type two decimal numbers
  
  Then  :Display the final decimal result
  
Scenario: Typing operator more than once
  
  Given Calculator turned ON

  When we type operator more than

  Then Overide the previous operators

  And consider the latest operator

Scenario: Invalid input 6+*
  
  Given Calculator turned ON

  When we type operand

  And then operators

  Then 'Display Syntax Error'

Scenario: Identify operation
  
  Given Calculator turned ON

  When we type operand

  ANd then 'plus'

  And then '0'
  
  Then Result would be the Operand

Scenario: Out of Range
  
  Given Calculator turned ON

  When Result goes out of range  

  Then Result would be viewed by using

  side arrows

Scenario: Addition of two negative numbers
  
  Given Calculator turned ON

  When we type first negative operand
  
  'plus' second negative operand  

  Then Addition of two operand with

  negative sign

Scenario: Addition of Integer and Fraction
  
  Given Calculator turned ON

  When we type first Intger operand
  
  'plus' second Fractional operand  

  Then Result would be Fraction with

  negative sign

Scenario: Addition of 3 numbers
  
  Given Calculator turned ON

  When we input 3 Intger operands
  
  Then perform addition of 3 integers
