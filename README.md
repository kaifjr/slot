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

## PROGRAM
```C
<html>
    <head>
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="500">
        </center>
        <br>
        <table align="center" width="540">
            <caption><b>SLOT TIMETABLE KAIF MOHAMED(212222043004)</b></caption>
            <table border="2px" cellpadding="4px"> 
            <tr align="center">
                <th bgcolor="red">Day/Time</th>
                <th bgcolor="red">Monday</th>
                <th bgcolor="red">Tuesday</th>
                <th bgcolor="red">Wednesday</th>
                <th bgcolor="red">Thursday</th>
                <th bgcolor="red">Friday</th>
            </tr>
            <tr align="center">
                <th bgcolor="blue">8-10</th>
                <td bgcolor="lightgreen">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="lightgreen">ETHICAL HACKING TECHNIQUES</td>
                <td bgcolor="lightgreen">INTRODUCTION TO IOT</td>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="lightGREEN">INTRODUCTION TO IOT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">10-12</th>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="ligthgreen">COMPUTER NETWORKS</td>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="lightgreen">COMPUTER NETWORKS</td>
                <td bgcolor="pink">FREE SLOT</td>
            </tr>
            <tr bgcolor="cyan" align="center">
                <th bgcolor="cyan">12-1</th>
                <td colspan="5" align="center"> L U N C H </td>
            <tr align="centre">
                <th bgcolor="blue">1-3</th>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="ligthgreen">Programming in C</td>
                <td bgcolor="lightgreen">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="ligthgreen">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th bgcolor="blue">1-5</th>
                <td colspan="3" align="center"> FREE SLOT </td>
                <td bgcolor="lightgreen">Soft Skills</td>
                <td bgcolor="pink">FREE SLOT</td>
            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr> 
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AM508</td>
                <td>INTRODUCTION TO IOT(IOT)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19CS417</td>
                <td>ETHICAL HACKING TECHNIQUES(EHT)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19CS406</td>
                <td>COMPUTER NETWORKS(CN)</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19CS302</td>
                <td>C PROGRAMMING(C)</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19EY701</td>
                <td>SOFT SKILLS (SS)</td>
            </tr>
        </table>
    </body>
</html>
```


## OUTPUT
![ex3](https://github.com/kaifjr/slot/assets/147469730/eb17b075-3d91-42a8-8e7b-7a1e8c579c78)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
