# Ex03 Time Table
## Date:06/11/2024

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
<html></html>
    </head>
	<body align="center" bgcolor="BLACK" >
		 <center>
            <img src= "/static/logo.png" height="100" width="800">
         </center>
		<table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="WHITE">
			<caption>SLOT TIME TABLE- JAGADEESH J (212223110015) </caption>
            <br>
			<tr>
				<th bgcolor="WHITE"> Day/Time </th>
				<th bgcolor="WHITE"> Monday </th>
				<th bgcolor="WHITE"> Tuesday </th>
                <th bgcolor="WHITE"> Wednesday </th>
                <th bgcolor="WHITE"> Thursday </th>
                <th bgcolor="WHITE"> Friday </th>
                <th bgcolor="WHITE"> Saturday </th>
			</tr>
			<tr>
				<th bgcolor="WHITE"> 8-10 </td>
                <td> FREE SLOT </td>
                <td>ML</td>
                <td> WEB</td>
                <td> PIOT </td>
                <td> PMC </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="WHITE"> 10-12 </th>
				<td> PIOT </td>
                <td> FREE SLOT </td>
                <td> ML</td>
                <td> FREE SLOT </td>
                <td> OS</td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="WHITE"> 12-1 </th>
                <td colspan="6" align="center"> LUNCH </td>
			</tr>
			<tr>
                <th bgcolor="WHITE"> 1-3 </th>
                <td> PMC </td>
                <td> FREE SLOT </td>
                <td> MENTOR MEET </td>
                <td> DBMS </td>
                <td> EMPD </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="WHITE"> 3-5 </td>
                <td> EMPD </td>
                <td> FREE SLOT </td>
                <td> MATH </td>
                <td> OS </td>
                <td> MATH </td>
                <td> FREE SLOT  </td>
			</tr>
			</table>
            <br>
            <table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="RED">
                <br>
                <tr>
                    <th align="center"> S.No </th>
                    <th align="center"> Subject Code </th>
                    <th align="center"> Subject Name </th>
                </tr>
                <tr>
                    <th> 1. </td>
                    <td align="center"> 19AI410 </td>
                    <td align="center"> INTRODUCTION TO MACHINE LEARNING (ML) </td>
                </tr>
                <tr>
                    <th align="center"> 2. </td>
                    <td align="center"> 19AI414 </td>
                    <td align="center"> FUNDAMENTAL OF WEB APPLICATION (WEB) </td>
                </tr>
                <tr>
                    <th align="center"> 3. </td>
                    <td align="center"> 19CS405 </td>
                    <td align="center"> OPERATING SYSTEM(OS) </td>
                </tr>
                <tr>
                    <th align="center"> 4. </td>
                    <td align="center"> 19AI303 </td>
                    <td align="center"> ENGINEERNIG MECHANICS AND PRODECT DEVELOPMENT(EMPD) </td>
                </tr>
                <tr>
                    <th align="center"> 5. </td>
                    <td align="center"> 19EE309 </td>
                    <td align="center"> PROGRAMMING MICROCONTROLLER (PMC) </td>
                </tr>
               
                <tr>
                    <th align="center"> 6. </td>
                    <td align="center"> 19C5405 </td>
                    <td align="center"> DATABASE MANAGEMENT DYSTEM AND ITS APPLICATION (DBMS) </td>
                </tr>
                <tr>
                    <th align="center"> 7. </td>
                    <td align="center"> 19CS420 </td>
                    <td align="center"> PROTOTYPING OF IOT SYSTEM(PIOT) </td>
                </tr>
                <tr>
                    <th align="center"> 8. </td>
                    <td align="center"> 19MA219 </td>
                    <td align="center"> MATH  </td>
                </tr>
                
                </table>
	</body>

</html>
```
## OUTPUT
![alt text](<Screenshot 2024-11-06 102550.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
