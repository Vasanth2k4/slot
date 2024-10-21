# Ex03 Time Table
## Date: 06-10-2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>My Time Table</title>
    </head>
    <body> 
        <center>
            <img src="C:\Users\admin\WEB EXP3\saveetha-logo.png" >  
        </center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>My Time Table - MANI SRI LATHA.M (212223110025)</b></caption>
<tr align="center">
<th bgcolor="indigo">Day/Time</th>
<th bgcolor="indigo">Monday</th>
<th bgcolor="indigo">Tuesday</th>
<th bgcolor="indigo">Wednesday</th>
<th bgcolor="indigo">Thursday</th>
<th bgcolor="indigo">Friday</th>
<th bgcolor="indigo">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="indigo">8-10</th>
<td colspan="0" align="center">Free Slot</td>
<td>Free Slot</td>
<td>HRM</td>
<td>BEE</td>
<td>SNM</td>
<td>FWAD</td>
</tr>
<tr align="center">
<th bgcolor="indigo">10-12</th>
<td>HRM</td>
<td>DE</td>
<td>SNM</td>
<td>FWAD</td>
<td>Intro to ML</td>
<td>CD</td>
</tr>
<tr>
<th bgcolor="indigo">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="indigo">1-3</th>
<td colspan="0" align="center">Free Slot</td>
<td>CD</td>
<td>Mentor meet</td>
<td>DE</td>
<td>BEE</td>
<td>Free Slot</td>
</tr>
<tr align="center">
<th bgcolor="indigo">3-5</th>
<td colspan="0" align="center">FWAD</td>
<td>OS</td>
<td>Free Slot</td>
<td>Introk to ML</td>
<td>Free Slot</td>
<td>OS</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI410</td>
<td>Intorduction to ML</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development(FWAD)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS405</td>
<td>Opearting System(OS)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS409</td>
<td>Compiler Design(CD)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>Statistics and Numerical Methods(SNM)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EE305</td>
<td>Basic Electrical,Electronics and Measurement Engineering(BEEE)</td>
</tr>
<tr>
    <td align="center">7.</td>
<td align="center">19MS156</td>
<td>Human Resource Management and Team Building</td>
</tr>
<tr>
    <td align="center">8.</td>
<td align="center">19EE404</td>
<td>Digital Electronics(DE)</td>
</tr>
</table>
    </body>
</html>
```
## OUTPUT
![Screenshot 2024-10-10 103545](https://github.com/user-attachments/assets/acc7c782-07f5-434c-a76a-24d23a059a97)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
