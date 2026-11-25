# Ex04 Time Table
## Date:19/11/2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>Time Table</title>
        <img src="logo.png" style="display:block ; margin: auto; margin-left:auto; margin-right: auto ; width: 100%; max-width: 580px ; height: auto;"><br><br>
    </head>
    <body>
        
     <table align="center" border="1" cellspacing="2" cellpading="12" >
     
        <tr bgcolor="lightpink" align="center">
            <td> Day/Time </td>
            <td> Monday </td>
            <td> Tuesday </td>
            <td> Wednesday </td>
            <td> Thursday </td>
            <td> Friday </td>
            <td> Saturday </td>
        </tr>

        <tr align="center">
            <td bgcolor="lightpink"> 8:00-9:30 </td>
            <td> DE </td>
            <td> EDM </td>
            <td> FWAD </td>
            <td> Free slot </td>
            <td> math </td>
            <td> PS </td>
        </tr>
        
        <tr align="center">
            <td bgcolor="lightpink"> 9:30-11:15 </td>
            <td> FWAD </td>
            <td> EDM </td>
            <td> Free slot </td>
            <td> math </td>
            <td> Free slot </td>
            <td> DE </td>
        </tr>

        <tr>
            <td bgcolor="lightpink"> 11:30-12:15 </td>
            <td colspan="6" align="center"> Mentor Meet or Event </td>
        </tr>

         <tr>
            <td bgcolor="lightpink"> 12:15-01.15 </td>
            <td colspan="6" align="center"> Lunch Break </td>
        </tr>

        <tr align="center">
            <td bgcolor="lightpink"> 01.15-02.44 </td>
            <td> Free Slot </td>
            <td> FWAD </td>
            <td> Free Slot </td>
            <td> PS </td>
            <td colspan="2" align="center"> Free slot </td>
        </tr>

        <tr align="center">
            <td bgcolor="lightpink"> 03:00-04:30 </td>
            <td colspan="2" align="center"> Free Slot </td>
            <td> PP </td>
            <td> Free slot </td>
            <td> PP </td>
            <td> PP </td>
        </tr>

     </table><br><br>
     <table align="center" border="1" cellspacing="2" cellpading="12">
      <caption align="center" style="font-family:'Times New Roman', Times, serif; font: size 45px;"><b>SLOT TIME TABLE - Sherin liya J.E[26019443]</b></caption>

     <tr bgcolor="lightgreen" align="center">
        <td> S.No </td>
        <td> Subject Code </td>
        <td> Subject Name </td>
     </tr>
     <tr align="center">
        <td> 1. </td>
        <td> 19AI414 </td>
        <td> Fundamentals of Web Application Development(FWAD) </td>
     </tr>
     <tr align="center">
        <td> 2. </td>
        <td> 19AI301 </td>
        <td> Python Programming(Python) </td>
     <tr align="center">
        <td> 3. </td>
        <td> 19AI302 </td>
        <td> Engineering Design And Modelling(EDM) </td>
     <tr align="center">
        <td> 4. </td>
        <td> 19EE404 </td>
        <td> Digital Electronics</td>
     <tr align="center">
        <td> 5. </td>
        <td> 19EN105 </td>
        <td> Public Speaking</td>
     <tr align="center">
        <td> 6. </td>
        <td> 19MA211 </td>
        <td> Statics Numericals and Methods </td>
     </tr>
     
     </table>
    </body>
</html>
```
## OUTPUT
![alt text](<Screenshot (27).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
