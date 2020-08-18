# Division

Scenario: Division by zero
  
  Given Calculator turned ON

  When denominator is zero and

  numerator is integer
  
  Then Display Can't divide by Zero

Scenario :Divide zero by any number
  
  Given Calculator turned ON
  
  When we input numerator zero

  and denominator is integer
  
  Then Display result zero
  
 Scenario: Division of '+' and '-' numbers
  
  Given Calculator turned ON
  
  When we input '+' number numerator

  and '-' number denominator
  
  Then display negative division result

Scenario: division with both operands zero
  
  Given Calculator turned ON
  
  When  We input numerator and denominator zero
  
  Then display can't divide by 0
  
Scenario: Pressing '/' operator more than once
  
  Given Calculator turned ON

  When we type operand and then

  type '/' more than once

  Then Override the previous operators

  And consider the latest operator

Scenario: Interleaving operators

   Given Calculator turned ON

   When we input more than one operator

   Then override each previous operator

Scenario: 2nd operand not present
  
  Given Calculator turned ON

  When we input integer and '/'

  operator
  
  Then Display Syntax Error

Scenario: Division of fractions
  
  Given Calculator turned ON

  When any/all operands are fractions

  Then convert each fraction in decimal and

  display division result

Scenario: More than one consecutive divisions
  
  Given Calculator turned ON

  When we input more than two operands for division

  Then perform division from left to right
