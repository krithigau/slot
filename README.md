# Ex03 Time Table
## Date:8.3.2024

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
        <title>My Time Tables</title>
    </head>
    <body bgcolor="yellow">
        <img src="logo.png" width="500" height="150"> 
        <br>
        <br>
        <br>
        <table border="2" cellspacing="5" cellpadding="5" width="25" height="25">
            <caption><B>SLOT TIME TABLE-KRITHIGA U (23006499)</B></caption>
                <tr>
                    <th bgcolor="orange">Day/Time</th>
                    <th bgcolor="orange">Monday</th>
                    <th bgcolor="orange">Tuesday</th>
                    <th bgcolor="orange">Wednesday</th>
                    <th bgcolor="orange">Thursday</th>
                    <th bgcolor="orange">Friday</th>
                    <th bgcolor="orange">Saturday</th>
                </tr>
                <tr>
                    <td bgcolor="orange">8-10</td>
                    <td bgcolor="pink">FREE SLOT</td>
                    <td bgcolor="pink">Trans</td>
                    <td bgcolor="pink">Chem</td> 
                    <td bgcolor="pink">FREE SLOT</td> 
                    <td bgcolor="pink">FWAD</td>
                    <td bgcolor="pink">CS</td> 
                </tr>
                <tr>
                    <td bgcolor="orange">10-12</td>
                    <td bgcolor="pink">FREE SLOT</td>
                    <td bgcolor="pink">FREE SLOT</td>
                    <td bgcolor="pink">Prob</td> 
                    <td bgcolor="pink">Trans</td> 
                    <td bgcolor="pink">EMPD</td>
                    <td bgcolor="pink">Chem</td>
                </tr>
                <tr>
                    <td bgcolor="orange">12-1</td>
                    <td bgcolor="pink" colspan="6">LUNCH</th>
                </tr>
                <tr>
                    <td bgcolor="orange">1-3</td>
                    <td bgcolor="pink">FREE SLOT</td>
                    <td bgcolor="pink">FWAD</td>
                    <td bgcolor="pink">EMPD</td> 
                    <td bgcolor="pink">FWAD</td> 
                    <td bgcolor="pink">CN</td>
                    <td bgcolor="pink">Prob</td>
                </tr>
                <tr>
                    <td bgcolor="orange">3-5</td>
                    <td bgcolor="pink">FREE SLOT</td>
                    <td bgcolor="pink">FREE SLOT</td>
                    <td bgcolor="pink">CN</td> 
                    <td bgcolor="pink">FREE SLOT</td> 
                    <td bgcolor="pink">FREE SLOT</td>
                    <td bgcolor="pink">FREE SLOT</td>
                </tr>
        
        </table>
        <br>
        <br>
        <table border="2" cellspacing="5" cellpadding="5" width="500" height="50">
                    <tr>
                        <th>S.No</th>
                        <th>Subject Code</th>
                        <th>Subject Name</th>
                    </tr>
                    <tr>
                        <td>1.</td>
                        <td>19MA219</td>
                        <td>Transforms and its applications(Trans)</td>
                    </tr>
                    <tr>
                        <td>2.</td>
                        <td>19AI414</td>
                        <td>Fundamentals of Web Application Development (FWAD)</td> 
                    </tr>
                    <tr>
                        <td>3.</td>
                        <td>19CY205</td>
                        <td>Principles of Chemistry in Engineering(Chem)</td>
                    </tr>
                    <tr>
                        <td>4.</td>
                        <td>19MA222</td>
                        <td>Probability and Queueing Models(Prob)</td>
                    </tr>
                    <tr>
                        <td>5.</td>
                        <td>19AI303</td>
                        <td>Engineering Mechanics and Product Development (EMPD)</td>
                    </tr>
                    <tr>
                        <td>6.</td>
                        <td>19CS406</td>
                        <td>Computer Networks (CN)</td>
                    </tr>
                    <tr>
                        <td>7.</td>
                        <td>19EY702</td>
                        <td>Creative Skills for Communication (CS)</td>
                    </tr>
    </table>
    </body>
</html>

```
## OUTPUT

![alt text](<Screenshot (62).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
