## Welcome to The Elevator Interface 

This interface is designed to ease the use of elevator, understand and facilitate the actions.  <br /> 
A best attempt has been made to have this design follow the Elevator standards. 

## Elevator location:
This elevator is from Rawls College of Business Administration, Texas Tech University. 

## Design issues:
* There is only one button for both the elevators. 
* No status of the current location of the elevator from outside.
* Both elevators have a different number of floors buttons. 

## Reasons for bad design:
* Upon pressing the button, one of the elevators opens the door and it’s hard to guess which one would open first when the button is pressed. 
* Both the elevators have only one floor display sign to indicate on one of the corners, which would again be difficult – To verify  
* The current floor number is visible, only when a user stands in close proximity to the elevator on top left and right corner.  
> There are chances when a user goes too close and the elevator door might open suddenly, and the people inside and outside the elevator might collide. 
> User has to look really high to read the floor number 
* Doesn’t support features for people with disabilities 

## Common uses in an elevator:
* Select the elevator touch panel button for the elevator to arrive at the current floor  
* Choose the floor number button to go to the required floor 
* Open and close the elevator door button 

## Rare uses in an elevator:
* Emergency call button  
* Emergency alarm button


## User interaction sequence of actions:
### Case-1:
* User selects the up-arrow option on touch panel from outside the elevator and audio plays command “You’re currently on floor ‘number’ and have selected the option to go to upper floor” 
* For any assistance, select the Disability option 
* The elevator door opens after it arrives at the current floor  
* User enters the lift  
* User has four options: 
* Select destination floor on the touch screen panel  
> Enter destination floor on the touch screen panel 
> Select destination floor on the button panel 
> In case of assistance or emergency, us the assistance option or emergency options on touch screen or button panel 
### Case-2:
* User selects the down-arrow option on touch panel from outside the elevator and audio plays command “You’re currently on floor ‘number’ and have selected the option to go to lower floor”  
* For any assistance, select the Disability option 
* The elevator door opens after it arrives at the current floor
* User enters the lift 
* User has four options: 
> Select destination floor on the touch screen panel 
> Enter destination floor on the touch screen panel  
> Select destination floor on the button panel 
> In case of assistance or emergency, us the assistance option or emergency options on touch screen or button panel 

## Design decisions:
* Touch panel outside the elevator: 
> Elevator status display screen: to view the status of the elevator 
> Audio output: for ease and extra assistance 
> Up and down arrows: to navigate the elevator 
> Assistance option: for any further assistance 
* Inside the elevator: 
> Two extra Touch panels: 
> > Elevator floor number status display on two front panels of elevator 
> Main Touch panel:  
> > Description of elevator number, capacity(lbs.), no. of people it can accommodate 
> > Date, time and current temperature 
> > Elevator status, floor numbers  
> > Choose destination floor, Enter destination floor 
> > Assistance option
> > Close doors, open doors 
> > Emergency call, Emergency alarm
> Button panel: <br /> 
> > Floor numbers <br /> 
> > Assistance option <br /> 
> > Close doors, open doors <br /> 
> > Emergency call, Emergency alarm
>
        
    
## Suggestions:
* Have separate outside touch panels for each elevator  
* View current floor number for the respective elevator on the touch panel along with other options  
* Have an audio output 
* Provide support for people with disabilities 
* Provide support for people with claustrophobia


## Contact
Copyright ©️ Hriddhi.Kulkarni@ttu.edu

MS in CS, Texas Tech University

