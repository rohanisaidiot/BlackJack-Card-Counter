# BlackJack-Card-Counter
Fuck BlackJack 

Python based program that calculates the true count of a blackjack game using Wong Halves, Omega II, or Lo-Hi systems. Using user inputted card values and the number of decks remaining in the shoe, the program gives a number that represents the statistical advantage to the player or the dealer. It also plots the trend of true counts and the probability of receiving any card value left in the shoe.

Motivation
Card counting is often portrayed in popular media as something only achievable by individuals with exceptional mathematical intelligence. I wanted to create a program that shows that card counting is more approachable than many assume it to be. Though it definitely helps, you don't have to be Rain Man!

Built With
Python 3.7.3
PyQt5
Qt Designer
Installation
Simply download and run the executable "Blackjack Card Counter.exe"

Usage
Sample GUI

To change the card counting system used to calculate the true count, click the drop down menu and select the one you wish to use. To change the number of decks in play, either type in an integer into the box or click the up/down buttons. Both of these changes will reset all user inputted card values and true counts.

To count cards, begin typing values of all dealt cards (beginning after a shuffle) in the top left text box. You can format the card values in one of two ways:

Single card value
Multiple card values separated by a whitespace and/or commas
To input the typed card values into the calculation of the true count and remaining card probabilities, press the Enter/Return key. All invalid inputs will be ignored and not factored into calculations.

The line graph on the right displays the current and all past true counts, while the bar graph on the bottom displays the probability of receiving each card value based on the remaining cards left in the shoe.

Once the deck is shuffled, press the "Shuffled" button to reset all user inputted card values and true counts. The selected card counting system and number of decks will not change.

Version History
0.1
Initial release
1.0
Standalone executable release
Known Issues
On MacOS systems, the "Shuffled" button successfully completes the "Reset" function but does not update the GUI until focus shifts away from the program window.
