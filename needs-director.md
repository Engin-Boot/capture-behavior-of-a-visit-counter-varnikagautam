# Visit-counter for a Director

## Scenario: Show patient visits during working days and holidays

Given : Any person visits the hospital, the sensor for issuing entry card works efficiently

When : A person enters the hospital on working day and holidays

Then : Increment the no of entrries by 1, aggregate the total and display on the
report for that day. Beds, seating arrangement, parking lot provided accordingly

### Scenario: Compute parking slots to reserve for visiting specialists

Given : Specialist vists and is issued an entry card
  
When : 1 hour before the specialist visits the hospital
  
Then : Compute and Reserve a parking slot for the specialist visiting the hospital
