# Ex02 Time Table
## Date:21/05/2026

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
        <title>slot Timetable</title>
    </head>
    <body>
        <center>
        <img src="OIP.webp" height="200" width="800">
        </center>
        <br>
        <table align="center" width="800" cellspacing="2" cellpadding="4" border="6" bgcolor="green">
            <caption><b>SLOT TIME TABLE - MUHILAN A(25015918)</b></caption>
            <tr align="center">
                <th bgcolor="yellow">Day/Time</th>
                <th bgcolor="yellow">Monday</th>
                <th bgcolor="yellow">Tuesday</th>
                <th bgcolor="yellow">Wednesday</th>
                <th bgcolor="yellow">Thursday</th>
                <th bgcolor="yellow">Friday</th>
                <th bgcolor="yellow">Saturday</th>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">8-10</td>
                <td>Free slot</td>
                <td>cp</td>
                <td>Free slot</td>
                <td>Free slot</td>
                <td>web</td>
                <td>ps</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">10-12</td>
                <td>cp</td>
                <td>Free slot</td>
                <td>ps</td>
                <td>Free slot</td>
                <td>web</td>
                <td>web</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">12-1</td>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">1-3</td>
                <td>web</td>
                <td>web</td>
                <td>MM</td>
                <td>ps</td>
                <td>Free slot</td>
                <td>ps</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">3-5</td>
                <td>Free slot</td>
                <td>cp</td>
                <td>cp</td>
                <td>cp</td>
                <td>Free slot</td>
                <td>Free slot</td>
            </tr>
            </table>
            <br>
            <table align="center" cellspacing="2" cellpadding="4" border="6">
            <tr align="center">
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td align="center">Fundamentals of web application development(web)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AI304</td>
                <td align="center">Fundamentals of c programming (cp)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19AI414</td>
                <td align="center">public speaking (ps)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">ECA-M</td>
                <td align="center">Mentor Meet(MM)</td>
            </tr>
            </table>
        </body>
    </html>
```



## OUTPUT
<img width="1500" height="898" alt="image" src="https://github.com/user-attachments/assets/72855429-745d-4192-890f-8445f6e9a3ae" />



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
