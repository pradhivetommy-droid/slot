# Ex03 Time Table
## Date:20/09/2025

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
        <title>Ragul-25014743</title>
    </head>
    <body>
        
         <center>
        <table style="border: dashed 3px blue; width:50%;height:45%;border-collapse:collapse;text-align:center;color:black" >
            <hr>
          <marquee><h1>SLOT TIMETABLE-RAGUL 25014743</marquee></h1>  <hr>  <tr bgcolor="39CCCC">
                <td>Day/Time</td>
                <td>Monday</td>
                <td>Tuesday</td>
                <td>Wednesday</td>
                <td>Thursday</td>
                <td>Friday</td>
                <td>Saturday</td>
            </tr>
            <tr>
                <td bgcolor="39CCCC">8-10</td>
                <td bgcolor="D3D3D3">ENG</td>
                <td bgcolor="D3D3D3">FREE</td>
                <td bgcolor="D3D3D3">FWAD</td>
                <td bgcolor="D3D3D3">ENG</td>
                <td bgcolor="D3D3D3">PYTH</td>
                <td bgcolor="D3D3D3">FWAD</td>
            </tr>
            <tr>
                <td bgcolor="39CCCC">10-12</td>
                <td bgcolor="32CD32">FREE</td>
                <td bgcolor="32CD32">PYTH</td>
                <td bgcolor="32CD32">FWAD</td>
                <td bgcolor="32CD32">FREE</td>
                <td bgcolor="32CD32">PYTH</td>
                <td bgcolor="32CD32">PYTH</td>
            </tr>
            <tr>
                <td bgcolor="39CCCC">12-1</td>
              <td colspan="6" bgcolor="1E90FF"> <center>LUNCH</center></td>
            </tr>
            <tr>
                <td bgcolor="39CCCC">1-3</td>
                <td bgcolor="8A2BE2">ENG</td>
                <td bgcolor="8A2BE2">ENG</td>
                <td bgcolor="8A2BE2">MENT</td>
                <td bgcolor="8A2BE2">ENG</td>
                <td bgcolor="8A2BE2">FWAD</td>
                <td bgcolor="8A2BE2">FWAD</td>
            </tr>
            <tr >
                <td bgcolor="39CCCC">3-5</td>
                <td bgcolor="FF8C00">FREE</td>
                <td bgcolor="FF8C00">FREE</td>
                <td bgcolor="FF8C00">PYTH</td>
                <td bgcolor="FF8C00">FREE</td>
                <td bgcolor="FF8C00">ENG</td>
                <td bgcolor="FF8C00">FREE</td>


            </tr>
            
         
        </table>
        </center>
       
    </body>
</html>


```

## OUTPUT
![alt text](<Screenshot (9)-1.png>)
![alt text](<Screenshot (10)-1.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
