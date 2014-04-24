#Task 6
##Question 1
We can keep track of the ace in the main section as it is not going to be changed while its running
##Question 2
The function that needs to be changed in order for the options to be displayed in the menu is DisplayMenu() function
##Question 3
The function needed to be changed to ensure the comparisons work is GetRank()
##Pseudo Code


FUNCTION DisplayOptions
   OUTPUT OPTION MENU
   OUTPUT
   OUTPUT 1. Set Ace to be HIGH or LOW
   OUTPUT
END FUNCTION

FUNCTION GetOptionChoice
   OptionChoice: string
   OUTPUT Select an option from the menu (or enter q to quit)
   INPUT OptionChoice
RETURN OptionChoice
END FUNCTION

FUNCTION SetOptions(OptionChoice: string)
   IF OptionChoice = 1 THEN
      CALL SetAceHighOrLow
   IF OptionChoice = q THEN
      
FUNCTION SetAceHighOrLow
   AceHigh: Boolean
   AceHighOrLow: string
   OUTPUT  Do you want Ace to be high or low? (h/l)
   INPUT AceHighOrLow
   IF AceHighOrLow = h THEN
      AceHigh <- TRUE
RETURN AceHigh
END FUNCTION
   
   
