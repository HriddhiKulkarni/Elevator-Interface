## Welcome to The Elevator Interface 
This interface is designed to ease the use of the elevator, understand and facilitate the actions.  <br /> 
The best attempt has been made to have this design follow the Elevator standards. 

## Elevator location:
This elevator is from Rawls College of Business Administration, Texas Tech University. 

## Elevator and its control interface:
Floor B:
![IMG_9658](https://user-images.githubusercontent.com/18117167/64655797-02dc0c80-d3f3-11e9-9ea9-0ca215344613.JPG)

Floor 1 :
![IMG_9650](https://user-images.githubusercontent.com/18117167/64580547-5c3d3080-d34c-11e9-9a28-87f01e350a91.JPG)

![IMG_9649](https://user-images.githubusercontent.com/18117167/64580681-d372c480-d34c-11e9-9718-24d33406fb76.JPG)

Left elevator:
![ezgif com-resize (1)](https://user-images.githubusercontent.com/18117167/64656433-08d2ed00-d3f5-11e9-929c-8b887538ae06.jpg)

Right elevator:
![ezgif com-resize](https://user-images.githubusercontent.com/18117167/64656204-53a03500-d3f4-11e9-82ab-4461340d0802.jpg)

## Control interface in operation:
Left elevator: 

![resize](https://user-images.githubusercontent.com/18117167/64627699-b7573d80-d3b5-11e9-97ef-daa6d726ec29.gif)

![ezgif com-optimize (5)](https://user-images.githubusercontent.com/18117167/64627078-a1954880-d3b4-11e9-9f24-1e3633976e51.gif)

Right elevator:

![ezgif com-optimize (7)](https://user-images.githubusercontent.com/18117167/64656155-20f63c80-d3f4-11e9-9b71-7cfb21616522.gif)

![ezgif com-optimize (6)](https://user-images.githubusercontent.com/18117167/64627222-d99c8b80-d3b4-11e9-809c-19058eba05d2.gif)

Both elevators:
![ezgif com-optimize (3)](https://user-images.githubusercontent.com/18117167/64586401-c4e2d800-d361-11e9-8600-bb3b6997d685.gif)

## Design issues:
* There is only one button for both the elevators. 
* The exact status of the current location of the elevator not evident from outside.
* Both elevators have a different number of floor buttons.  

## Reasons for bad design:
* Upon pressing the button, one of the elevators opens the door and it’s hard to guess which one would open first when the button is pressed. 
* The floor, the elevator is currently on, is not indicated
  * A sign above the elevator displays white color once for one floor up and twice for two floors up 
  * A sign above the elevator displays red color once for one floor down and twice for two floors down 
* Doesn’t support features for people with disabilities 

## Common uses in an elevator:
* Select the button in the elevator control interface to reach the destination floor  
* Choose the floor number or enter the floor number to go to the destination floor 
* Open and close the elevator door button 

## Rare uses in an elevator:
* Emergency call button  
* Emergency alarm button

## Interface review:
### Existing interface review with mistakes:
Though the existing interface provides options like up and down arrow on the outer panel, that doesn't make it easier to use as only one control interface exists for two elevators
The floor numbers are different in both elevators and it is an additional task if a user enters the wrong elevator

### My interface:

## User interaction sequence of actions:
### Existing elevator:
* The user selects the up or down arrow from outside the elevator
* The elevator arrives and the user enters inside
* User closes the door if there is a time lag
* The user selects the destination floor option and selects the door close option on the elevator control interface
* The user reaches the destination floor and steps out after the elevator door opens

### My design:
### Case-1:
* The user selects the up-arrow option on touch panel from outside the elevator and audio plays command “You’re currently on floor ‘number’ and have selected the option to go to upper floor” 
* For any assistance, select the Disability option 
* The elevator door opens after it arrives at the current floor  
* User enters the lift  
* User has four options: 
  * Select destination floor on the touch screen panel  
  * Enter destination floor on the touch screen panel 
  * Select destination floor on the button panel 
  * In case of assistance or emergency, us the assistance option or emergency options on touch screen or button panel 
### Case-2:
* User selects the down-arrow option on touch panel from outside the elevator and audio plays command “You’re currently on floor ‘number’ and have selected the option to go to lower floor”  
* For any assistance, select the Disability option 
* The elevator door opens after it arrives at the current floor
* User enters the lift 
* User has four options: 
  * Select destination floor on the touch screen panel 
  * Enter destination floor on the touch screen panel  
  * Select destination floor on the button panel 
  * In case of assistance or emergency, us the assistance option or emergency options on touch screen or button panel 

## How to use the elevator:
### Existing elevator:
* Outside control interface:
  * Has up, down arrows indicating direction to use the elevator in
* Inside control interface:
  * Has floor numbers as A, B, 1, 2, 3 to reach the destionation floor
  * Has emergency call and emergency alarm buttons
  * Has door open and close buttons
### My elevator:
* Outside control interface:
  * Has up or down arrow indicating direction to use the elevator in
  * Has assistance option indicating any required assistance
* Inside control interface:
  * Touch panel:
    * Select or enter floor number to reach the destionation floor
    * Select assistance, emergency call, emergency alarm, door open, door close options
  * Button panel: 
    * Select floor number to reach the destionation floor
    * Select assistance, emergency call, emergency alarm, door open, door close options

## Elevator providing feedback to user:
### Existing elevator:
* Door opens upon pressing up or down arrows 
* Door plays a 2-3 second audio after it opens or closes
* Panel above elevator displays white color for up arrow and red color for down arrow along with audio
### My elevator:
* Touch panel:
  * 
  * Select or enter floor number 
  * Select 
* Button panel: 
  * Select floor number
  * Select 

## Suggestions:
* Have separate outside touch panels for each elevator  
* View current floor number for the respective elevator on the touch panel along with other options  
* Have an audio output 
* Provide support for people with disabilities 
* Provide support for people with claustrophobia by having a picture or design of numbers, alphabets on one wall of the elevator

## Design decisions:
* Touch panel outside the elevator: 
  * Elevator status display screen: to view the status of the elevator 
  * Audio output: for ease and extra assistance 
  * Up and down arrows: to navigate the elevator 
  * Assistance option: for any further assistance 
* Inside the elevator: 
  * Two extra Touch panels: 
    * Elevator floor number status display on two front panels of elevator 
  * Main Touch panel:  
    * Description of elevator number, capacity(lbs.), no. of people it can accommodate 
    * Date, time and current temperature 
    * Elevator status, floor numbers  
    * Choose destination floor, Enter destination floor 
    * Assistance option
    * Close doors, open doors 
    * Emergency call, Emergency alarm
  * Button panel: 
    * Floor numbers 
    * Assistance option
    * Close doors, open doors  
    * Emergency call, Emergency alarm

## Contact
Copyright ©️ Hriddhi.Kulkarni@ttu.edu <br /> 
MS in CS, Texas Tech University

