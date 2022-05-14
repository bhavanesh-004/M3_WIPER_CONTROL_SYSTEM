
## M3_WIPER_CONTROL_SYSTEM

* User button is hold for two seconds,the red LED is on
* Wiper Speed is LOW
* Wiper Speed is MEDIUM
* Wiper Speed is HIGH
* User button is pressed and hold for 2 seconds, the red LED is off
# TEST CASES and Corresponding Output:


##  HIGH LEVEL TEST PLAN
| Test ID | Description                                              | Exp I/P | Exp O/P | Actual Output |Type Of Test  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  H_01       | At the Time of engine ON  |  ONCE a button is pressed | ON Engine |ON Engine|Requirement based |
|  H_02       |At the time of engine OFF|  TWICE a button are pressed | OFF Engine |OFF Engine|Requirement based |
|  H_03       |At the time of Wiper ON|  THRICE a button are pressed | ON Wiper |ON Wiper in Clockwise direction |Requirement based |
|  H_04       |At the time of Wiper OFF|  Four times a button are pressed | OFF Wiper |OFF Wiper in Anticlockwise direction |Requirement based |


##  LOW LEVEL TEST PLAN

| Test ID | Description       | Exp I/P | Exp O/P | Actual Output |Type Of Test  |   
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  L_01       | ON Engine check condition| Pressed Button Once | On All LED|ON All LED as per Encryption|Requirement based |
|  L_02       | OFF Engine check condition | Pressed Button Twice | OFF all LED|OFF all LED as per encryption|Requirement based |
|  L_03       | ON Wiper check condition | Pressed Button three times |ON LED in Clockwise Direction| On LED in clockwise direction as per encrytion |Requirement based    |
|  L_03       | OFF Wiper check condition | Pressed Button Four times |OFF LED in Anticlockwise Direction| OFF LED in Anticlockwise direction as per encrytion |Requirement based    |
