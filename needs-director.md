# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given: The entry card issuer is up and
         running and patients visit the hospital .
  
  When: Director asks for visitor-count report .
  
  Then: Display patient visit count during working days and holidays.

Scenario: Compute parking slots to reserve for visiting specialists

  Given: Reserved parking place has empty slots available.
  
  When: Specialist enters the hospital and has a visitor card.
  
  Then: A parking slot from reserved place is allocated to the specialist.
