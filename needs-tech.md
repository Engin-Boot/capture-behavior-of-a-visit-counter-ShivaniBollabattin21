# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given: The system is up and running.
  
  When: The server that runs visit-counter restarts.
  
  Then: System sends server restart and data recovery
        alert to technical manager .

Scenario: Reconcile counts if the sensor is offline for a while

  Given: The system(or sensor) is up and running.
  
  When: The sensor is offline.
  
  Then: Then sensor stores the count data in its local
        memory and pushes on to the server when it is
        online .  
