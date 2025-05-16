# Ex03 Time Table
## Date:16-05-2025

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
<HTML>
    <HEAD>
        <TITLE>Time Table</TITLE>
    </HEAD>
    <BODY>
        <center><img src="/static/logo.png"  width="500" height="100" ></center>
        <TABLE border = "1"  cellpadding = "5" bgcolor = "#f4f6f7">
            <CAPTION>SLOT TIME TABLE - Prasidha A (24005839)</CAPTION>
            <TR bgcolor = "#ec7063">
                <TH>DAY/TIME</TH>
                <TH>8 - 10</TH>
                <TH>10 - 12</TH>
                <TH rowspan = "7">Lunch</TH>
                <TH>1 - 3</TH>
            </TR>
            <TR>
                <TH bgcolor = "#ec7063">Monday</TH>
                <TD>Web Development</TD>
                <TD>Task Completion</TD>
                <TD>Fundamental of AI</TD>
            </TR>
            <TR>
                <TH bgcolor = "#ec7063">Tuesday</TH>
                <TD>Task Completion</TD>
                <TD>Web Development</TD>
                <TD>Module Completion</TD>
            </TR>
            <TR>
                <TH bgcolor = "#ec7063">Wednesday</TH>
                <TD>Assessment Hour</TD>
                <TD>Task Completion</TD>
                <TD>Mentor Meet</TD>
            </TR>
            <TR>
                <TH bgcolor = "#ec7063">Thursday</TH>
                <TD>Task Presentation</TD>
                <TD>Module Completion</TD>
                <TD>Fundamental of AI</TD>
            </TR>
            <TR>
                <TH bgcolor = "#ec7063">Friday</TH>
                <TD>Task Completion</TD>
                <TD>Web Development</TD>
                <TD>Module Completion</TD>
            </TR>
            <TR>
                <TH bgcolor = "#ec7063">Saturday</TH>
                <TD>Module Assessment Completion</TD>
                <TD>Module Assessment Completion</TD>
                <TD>Module Assessment Completion</TD>
            </TR>
        </TABLE>
```


## OUTPUT
![image](https://github.com/user-attachments/assets/d90c32cc-43dd-4819-96b4-ac3880f158b0)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
