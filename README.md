# Ex03 Time Table
# Date: 02-12-2024
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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Timetable</title>
    <center><img src="saveetha image.png"></center>

    
</head>
<style>
    table,td,tr{
        border: 2px solid  rgba(21, 21, 137, 0.707);
        border-radius: 3px;
        margin-top: 40px;
       
    }
    .one, td,tr,th{
        border: 2px solid rgba(21, 21, 137, 0.707);
        border-radius: 3px;
        width: 500px;
        height: 40px;
        text-align: center;
        

    }
    
</style>
<body>
    <center>
        
    <table class="one" >
        
        <tr>
            <th>Days</th>
            <th style="width: 50px;">8-10 </th>
            <th style="width: 50px;">10-12</th>
            <th rowspan="7" style="width: 40px;">L<BR>U<BR>N<BR>C<BR>H</th>
            <th style="width: 50px;">1-3</th>
            <th style="width: 50px;">3-5</th>
        </tr>
        <tr>
            <th>MON</th>
            <td></td>
            <td>WEB</td>
            <td></td>
            <TD></TD>
        </tr>
        <TR>
            <TH>TUE</TH>
            <TD>CE</TD>
            <TD></TD>
            <TD>PY</TD>
            <TD></TD>
        </TR>
        <TR>
            <TH>WED</TH>
            <TD></TD>
            <TD></TD>
            <TD></TD>
            <TD>che</TD>
        </TR>
        <TR>
            <TH>THUR</TH>
            <TD>EDM</TD>
            <TD>PY</TD>
            <TD>WEB</TD>
            <TD>Che</TD>
        </TR>
        <tr>
            <TH>FRI</TH>
            <TD>CE</TD>
            <TD></TD>
            <TD>PY</TD>
            <TD></TD>
        </tr>
        <TR>
            <TH>SAT</TH>
            <TD>EDM</TD>
            <TD></TD>
            <TD>PY</TD>
            <TD>WEB</TD>
        </TR>
    

    </table>

    <table >
        <tr>
            <th>sub-code</th>
            <th>sub-name</th>

        </tr>
        <tr>
            <th>19AI301C</th>
            <td>Python and linear Algebra</td>
        </tr>
        <tr>
            <th>19AI302</th>
            <td>Engineering Design And Modeling</td>
        </tr>
        <tr>
            <th>19AI414</th>
            <td>Fundamendals of Web Application Development </td>
        </tr>
        <tr>
            <th>19CY205</th>
            <td>Principles of Chemistry in Engineering</td>
        </tr>
        <tr>
            <th>19EN101</th>
            <td>Communicative English</td>
        </tr>
        <tr>
            <td colspan="2">ECA-M -SCOFT - Mentor Meet</td>
        </tr>
    </table>
</center>

</body>
</html>

~~~
# OUTPUT
![Screenshot (86)](https://github.com/user-attachments/assets/9ac24c18-445d-472c-96cc-e4dfc52b6eb9)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
