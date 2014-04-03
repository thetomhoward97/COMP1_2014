#Task 3
##Question 1
The function responsible for getting he users name is the GetPlayerName() function.
##Question 2
I will implement a loop to ensure user is repeatedly asked to enter name
##Question 3
ValidName: Boolean
##Task 3 psuedo code

FUNCTION GetPlayerName
    PlayerName: string
    OUTPUT ''
    OUTPUT 'Please enter name: '
    INPUT PlayerName
    RETURN PlayerName
END FUNCTION

##Improved Psuedo code

FUNCTION GetPlayerName
    PlayerName: String
    ValidName: Boolean
    ValidName <- FALSE
    WHILE ValidName = FALSE DO
       OUTPUT ''
       OUTPUT 'Please enter name: '
       INPUT PlayerName
       IF LENGTH PlayerName > 0 THEN
          ValidName <- TRUE
       END IF
    END WHILE
    RETURN PlayerName
END FUNCTION