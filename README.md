Date: 19.10.2023

# Ex03 Time Table

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

## CODE

<!DOCTYPE html>
<meta name="viewport">
<img src="download.png" >

<html>
<head>
    <title>Time Table</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="background-color: rgb(173, 230, 221);">
    <p>Slot Time Table - Dhanush S (212221040039) </p>

<table border="1">
    <tr>
        <th style="background-color: violet;">Day/Time</th>
        <th style="background-color: violet;">Monday</th>
        <th style="background-color: violet;">Tuesday</th>
        <th style="background-color: violet;">Wednesday</th>
        <th style="background-color: violet;">Thursday</th>
        <th style="background-color: violet;">Friday</th>
        <th style="background-color: violet;">Saturday</th>
    </tr>
    
    <tr>
        <td style="background-color: yellow;">8-10</td>
        <td style="background-color: rgb(0, 255, 128);"> Free</td>
        <td style="background-color: rgb(0, 255, 128);">Web</td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
        <td style="background-color: rgb(0, 255, 128);" >Toc</td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
    </tr>
    <tr>
        <td style="background-color: yellow;">10-12</td>
        <td style="background-color: rgb(0, 255, 128);">Mern</td>
       <td style="background-color: rgb(0, 255, 128);">Free</td>
       <td style="background-color: rgb(0, 255, 128);">Mern</td>
       <td style="background-color: rgb(0, 255, 128);">TOC</td>
       <td style="background-color: rgb(0, 255, 128);">Mern</td>
       <td style="background-color: rgb(0, 255, 128);">Crypto</td>
    </tr>
    <tr>
        <td style="background-color: yellow;">1-3 </td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
        <td style="background-color: rgb(0, 255, 128);">Mern</td>
        <td style="background-color: rgb(0, 255, 128);">Game</td>
        <td style="background-color: rgb(0, 255, 128);">Game</td>
        <td style="background-color: rgb(0, 255, 128);">Compiler</td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
    </tr>
    <tr>
        <td style="background-color: yellow;">3-5 </td>
        <td style="background-color: rgb(0, 255, 128);">Crypto</td>
        <td style="background-color: rgb(0, 255, 128);">Compiler</td>
        <td style="background-color: rgb(0, 255, 128);">Compiler</td>
        <td style="background-color: rgb(0, 255, 128);">Web</td>
        <td style="background-color: rgb(0, 255, 128);">Trainning</td>
        <td style="background-color: rgb(0, 255, 128);">Web</td>
    </tr>
    
</table>

</body>
</html>

## OUTPUT
![Slot SS](https://github.com/thegreyhatman/slot/assets/136783487/3a3f679c-4041-4851-b8c1-c2233b967081)


## HTML VALIDATOR


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
