3)CREATE A TABLE WITH ROWS AND COLOUMNS AND PLACE AN IMAGE IN ONE COLOUMN

<html lang="en">

<head>

<title>TIMETABLE</title>

</head>

<body align="center" bgcolor="blue">

<p> TIMETABLE</p>

<font color="black">

<table border="2" cellspacing="3" cellpadding="3" align="center"

bgcolor="grey">

<tr>

<th>DAY</th>

<th>8:45-9:45</th>

<th>9:45-10:45</th>

<th>10:45-11</th>

<th>11-12</th>

</tr>

<tr>

<td>MONDAY</td>

<td>PHP/MYSQL</td>

<td>WEB TECHNOLOGY</td>

<td>PYTHON</td>

<td rowspan="6" align="center">B<br>R<br>E<br>A<br>K</td>

</tr>

<tr>

<td>TUESDAY</td>

<td>PHP/MYSQL</td>

<td>WEB TECHNOLOGY</td>

<td>PYTHON</td>

</tr>

<tr>

<td>WEDNESDAY</td>
<td>PHP/MYSQL</td>

<td>WEB TECHNOLOGY</td>

<td>PYTHON</td>

</tr>

<tr>

<td>THURSDAY</td>

<td>PHP/MYSQL</td>

<td>WEB TECHNOLOGY</td>

<td>PYTHON</td>

</tr>

<tr>

<td>FRIDAY</td>

<td>PHP/MYSQL</td>

<td>WEB TECHNOLOGY</td>

<td>PYTHON</td>

</tr>

<tr>

<td>SATURDAY</td>

<td>PHP/MYSQL</td>

<td>WEB TECHNOLOGY</td>

<td>PYTHON</td>

</tr>

<tr>

<td>SUNDAY <br> HOLIDAY</td>

<td colspan="4" align="center"><img src="C:\Users\ADITYA\Pictures\adityalogo png" height=100 width=100></td>

</tr>

</table>

</font>

</body>

</html?


4) using table tag,align the imageas follows

CODE:

<html>

<body bgcolor=lightyellow>

<table border=2 align=center>

<caption align=center>

<h1>ALIGNMENT OF IMAGES USING TABLE TAG</h1>

</caption>

<th><img src="C:\Users\ADITYA\Pictures\IMG1.jfif" height=100 width gamma = 100 >

<th><img src="C:\Users\ADITYA\Pictures\IMG2.jfif" height t = 100 width gamma = 100 >

<th><img src="C:\Users\ADITYA\Pictures\IMG3.jfif" height t = 100 width i = 100 >

</tr>

<tr>

<td align=center colspan=5><b><FONT COLOR=RED>BEAUTIFUL FLOWERS</

FONT></b></td>

</tr>

<th><img src="C:\Users\ADITYA\Pictures\IMG4.jfif" height=100 width I = 100 >

<th><img src="C:\Users\ADITYA\Pictures\IMG5.jfif" height=100 width n = 100 >

<th><img src="C:\Users\ADITYA\Pictures\IMG6.jfif" height=100 width I = 100 >

</tr>

</body>

</html>


5) create a menu from using HTML
CODE:

<!Doctype Html>

<Html>

<Head>

<Title></Title>

</Head>

<Body><form><label> SELECT SUBJECT </label>

<select>

<option value = "WEB TECHNOLOGY"> WEB TECHNOLOGY

</option>

<option value = "WEBPROGRAMMING"> WEBPROGRAMMING

</option>

<option value = "IOT"> IOT

</option>

<option value = "DATASCIENCE WITH PYTHON"> DATASCIENCE WITH PYTHON

</option>

</select>

</form></Body>

</Html>


6) style the menu buttons using CSS
CODE:

<IDOCTYPE html>

<html>

<head>

<meta name="viewport" content="width=device-width, initial-scale=1">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-

awesome/4.7.0/css/font-awesome.min.css">

<style>

body {

font-family: Arial, Helvetica, sans-serif;

.navbar {

overflow: hidden;

background-color: #333;

}

.navbar a {

float: left;

font-size: 16px;

color: white;

text-align: center;

padding: 14px 16px;

text-decoration: none;

}

.dropdown {

float: left;

overflow: hidden;

}

.dropdown.dropbtn {
font-size: 16px;
border: none;

outline: none;

color: white;

padding: 14px 16px;

background-color: inherit;

font-family: inherit;

margin: 0;

}

navbar a:hover, .dropdown:hover.dropbtn {

background-color: red;

}

.dropdown-content {

display: none;

position: absolute;

background-color: #f9f9f9;

min-width: 160px;

box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);

z-index: 1;

}

