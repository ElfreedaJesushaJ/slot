# Ex03 Time Table
## Date:12.11.2024

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
        <img src="logo.png" width="700" height="200">
        <table border="1" cellspacing="15" cellpadding="2">
            <caption>My Schedule-Elfreeda Jesusha-24900146</caption>
            <tr bgcolor="cyan">
                <th>DAY/TIME</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <td>8-10</td>
                <td>Free hour</td>
                <td>CDS</td>
                <td>CMA</td>
                <td>Free hour</td>
                <td>FWAD</td>
                <td>DE</td>
            </tr>
            <tr>
                <td>10-12</td>
                <td>FOCP</td>
                <td>EDM</td>
                <td>DE</td>
                <td>CMA</td>
                <td>FOCP</td>
                <td>Free hour</td>
            </tr>
            <tr>
                <td>12-1</td>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr>
                <td>1-3</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>Mentor meet</td>
                <td>PQC</td>
                <td>EDM</td>
                <td>PQC</td>
            </tr>
        </table>
        <table>
            <table border="2">
            <tr>
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19EY708</td>
                <td>Career Development Skills</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19AI302</td>
                <td>Engineering Design and Modeling</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>SH3214</td>
                <td>Physics for Quantum Computing</td>
            </tr>
        </table>
    </body>
</html>      
            

```

## OUTPUT
![alt text](<Screenshot 2024-11-12 170845.png>)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
