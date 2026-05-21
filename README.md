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

## PROGRAM:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Weekly Timetable</title>

  <style>
    body{
      margin:0;
      padding:20px;
      background:#0b0b0b;
      font-family: Arial, sans-serif;
      color:white;
    }

    h1{
      text-align:center;
      color:#4da3ff;
      margin-bottom:25px;
    }

    table{
      width:100%;
      border-collapse:collapse;
      background:#121212;
      border-radius:12px;
      overflow:hidden;
      box-shadow:0 0 10px rgba(0,0,0,0.5);
    }

    th{
      background:#1e1e1e;
      color:#4da3ff;
      padding:15px;
      font-size:18px;
      border-bottom:2px solid #333;
    }

    td{
      padding:14px;
      text-align:center;
      border-bottom:1px solid #2a2a2a;
      font-size:16px;
    }

    tr:hover{
      background:#1a1a1a;
    }

    .no-class{
      color:#ff6b6b;
      font-weight:bold;
    }

    @media screen and (max-width: 768px){
      table{
        font-size:14px;
      }

      th, td{
        padding:10px;
      }
    }
  </style>
</head>

<body>

  <h1>Weekly Timetable</h1>

  <table>
    <tr>
      <th>Day</th>
      <th>Subject</th>
      <th>Time</th>
      <th>Venue</th>
    </tr>

    <tr>
      <td>Monday</td>
      <td>Python Programming</td>
      <td>08:00 AM - 09:59 AM</td>
      <td>2511</td>
    </tr>

    <tr>
      <td>Tuesday</td>
      <td>Fundamentals of Web Application Development</td>
      <td>10:00 AM - 11:59 AM</td>
      <td>2853</td>
    </tr>

    <tr>
      <td>Tuesday</td>
      <td>Fundamentals of Web Application Development</td>
      <td>01:00 PM - 02:59 PM</td>
      <td>2371</td>
    </tr>

    <tr>
      <td>Wednesday</td>
      <td>Python Programming</td>
      <td>08:00 AM - 09:59 AM</td>
      <td>2411</td>
    </tr>

    <tr>
      <td>Wednesday</td>
      <td>Fundamentals of Web Application Development</td>
      <td>10:00 AM - 11:59 AM</td>
      <td>2851</td>
    </tr>

    <tr>
      <td>Wednesday</td>
      <td>Mentor Meet</td>
      <td>01:00 PM - 02:59 PM</td>
      <td>6683</td>
    </tr>

    <tr>
      <td>Thursday</td>
      <td>Python Programming</td>
      <td>10:00 AM - 11:59 AM</td>
      <td>2511</td>
    </tr>

    <tr>
      <td>Thursday</td>
      <td>Python Programming</td>
      <td>01:00 PM - 02:59 PM</td>
      <td>2512</td>
    </tr>

    <tr>
      <td>Friday</td>
      <td>Fundamentals of Web Application Development</td>
      <td>10:00 AM - 11:59 AM</td>
      <td>6872</td>
    </tr>

    <tr>
      <td>Saturday</td>
      <td class="no-class">No Class</td>
      <td>—</td>
      <td>—</td>
    </tr>

    <tr>
      <td>Sunday</td>
      <td class="no-class">No Class</td>
      <td>—</td>
      <td>—</td>
    </tr>

  </table>

</body>
</html>
~~~

## OUTPUT:


<img width="917" height="557" alt="Screenshot 2026-05-21 113255" src="https://github.com/user-attachments/assets/bb7f9474-22ad-4b01-a076-d2ad98f81a15" />




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
