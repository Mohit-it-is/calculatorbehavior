# Addition

Scenario: Add two number
  
  Given I have a working calculator

  When I enter "number1" 
  And press "+" button 
  And I enter "number2" 
  And press "=" button
  
  Then I see the "added sum" as the result
  


