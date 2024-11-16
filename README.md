# Ex03 Time Table
## Date:16/11/24
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
    <title>SLOT TIMETABLE</title>
    <center>
    <img src="logo.png" height="100" width="540">
</center>
    
    <table border="5" cellpadding="15" bgcolor="SKY BLUE" align="center">
        <caption align="center">VIGNESH(24900753)</caption>
        <hr>
        <font color="white">
        <th bgcolor="YELLOW">Time\Day</th><th bgcolor="yellow">Monday</th> <th bgcolor="yellow">Tuesday</th> <th bgcolor="yellow">Wednesday</th> <th bgcolor="yellow">Thursday</th> <th bgcolor="yellow">Friday</th> <th bgcolor="yellow">Saturday</th>
        <tr >
            <td bgcolor="green">8.00-10.00</td>
            <td>-</td>
            <td>-</td>
            <TD>-</TD>
            <td>Pysics</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr><td bgcolor="green">10.00-12.00</td><td>chemistry</td><td>Digital Electronics</td><td>C Programming</td><td>Physics</td><td>chemistry</td><td>FWAD</td>
        </tr>
        <tr>
            <td bgcolor="green">1.00-3.00</td><td>BEEE</td><td>FWAD</td><td>MENTOR</td><td>FWAD</td><td>Physics</td><td>C Programming</td>
               </tr>
               <tr>
                <td bgcolor="green">3.00-5.00</td><td>-</td><td>-</td><td>BEEE</td><td>-</td><td>-</td><td>-</td>
               </tr>
    </font>


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
<td align="center">19A1414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19A1304</td>
<td>FUNDAMENTALS OF C PROGRAMMING (C PROGRAM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CY205</td>
<td>principal of chemistry in Engineering</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EE305</td>
<td>Basic Electrical,Electronics and Measurement Engineering</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EE404</td>
<td>Digital Electronics</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">ECA-M--SCOFT</td>
<td>Mentor Meet</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">SH3214</td>
<td>Physics for Quantum Coputing</td>
</tr>
</table>
</body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2024-11-16 114523.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
