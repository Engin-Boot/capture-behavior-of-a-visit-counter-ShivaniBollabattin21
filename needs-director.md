# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given: The entry card issuer is up and
         running and patients visit the hospital .
  
  When: Director asks for visitor-count report .
  
  Then: Display patient visit count during working days and holidays.

Scenario: Compute parking slots to reserve for visiting specialists

  Given: Reserved parking place has empty slots available.
  
  When: Specialist enters the hospital and has a visitor card.
  
  Then: System allocates a parking slot from reserved place to the specialist.

Scenario: Show patient visits-counts per shifts .

  Given: The system is up and running and it
         stores data of visit count in shifts( 3 categories - M, A, N)
         based on time stamp .
  
  When: Director asks for the count for a particular shift.
  
  Then: System displays the visitor count as per the requested shift.
