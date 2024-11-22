# Ex03 Time Table
## Date:21.11.24

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
    <body>
        <img src="logo.png" width="500" height="100">
<table border="2" cellspacing="15" cellpadding="5">
    <caption>Timetable  MANIYARASAN(24900020)</caption>
    <tr bgcolor="cyan">
        <th>DAY</th>
        <th>8-10</th>
        <th>10-12</th>
        <th>1-3</th>
    </tr>
    <tr>
        <td bgcolor="cyan">MONDAY</td>
        <td bgcolor="pink">FREE</td>
        <td bgcolor="pink">PHYSICS</td>
        <td bgcolor="pink">CAREER</td>


    </tr>
    <tr>
        <td bgcolor="cyan">TUESDAY</td>
        <td bgcolor="pink">WEB</td>
        <td bgcolor="pink">FREE</td>
        <td bgcolor="pink">ENGLISH</td>
        
    </tr>
    <tr>
        <td bgcolor="cyan">WEDNESDAY</td>
        <td bgcolor="pink">FREE</td>
        <td bgcolor="pink">C</td>
        <td bgcolor="pink">MENTOR</td>
    </tr>
    <tr>
        <td bgcolor="cyan">THURSDAY</td>
        <td bgcolor="pink">EDM</td>
        <td bgcolor="pink">ENGLISH</td>
        <td bgcolor="pink">PHYSICS</td>
    </tr>
    <tr>
        <td bgcolor="cyan">FRIDAY</td>
        <td bgcolor="pink">MATHS</td>
        <td bgcolor="pink">C</td>
        <td bgcolor="pink">WEB</td>
        
    </tr>
    <tr>
        <td bgcolor="cyan">SATURDAY</td>
        <td bgcolor="pink">EDM</td>
        <td bgcolor="pink">MATHS</td>
        <td bgcolor="pink">WEB</td>
    </tr>
</table>

<table border="2">
	<tr>
	    <th>S.NO</th>
	    <th>COURSE CODE</th>
	    <th>COURSE NAME</th>
	</tr>
	<tr>
	    <td>1</td>
	    <td>19AI414</td>
	    <td>Fundamental Web Application Development</td>
	</tr>
	<tr>
	    <td>2</td>
	    <td>19AI304</td>
	    <td>Fundamentals Of C Programming</td>
	</tr>
	<tr>
	    <td>3</td>
	    <td>19AI302</td>
	    <td>Engineering Design And Modelling</td>
	</tr>
	<tr>
	    <td>4</td>
	    <td>19EN101</td>
	    <td>Communicative English</td>
	</tr>
	<tr>
	    <td>5</td>
	    <td>SH3214</td>
 	    <td>Physics For Quantum Computing</td>
	</tr>
    <tr>
        <td>6</td>
        <td>19MA201</td>
        <td>Calculus and Matrix Algebra</td>
    </tr>
    <tr>
        <td>7</td>
        <td>19EY708</td>
        <td>Career Development Skills</td>
    </tr>
    
</table>
    </body>
</html>
```
## OUTPUT
![alt text](<Screenshot (3).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
