# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given: The system is up and running, visitor data is available .
  
  When: Facilities manager asks for a report .
  
  Then: System displays weekly trends for the visitors .
  
Scenario: Alert when seating capacity is full

  Given: The system is up and running, the visitor data
         and number of seats available .
  
  When: Patient visits the hospital
        and visitor count exceeds the seating capacity .
  
  Then: System sends Seating capacity full alert to the facilities manager.
