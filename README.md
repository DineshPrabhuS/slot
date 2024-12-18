# Ex03 Time Table
## Date:07.12.2024

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
        <title>
            Slot
        </title>
    </head>
    <BODY>
        <CENTER><img src="C:\Users\admin\Documents\web\slot\logo.png" width="800"></CENTER>
        <TABLE ALIGN="CENTER" BGCOLOR="CYAN" BORDER="2" CELLSPACE="10" STYLE="width:60%">
            <caption ALIGN="CENTER"><h2> TIME TABLE - DINESH PRABHU S (24004388)</h2></caption>
            <TR BGCOLOR="YELLOW">
                <TH WIDTH="16%" ALIGN="CENTER">TIMING/DAYS</TH><TH WIDTH="12%" ALIGN="CENTER">MONDAY</TH><TH WIDTH="12%" ALIGN="CENTER">TUESDAY</TH><TH WIDTH="12%" ALIGN="CENTER">WEDNESDAY</TH><TH WIDTH="12%" ALIGN="CENTER">THURSDAY</TH><TH WIDTH="12%" ALIGN="CENTER">FRIDAY</TH><TH WIDTH="12%" ALIGN="CENTER">SATURDAY</TH>
            </TR>
            <TR>
                <TH WIDTH="16%" BGCOLOR="YELLOW" ALIGN="CENTER">8AM TO 10AM</TH><TD WITH="12%" ALIGN="CENTER" COLSPAN="2">FREE SLOT</TD><TD WITH="12%">PYTHON PROGRAMMING</TD><TD WITH="12%">FUNDAMETALS OF C PROGRAMMIG</TD><TD WITH="12%" ALIGN="CENTER" COLSPAN="2">FREE SLOT</TD>
            </TR>   
            <TR>
                <TH WIDTH="16%" BGCOLOR="YELLOW" ALIGN="CENTER">10AM TO 12PM</TH><TD WITH="12%">PYTHON PROGRAMMING</TD><TD WITH="12%">DIGITAL ELECTRONICS</TD><TD WITH="12%">CALCULAS AND MATRICE ALGEBRA</TD><TD WITH="12%">PRINCICPLES OF CHEMISTRY IN ENGINEERING</TD><TD WITH="12%">DIGITAL ELECTRONIC</TD><TD WITH="12%">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD>
            </TR>
            <TR>
                <TH WIDTH="16%" BGCOLOR="YELLOW" ALIGN="CENTER">12PM TO 1PM</TH><TH COLSPAN="6"> LUNCH BREAK</TH>
            </TR>
            <TR>
                <TH WIDTH="16%" BGCOLOR="YELLOW" ALIGN="CENTER">1PM TO 3PM</TH><TD WITH="12%">PRINCIPLES OF CHEMISTRY IN ENGINEERING</TD><TD WITH="12%">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD><TD WITH="12%">MENTOR MENTEE MEET</TD><TD WITH="12%">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD><TD WITH="12%">CALCULAS AND MATRICE ALGEBRA</TD><TD WITH="12%">FUNDAMENTALS OF C PROGRAMMING</TD>
            </TR>
            <TR>
                <TH WIDTH="16%" BGCOLOR="YELLOW" ALIGN="CENTER">3PM TO 5PM</TH><TH COLSPAN="6"> FREE SLOT </TH>
            </TR>
        </TABLE>
        <BR>
            <TABLE ALIGN="CENTER" BORDER="2" CELLSPACE="30" STYLE="width:60% ">
            <TR>
                <TH WIDTH-="10%">S.No.</TH><TH WIDTH="25%">SUBJECT CODE</TH><TH WIDTH="65%">SUBJECT NAME</TH>
            </TR>
            <TR>
                <TH WIDTH-="10%">1.</TH><TH WIDTH="25%">19AI414</TH><TH WIDTH="65%">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</TH>
            </TR>
            <TR>
                <TH WIDTH-="10%">2.</TH><TH WIDTH="25%">19AI304</TH><TH WIDTH="65%">FUNDAMENTALS OF C PROGRAMING(FOC)</TH>
            </TR>
            <TR>
                <TH WIDTH-="10%">3.</TH><TH WIDTH="25%">19AI301</TH><TH WIDTH="65%">PYTHON PROGRAMMING(PP)</TH>
            </TR>
            <TR>
                <TH WIDTH-="10%">4.</TH><TH WIDTH="25%">19EE404</TH><TH WIDTH="65%">DIGITAL ELECTRONICS(DE)</TH>
            </TR>
            <TR>
                <TH WIDTH-="10%">5.</TH><TH WIDTH="25%">19MA201</TH><TH WIDTH="65%">CALCULAS AND MATRICE ALGEBRA(MATH)</TH>
            </TR>
            <TR>
                <TH WIDTH-="10%">6.</TH><TH WIDTH="25%">19CY205</TH><TH WIDTH="65%">PRINCIPLES OF CHEMISTRY IN ENGINEERING(CHE)</TH>
            </TR>
        </TABLE>
    </BODY>
</html>
```

## OUTPUT

![alt text](<Screenshot (143).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
