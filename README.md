# Ex02 Time Table
## Date:12/02/2026

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
```python
<!DOCTYPE html>
<html>
<head>
    <img src="./logo.png" width="1300" height="200">
    <title>College Timetable</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f6f8;
            text-align: center;
        }

        h1 {
            margin-top: 20px;
        }

        table {
            margin: 20px auto;
            border-collapse: collapse;
            width: 80%;
            background-color: white;
        }

        th, td {
            border: 1px solid #999;
            padding: 10px;
        }

        th {
            background-color: #2c3e50;
            color: white;
        }

        .lunch {
            background-color: #eaeaea;
            font-weight: bold;
        }

        .leave {
            background-color: #f0f0f0;
            font-weight: bold;
        }

        .subject-title {
            margin-top: 30px;
            font-size: 18px;
        }
    </style>
</head>

<body>

<h1>College Timetable-Preetham Kumar(212224040032)</h1>

<table>
    <tr>
        <th>Day/Time</th>
        <th>08.00-10.00</th>
        <th>10.00-12.00</th>
        <th>12.00-01.00</th>
        <th>01.00-03.00</th>
    </tr>

    <tr>
        <td>Monday</td>
        <td>FWAD</td>
        <td>DBMS</td>
        <td rowspan=5 class="lunch">Lunch</td>
        <td>-</td>
    </tr>

    <tr>
        <td>Tuesday</td>
        <td>FWAD</td>
        <td>-</td>
        <td>-</td>
    </tr>

    <tr>
        <td>Wednesday</td>
        <td>-</td>
        <td>FWAD</td>
        <td>Mentor Meet</td>
    </tr>

    <tr>
        <td>Thursday</td>
        <td>-</td>
        <td>-</td>
        <td>FWAD</td>
    </tr>

    <tr>
        <td>Friday</td>
        <td>-</td>
        <td>FWAD</td>
        <td>DBMS</td>
    </tr>

    <tr>
        <td>Saturday</td>
        <td colspan="4" class="leave">Leave</td>
    </tr>
</table>

<div class="subject-title"><b>Subject Details</b></div>

<table>
    <tr>
        <th>S.No</th>
        <th>Code</th>
        <th>Subject</th>
    </tr>

    <tr>
        <td>1</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>

    <tr>
        <td>2</td>
        <td>19CS404</td>
        <td>Database Management Systems (DBMS)</td>
    </tr>
</table>

</body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2026-02-12 142730.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

### Name:Ashok Kumar Preetham Kumar
### Roll No:212224040032