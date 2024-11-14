# DigitalClock
Digital Date and Time System || Brac University || CSE260 : Digital Logic Design

Team Members:
Farhan Faruk 
H.M. Sarwer Alam 
Shudeb Ghosh Barno 

Project Title: Digital Date and Time System

Introduction:
Our project, the "Digital Date and Time System," is an automated digital clock capable of tracking hours, minutes, seconds, days, months, and years from 2020 to 2029. Using IC-74192 and DCLOCK, the clock displays 14 digits across multiple 7-segment displays and handles cases like leap years, varying month lengths, and allows manual adjustments.

Proposed Model:
The digital clock operates on a 24-hour format (00:00:00 to 23:59:59), and the date updates accordingly. We used 14 seven-segment displays to show time and date, and we added logic for leap years and month variations.

Components Used:
Primary components include 7-segment displays, IC-74192, basic logic gates (AND, OR, NOT), switches, and DCLOCK.

Circuit Design and Function:
For time tracking, counters (IC 74192) are synced with the display to show seconds, minutes, and hours. Logic gates reset the count after every 59 seconds and 23 hours. For date tracking, similar logic handles days, months, and years with additional exceptions for different month lengths and leap years.

Conclusion:
The project demonstrates a functional digital clock and calendar system using basic digital logic, though it has some limitations in accuracy due to frequency imperfections. The project reinforces the practical use of digital logic design principles learned in CSE260.






