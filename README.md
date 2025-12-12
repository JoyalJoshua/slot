# Ex02 Time Table
## Date: 12-12-2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Time Table</title>
</head>

<body>
    <center>
        <img src="logo.png" alt="" style="width: 50%; display: block; margin-bottom: 20px;">
    </center>
    <table border="1" style="border-collapse: collapse; width: 100%; font-family: Arial; text-align: center;">
        <tr>
            <th style="background-color: red; color: white; padding: 12px; font-weight: bold;">Day</th>
            <th style="background-color: green; color: white; padding: 12px; font-weight: bold;">8 - 10</th>
            <th style="background-color: #2b8a3e; color: white; padding: 12px; font-weight: bold;">10 - 12</th>
            <th style="background-color: #2b8a3e; color: white; padding: 12px; font-weight: bold;">1 - 3</th>
            <th style="background-color: #2b8a3e; color: white; padding: 12px; font-weight: bold;">3 - 5</th>
        </tr>
        <tr style="background-color: #f9f9f9;">
            <td style="padding: 10px; color: #333;">Monday</td>
            <td style="padding: 10px; color: #333;">Public Speaking</td>
            <td style="padding: 10px; color: #333;">Web Development</td>
            <td style="padding: 10px; color: #333;">Python Programming</td>
            <td style="padding: 10px; color: #333;">N/A</td>
        </tr>
        <tr>
            <td style="padding: 10px; color: #333;">Tuesday</td>
            <td style="padding: 10px; color: #333;">Public Speaking</td>
            <td style="padding: 10px; color: #333;">N/A</td>
            <td style="padding: 10px; color: #333;">Python Programming</td>
            <td style="padding: 10px; color: #333;">N/A</td>
        </tr>
        <tr style="background-color: #f9f9f9;">
            <td style="padding: 10px; color: #333;">Wednesday</td>
            <td style="padding: 10px; color: #333;">Python Programming</td>
            <td style="padding: 10px; color: #333;">Public Speaking</td>
            <td style="padding: 10px; color: #333;">Mentor Meet</td>
            <td style="padding: 10px; color: #333;">Web Development</td>
        </tr>
        <tr>
            <td style="padding: 10px; color: #333;">Thursday</td>
            <td style="padding: 10px; color: #333;">Web Development</td>
            <td style="padding: 10px; color: #333;">Python Programming</td>
            <td style="padding: 10px; color: #333;">N/A</td>
            <td style="padding: 10px; color: #333;">N/A</td>
        </tr>
        <tr style="background-color: #f9f9f9;">
            <td style="padding: 10px; color: #333;">Friday</td>
            <td style="padding: 10px; color: #333;">Public Speaking</td>
            <td style="padding: 10px; color: #333;">N/A</td>
            <td style="padding: 10px; color: #333;">Web Development</td>
            <td style="padding: 10px; color: #333;">Web Development</td>
        </tr>
        <tr>
            <td style="padding: 10px; color: #333;">Saturday</td>
            <td style="padding: 10px; color: #333;">N/A</td>
            <td style="padding: 10px; color: #333;">Python Programming</td>
            <td style="padding: 10px; color: #333;">N/A</td>
            <td style="padding: 10px; color: #333;">N/A</td>
        </tr>
    </table>
</body>
</html>
```


## OUTPUT

![alt text](<Screenshot 2025-12-12 141041.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
