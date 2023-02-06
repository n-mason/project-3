# UOCIS322 - Project 3 #

## Name: Nathaniel Mason

## Contact Info: nmason@uoregon.edu

## Brief Project Description:
The goal of this project is to change the flask_vocab anagram game so that the original form interaction is replaced with AJAX interaction instead. The page will check each key that is pressed and send the appropriate response based on the following conditions:
* If the letter(s)/word entered are not in the vocabulary, a message will be displayed at the bottom of the page
* If the word cannot be made from the letters in the anagram, a different message will be displayed at the bottom of the page
* If the word entered is a match, then it will be listed under "You found" (the words found are listed above the other messages mentioned previously)
* After a match is found and the word is added under "You found", the input box will be cleared so that it's ready for the next letter(s)/word from the user

Once three word matches are found, the goal of the game is complete so the user will be redirected to a success page. This success page lets the user know they won the game and has an option to play the game again.