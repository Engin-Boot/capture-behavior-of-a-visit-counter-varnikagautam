# Visit-counter for a Facilities Manager

## Scenario: Report visitor trends during a week of operation

  Given : Day wise footfall count is reported.
  
  When : A Person enters, the sensors increments its data
  and compile it to weekly reports.
  
  Then : The report of the week shows day wise visitor trends.
  
## Scenario: Alert when seating capacity is full

  Given : No of seats available and the no of visitors entered in the hospital
  
  When : The no of visitors is equal the seating capacity
  
  Then : Seating capacity full- Alert sent to Facilities manager
