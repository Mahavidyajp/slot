# Ex03 Time Table
## Date: 08.11.2023

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
<title>Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" border="2" bgcolor="skyblue" cellspacing="2" cellpadding="10">
<caption><b>SLOT TIME TABLE - MAHA VIDYA (23013441)</b></caption>
<tr align="center">
<th bgcolor="lavender">Day/Time</th>
<th bgcolor="lavender">Monday</th>
<th bgcolor="lavender">Tuesday</th>
<th bgcolor="lavender">Wednesday</th>
<th bgcolor="lavender">Thursday</th>
<th bgcolor="lavender">Friday</th>
</tr>
<tr align="center">
<th bgcolor="lavender">8-10</th>
<td>FREE SLOT</td>
<td>CHE</td>
<td>PY</td>
<td>FWAD</td>
<td>DE</td>
</tr>
<tr align="center">
<th bgcolor="lavender">10-12</th>
<td>CHE</td>
<td>MAT</td>
<td>CA</td>
<td>FWAD</td>
<td>CA</td>
</tr>
<tr align="center">
<th bgcolor="lavender">12-1</th>
<td colspan="5">LUNCH</td>
<tr align="center">
<th bgcolor="lavender">1-3</th>
<td>FREE SLOT</td>
<td>CHE</td>
<td>DE</td>
<td>FREE SLOT</td>
<td>FWAD</td>
</tr>
<tr align="center">
<th bgcolor="lavender">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>PY</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
</table>
<br>
<br>

<table align="center" border="2" bgcolor="skyblue" cellspacing="2" cellpadding="10">
<tr align="center">
<th bgcolor="lavender">S.no</th>
<th bgcolor="lavender">Subject Code</th>
<th bgcolor="lavender">Subject Name</th>
</tr>
<tr align="center">
<th bgcolor="lavender">1.</th>
<td>19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr align="center">
<th bgcolor="lavender">2.</th>
<td>19MA210</td>
<td>Calculus & Matrix (MAT)</td>
</tr>
<tr align="center">
<th bgcolor="lavender">3.</th>
<td>19EE404</td>
<td>Digital Electronics (DE)</td>
</tr>
<tr align="center">
<th bgcolor="lavender">4.</th>
<td>19CY205</td>
<td>Principles of Chemistry in Engineering (CHE)</td>
</tr>
<tr align="center">
<th bgcolor="lavender">5.</th>
<td>19AI301</td>
<td>Python Programming (PY)</td>
</tr>
<tr align="center">
<th bgcolor="lavender">6.</th>
<td>19CS305</td>
<td>Computer Architecture (CA)</td>
</tr>
</table>
</body>
</html>
```
## OUTPUT
![Alt text](<Screenshot 2023-11-08 181045.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
