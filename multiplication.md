# Multiplication

Scenario: Result overflow
  
  Given Calculator turned ON

  And input Two integers for multiplication

  When Result is out of range
  
  Then Scroll result using side arrows

Scenario: Multiplication of '+' with '-' number
  
  Given Calculator turned ON
  
  When we input one positive and one negative

  number for multiplication
  
  Then Display result with negative sign
  
 Scenario: Multiplication with '0'
  
  Given Calculator turned ON
  
  When  We input one of the operand zero
  
  Then display result '0'

Scenario: Multiplication with '1'
  
  Given Calculator turned ON
  
  When  We input one of the operand 'one'
  
  Then display result as operand itself
  
Scenario: Pressing '*' operator more than once
  
  Given Calculator turned ON

  When we type operand and then

  type '*' multiple times

  Then Overide the previous operators

  And consider the latest operator

Scenario: Multiplication of more than 2 numbers
  
  Given Calculator turned ON

  When we input more than 2 integers
  
  Then perform multiplication left to right

Scenario: Decimal value multiplication
  
  Given Calculator turned ON

  When we input decimal numbers

  Then Display decimal multiplication result

Scenario: Rational multiplication
  
  Given Calculator turned ON

  When we input 'numerator','/' and 'denominator'

  as operands
  
  Then convert each operand in decimals and do multiplication

Scenario: Decimal and integer multiplication
  
  Given Calculator turned ON

  When one operand is integer and other decimal

  Then display decimal multiplication result

Scenario: Operand goes out of range
  
  Given Calculator turned ON

  When we input operand and

  and it goes out of range

  Then convert in powers of 10

Scenario: Interleaving operators

   Given Calculator turned ON

   When we input multiple operators

   Then override each previous operator
