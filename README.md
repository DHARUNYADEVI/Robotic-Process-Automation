# Robotic-Process-Automation
# RPA-EXPERIMENT-3
## NAME:Dharunyadevi S
## REGISTER NUMBER:212223220018

## AIM:
To create a UiPath workflow using Flow Sequence or Flowchart that demonstrates the use of Repeat, While, and Do While loops for iteration and message display.

## Procedure:
### While Loop:
Variables: whileInput (String), whileCount (Int32), counterWhile = 1
Input Dialog → store in whileInput
Assign whileCount = CInt(whileInput)
Use While with condition: counterWhile <= whileCount
Inside loop:
Message Box → "While Loop: " + counterWhile.ToString
Assign counterWhile = counterWhile + 1

### Do While Loop:
Variables: doWhileInput (String), doWhileCount (Int32), counterDoWhile = 1
Input Dialog → store in doWhileInput
Assign doWhileCount = CInt(doWhileInput)
Use Do While with condition: counterDoWhile <= doWhileCount
Inside loop:
Message Box → "Do While Loop: " + counterDoWhile.ToString
Assign counterDoWhile = counterDoWhile + 1

### Repeat Number of Times:
Variables: repeatInput (String), repeatCount (Int32)
Show Input Dialog → store in repeatInput
Assign repeatCount = CInt(repeatInput)
Use Repeat Number of Times with repeatCount
Inside loop: Message Box → "Repeat Loop: " + CurrentItem.ToString

## OUTPUT

### While loop:
<img width="1273" height="1075" alt="image" src="https://github.com/user-attachments/assets/4b8266bc-c9a7-4411-b888-4e7fbc66ed00" />

### Do While loop:
<img width="1278" height="1077" alt="image" src="https://github.com/user-attachments/assets/10b76c95-d821-41e6-b0d8-d32591819426" />

### Repeat:
<img width="1278" height="1079" alt="image" src="https://github.com/user-attachments/assets/b0d9ff8b-cf21-4112-a1c5-b9df2f365c26" />


## RESULT
Thus, the UiPath workflow using Flow Sequence or Flowchart that demonstrates theuse of Repeat, While, and Do While loops for iteration and message display executed successfully.
