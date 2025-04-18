# Ex03 Time Table
## Date: 18.04.2025

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
### time.html

<html>
    <head>
        <link rel="stylesheet" href="time.css">
        <title>
            My TimeTable
        </title>
    </head>
    <body>
        <center><img src="logo.png" height="160" width="850"></center>
        <table width=800 border="10" align="center" cellspacing="1" cellpadding="5" style="border-style:ridge; font-size: 20;border-color: white;" >
            <caption><h3>Time Table - Dhanvant (24005057)</h3></caption>
            <tr>
                <th id="size">D/P</th>
                <th>Period 1</th>
                <th>Period 2</th>
                <th rowspan="7" valign="middle" style="writing-mode:sideways-lr;letter-spacing: 10px;">Lunch</th>
                <th>Period 3</th>
            </tr>
            <tr>
                <th>Monday</th>
                <td>Fundamentals of Web Development</td>
                <td>Free</td>
                <td>Fundamentals of AI</td>
            </tr>
            <tr>
                <th>Tuesday</th>
                <td>Free</td>
                <td>Fundamentals of Web Development</td>
                <td>Fundamentals of C programming</td>
            </tr>
            <tr>
                <th>Wednesday</th>
                <td>Python Programming</td>
                <td>Free</td>
                <td>Mentor Meet</td>
            </tr>
            <tr>
                <th>Thursday</th>
                <td>Fundamentals of AI</td>
                <td>Fundamentals of C programming</td>
                <td>Free</td>
            </tr>
            <tr>
                <th>Friday</th>
                <td>Free</td>
                <td>Operating System</td>
                <td>Python Programming</td>
            </tr>
            <tr>
                <th>Saturday</th>
                <td>Operating System</td>
                <td>Yoga and Meditation</td>
                <td>Free</td>
            </tr>
        </table>
        <br>
        <table width=700 border="10" align="center" cellspacing="1" cellpadding="5" style="border-style:ridge; font-size: 20;border-color: white;">
            <tr>
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <th>1.</th>
                <td>19AI414</td>
                <td>Fundamentals of Web Development</td>
            </tr>
            <tr>
                <th>2.</th>
                <td>19AI405</td>
                <td>Fundamentals of AI</td>
            </tr>
            <tr>
                <th>3.</th>
                <td>19AI304</td>
                <td>Fundamentals of C programming</td>
            </tr>
            <tr>
                <th>4.</th>
                <td>19AI301</td>
                <td>Python Programming</td>
            </tr>
            <tr>
                <th>5.</th>
                <td>19CS405</td>
                <td>Operating System</td>
            </tr>
            <tr>
                <th>6.</th>
                <td>SH5616</td>
                <td>Yoga and Meditaion</td>
            </tr>
        </table>
        <br>
        <br>
    </body>
</html>

### time.css

th{
    transition-duration: 0.5s;
    text-align: center;
    font-size: 20;
    background-color: rgb(34, 100, 39);
    color: rgb(255, 255, 255);
}
th:hover{
    background-color: rgb(118, 192, 124);
    color: rgb(0, 0, 0);
}
td{
    transition-duration: 0.5s;
    text-align: center;
    font-size: 20;
    border: 23;
    background-color: rgb(118, 192, 124);
}
td:hover{
    background-color: rgb(34, 100, 39);
    -webkit-text-fill-color: rgb(255, 255, 255);
}
body{
    text-align: center;
    background-color:rgb(52, 133, 105);
    transition-duration:1s;
    
}
#size{
    font-size: 17;
}
caption{
    font-size: 25;
}

```

## OUTPUT

![alt text](<Screenshot (149).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
