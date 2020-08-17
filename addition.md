# Addition

Scenario: Add two number
  
  Given I have a working calculator turned on

  When I enter "number1"
  And press "+" button
  And I enter "number2"
  And press "=" button
  
  Then I see the "added sum" as the result
  
Scenario: Add two large number

  Given I have a working calculator turned on
  
  When I enter "number1"
  And press "+" button
  And I enter "number2"
  And press "=" button
  
  Then I see the result in exponential
  or display "result can not be displayed"
