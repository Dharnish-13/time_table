# Ex03 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
HTML
```
<html>
    <head>
      <title>MY TIME TABLE</title>
      <link rel="icon" type="image/png"
      href="saveetha logo.jpeg">
      <style>
        table,th,td{
           border:3px solid black ;
           width: 100px;
           border-collapse: collapse;
           margin: 20px;
           font-style: initial;
           background-color: aqua;
           margin-left: auto;
           margin-right: auto;
        }
        th{
            background-color: antiquewhite;
        }
        td{
            background-color: aliceblue;
        }
        caption{
            font-size: 20px;
            margin: 10px;
            background-color: blue;
        }
        span{
            writing-mode: vertical-rl;
            text-orientation:upright;
            letter-spacing: 10px;
        }
        img{
            display: block;
            width: 850px;
            height: 200px;
            margin-left: auto;
            margin-right: auto;
        }
        table {
    width: 600px;
}
td[rowspan] {
    text-align: center;      /* Horizontal center  */
    vertical-align: middle;  /* Vertical center    */
}
body{
    background-image: url("backgroundforwebsite.jpg");
    background-size: cover;      /* makes image fit the screen */
    background-repeat: no-repeat; /* prevents repeating */
    background-position: center;
}
 </style>  
    </head>
    <body>
       <img src= " sec-logo-01as.png">
        <h1 style="text-align: center;">MY TIME TABLE</h1>  
 <table>
 <tr>
    <th>days/time</th>
    <th>8:00-10:00</th>
    <th>10:00-12:00</th>
    <th>12:00-1:00</th>
    <th>1:00-3:00</th>
    <th>3:00-5:00</th>
 </tr>
 <tr>
    <td style="background-color: aqua;">MONDAY</td>
    <td>C PRG</td>
    <td>FREE SLOT</td>
    <td rowspan="6"><span>LUNCH</span></td>
    <td>FREE SLOT</td>
    <td>ENGLISH</td>
 </tr>
 <tr>
    <td style="background-color: aqua;">TUESDAY</td>
    <td>FREE SLOT</td>
    <td>FREE SLOT</td>
    <td>FWAD</td>
    <td>FREE SLOT</td>
 </tr>
<tr>
    <td style="background-color: aqua;">WEDNESDAY</td>
    <td>C PRG</td>
    <td>FWAD</td>
    <td>MENTOR MEET</td>
    <td>FREE SLOT</td>
</tr>
<tr>
    <td style="background-color: aqua;">THURSDAY</td>
    <td>FREE SLOT</td>
    <td>ENGLISH</td>
    <td>FREE SLOT</td>
    <td>C PRG</td>
</tr>
<tr>
    <td style="background-color: rgb(0, 255, 221);">FRIDAY</td>
    <td>FREE SLOT</td>
    <td>FWAD</td>
    <td>ENGLISH</td>
    <td>C PRG</td>
</tr>
<tr>
<td style="background-color: rgb(0, 255, 251);">SATURDAY</th>
<td>FWAD</td>
<td>FWAD</td>
<td>C PRG</td>
<td>ENGLISH</td>
</tr>
 </table>
<table>
    <tr>
     <th>Subject</th>
    <th>Sub-Code</th>
     </tr>
    <tr>
     <td>FWAD-Fundamentals of web apllication development</td>
 <td>19AI414</td>
</tr>
<tr>
    <td>c-programming</td>
    <td>19AI304</td>
    </tr>
    <tr>
    <td>communicative-english</td>
    <td>19EN101</td>
</tr>
</table>
</body>
</html>
```
# OUTPUT
<img width="1920" height="1080" alt="Screenshot 2025-11-28 230535" src="https://github.com/user-attachments/assets/12d14182-132c-46cb-89f2-5596713acc63" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