.dropdown-content a {

float: none;

color: black;

padding: 12px 16px;

text-decoration: none;

display: block;

text-align: left;

}

.dropdown-content a:hover {

background-color: #ddd;

}

dropdown:hover dropdown-content {

display: block;

</style>

</head>

<body>

<div class="navbar">

<a href="#home">Home</a>

<a href="#news">News</a>

<div class="dropdown">

<button class="dropbtn">Dropdown

<i class="fa fa-caret-down"></i>

</button>

<div class="dropdown-content">

<a href="#">Link 1</a>

<a href="#">Link 2</a>

<a href="#">Link 3</a>

</div>

</div>

</div>

<h3> Menu Buttons with Dropdown list</h3>

<p>Click on the "Dropdown" link to see the dropdown menu.</p>

</body>

</html>



7) create a form using HTML which has the following types of control a) text box, option/radio button, check button, reset and submit buttons

CODE:-

<html>
<head>

<title>LOGIN FORM</title>

</head>

<body ALIGN="CENTER"BORDER="2" style="margin-top: 100

background="https://png.pngtree.com/thumb_back/fw800/back_our/20190620/ourmid/pngtree-national-dance-dance-culture-training-enrollment-poster-background-image_155204 jpg"><h2 style="color:blue">REGISTRATION</H2>

<TABLE BORDER="2" ALIGN="CENTER">

<form ACTION="https://www.hackerrank.com" METHOD="POST">

<TR><TD><label >NAME</label></TD>

<TD><SELECT>

<option value="MR">MR</OPTION>

<OPTION VALUE="MS">MS</OPTION>

</SELECT>

<input type="text" placeholder="TIM BERNERS LEE" required/></TD></TR>

<TR><TD><label>EMAIL</label></TD>

<TD><input type="email" placeholder="TIM@gmail.com" required/></TD></TR>

<TR><TD><label>DOB</label></TD>

<TD><input type="DATE" placeholder="DD-MM-YYYY" required/></TD></TR>

<TR><TD><label>AGE</label></TD>

<TD><input type="NUMBER" placeholder="AGE" required/></TD></TR>

<TR><TD><label>NUMBER</label></TD>

<TD><input type="text" placeholder="MOBILE NUMBER" required/></TD></TR>

<TR><TD><label>COUNTRY</label></TD>

<TD><SELECT>S

<OPTION VALUE="INDIA">INDIA</OPTION>

<OPTION VALUE="INDIA">USA</OPTION>

<OPTION VALUE="INDIA">JAPAN</OPTION>

<OPTION VALUE="INDIA">KOREA</OPTION>

<OPTION VALUE="INDIA">UK</OPTION>

<OPTION VALUE="INDIA">GREENLAND</OPTION>

</SELECT></TR></TD>

<TR><TD><LABEL YEAR OF PASSING</LABEL></TD>

<TD><INPUT TYPE="RADIO" NAME="YEAR">2021</INPUT><BR>

<INPUT TYPE="RADIO" NAME="YEAR">2020</INPUT><BR>

<INPUT TYPE="RADIO" NAME="YEAR">2019</INPUT></TD></TR>

<TR><TD> SKILLS</TD>

<TD>

<OL>

<LI><INPUT TYPE="CHECKBOX">C</INPUT></LI>

<LI><INPUT TYPE="CHECKBOX">JAVA</INPUT></LI>

<LI><INPUT TYPE="CHECKBOX">DBMS</INPUT></LI>

<LI><INPUT TYPE="CHECKBOX">JAVASCRIPT</INPUT></LI>

<LI><INPUT TYPE="CHECKBOX">HTML</INPUT></LI>

<LI><INPUT TYPE="CHECKBOX">CSS</INPUT></LI>

<LI><INPUT TYPE="CHECKBOX">PHP</INPUT></LI>

<LI><INPUT TYPE="CHECKBOX">PYTHON</INPUT></LI>

</OL></TD></TR>

<TR><TD><label>ADDRESS</label></TD>

<TD><TEXTAREA REQUIRED PLACEHOLDER "ADDRESS"></TEXTAREA></TD></TR>

<TR><TD>PHOTO</TD><TD><INPUT TYPE="FILE" REQUIRED></INPUT></TD></TR>

<TR><TD>RESUME</TD><TD><INPUT TYPE="FILE" REQUIRED"></INPUT></TD></TR>

<TR><TD COLSPAN="2" ALIGN="CENTER"><INPUT TYPE="SUBMIT"></INPUT></TR>

</FORM>

</TABLE>

</body>

</html>

--------------the end-----------------

                           Rohit_01
