## Welcome to The Elevator Interface 

This interface is designed to ease the use of elevator, understand and facilitate the actions.  <br /> 
A best attempt has been made to have this design follow the Elevator standards. 


## Design issues:
•	There is only one button for both the elevators.<br /> 
•	No status of the current location of the elevator from outside.<br /> 
•	Both elevators have a different number of floors buttons. <br /> 

## Reasons for bad design:
•	Upon pressing the button, one of the elevators opens the door and it’s hard to guess which one would open first when the button is pressed<br /> 
•	Both the elevators have only one floor display sign to indicate on one of the corners, which would again be difficult – To verify<br /> 
•	The current floor number is visible, only when a user stands in close proximity to the elevator on top left and right corner. <br /> 
    o	There are chances when a user goes too close and the elevator door might open suddenly, and the people inside and outside the elevator might collide.<br /> 
    o	User has to look really high to read the floor number<br /> 
•	Doesn’t support features for people with disabilities <br /> 

## Common uses in an elevator:
•	Select the elevator touch panel button for the elevator to arrive at the current floor
•	Choose the floor number button to go to the required floor 
•	Open and close the elevator door button

## Rare uses in an elevator:
•	Emergency call button

•	Emergency alarm button


## User interaction sequence of actions:
# Case-1:
•	User selects the up-arrow option on touch panel from outside the elevator and audio plays command “You’re currently on floor ‘number’ and have selected the option to go to upper floor”
•	For any assistance, select the Disability option.
•	The elevator door opens after it arrives at the current floor
•	User enters the lift
•	User has four options:
    o	Select destination floor on the touch screen panel
    o	Enter destination floor on the touch screen panel
    o	Select destination floor on the button panel
    o	In case of assistance or emergency, us the assistance option or emergency options on touch screen or button panel 

# Case-2:
•	User selects the down-arrow option on touch panel from outside the elevator and audio plays command “You’re currently on floor ‘number’ and have selected the option to go to lower floor”
•	For any assistance, select the Disability option.
•	The elevator door opens after it arrives at the current floor
•	User enters the lift
•	User has four options:
    o	Select destination floor on the touch screen panel
    o	Enter destination floor on the touch screen panel
    o	Select destination floor on the button panel
    o	In case of assistance or emergency, us the assistance option or emergency options on touch screen or button panel 

## Design decisions:
•	Touch panel outside the elevator:
    o	Elevator status display screen: to view the status of the elevator
    o	Audio output: for ease and extra assistance
    o	Up and down arrows: to navigate the elevator
    o	Assistance option: for any further assistance

•	Inside the elevator:
    o	Two extra Touch panels:
        	Elevator floor number status display on two front panels of elevator
    o	Main Touch panel:
        	Description of elevator number, capacity(lbs.), no. of people it can accommodate
        	Date, time and current temperature
        	Elevator status, floor numbers
        	Choose destination floor, Enter destination floor
        	Assistance option
        	Close doors, open doors
        	Emergency call, Emergency alarm
    o	Button panel:
        	Floor numbers
        	Assistance option
        	Close doors, open doors
        	Emergency call, Emergency alarm
    o	
    
## Suggestions:
•	Have separate outside touch panels for each elevator
•	View current floor number for the respective elevator on the touch panel along with other options
•	Have an audio output 
•	Provide support for people with disabilities 
•	Provide support for people with claustrophobia



### Contact
Copyright ©️ Hriddhi.Kulkarni@ttu.edu

MS in CS, Texas Tech University
