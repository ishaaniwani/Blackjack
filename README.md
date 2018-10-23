# Blackjack
This is a java program that lets the user play games of blackjack with a computer.

There are a couple of classes in this project. I will go more in depth on what each class is on

Deck - A class that creates a deck of 52 for the user and computer to use. It includes a method called shuffle that shuffles the cards. I will use selection sort to shuffle the cards, as it is the most popular sorting method for cards. 

BlackjackHand - This class contains a bunch of methods and a subroutine of the game Blackjack. This class accesses a deck object to perform its operations. The first method is called play. It emulates one game of blackjack and returns a boolean value. If the user wins, then it returns true and if the computer wins, false is returned.

Main - This class is kind of self explanatory. This contains the main method where the actual game is played. The main method takes methods from Deck and BlackjackHand to run the actual game. The game is under a while loop so that the game is continually played until either the user runs out of Money or they choose not to play anymore.
