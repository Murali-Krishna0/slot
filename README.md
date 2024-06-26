# Ex03 Time Table
## Date:29.04.24

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
<title>Slot Timetable</title>
</head>
<body>

<br>
<table align="center" width="500" cellspacing="3" cellpadding="2" border="2" bgcolor="yellow">
<caption><b>SLOT TIME TABLE - MURALI KRISHNA S (212223230129)</b></caption>
<tr align="center">
<th bgcolor="cyan">Day/Time</th>
<th bgcolor="cyan">Monday</th>
<th bgcolor="cyan">Tuesday</th>
<th bgcolor="cyan">Wednesday</th>
<th bgcolor="cyan">Thursday</th>
<th bgcolor="cyan">Friday</th>
<th bgcolor="cyan">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="pink">8-10</th>
<td>Fundamentals of Web Application Development</td>
<td>Digital Electronics</td>
<td>German Basic and Advanced</td>
<td>Digital Electronics</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="pink">10-12</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>Probability and Queueing Models</td>
<td>Creative Skills</td>
<td>Python Programming</td>
<td>Operating System</td>
</tr>
<tr>
<th bgcolor="pink">12-1</th>
<td colspan="6" align="center">L U N C H    B R E A K </td>
</tr>
<tr align="center">
<th bgcolor="pink">1-3</th>
<td>German Basic and Advanced</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>Fundamentals of Web Application Development</td>
<td>Fundamentals of Web Application Development</td>
<td>Probability and Queueing Models</td>
</tr>
<tr align="center">
<th bgcolor="pink">3-5</th>
<td>Operating System</td>
<td>German Basic and Advanced</td>
<td>FREE SLOT</td>
<td>Python Programming</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="2" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center"><b><font color = red>19AI414</font></b></td>
<td><b><font color = red>Fundamentals of Web Application Development (FWAD)</font></b></td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI301</td>
<td>Python Programming(Python)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS405</td>
<td>Operating System(OS)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EE404</td>
<td>Digital Electronics(DE)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EN613C</td>
<td>German Basic and Advanced(GBA)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19MA222</td>
<td>Probability and Queueing Models(PQM)</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19EY702</td>
<td>Creative Skills(CS)</td>
</tr>
</table>
</body>
</html>
```
## OUTPUT

![image](https://github.com/Murali-Krishna0/slot/assets/149054535/bb6a1b63-1dbf-4a38-80b7-810274892354)



![image](https://github.com/Murali-Krishna0/slot/assets/149054535/c0201027-3127-43b0-a350-e67f2b534a32)

![image](https://github.com/Murali-Krishna0/slot/assets/149054535/ce1c8584-bdb7-4b0c-8afe-129d10327975)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
