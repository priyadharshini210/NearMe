# Ex04 Places Around Me
## Date: 22/03/2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html

<html>
<head>
<title>MY CITY</title>
</head>
<body>
<h1 align="center">
<font color="black"><b>MELUR</b></font>
</h1>
<h3 align="center">
<font color="green"><b>PRIYADHARSHINI.P(212223240128)</b></font>
</h3>
<center>
<img src="Screenshot 2024-03-24 144347.png" usemap="#image-map">

<map name="image-map">
    <area target="_self" alt="Spartanz Fitness" title="Spartanz Fitness" href="fitness.html" coords="657,687,483,572" shape="rect">
    <area target="_self" alt="Government Hospital" title="Government Hospital" href="hospital.html" coords="464,142,642,231" shape="rect">
    <area target="_self" alt="RTO Office Melur" title="RTO Office Melur" href="office.html" coords="1154,644,69" shape="circle">
    <area target="_self" alt="Ganesh Theatre Complex" title="Ganesh Theatre Complex" href="theatre.html" coords="723,299,840,380" shape="rect">
    <area target="_self" alt="Poorvika Mobiles Melur" title="Poorvika Mobiles Melur" href="mobiles.html" coords="509,322,661,430" shape="rect">
</map>
</center>
</body>
</html>

finess.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="silver"><b>MELUR</b></font>
</h1>
<h3 align="center">
<font color="red"><b>Spartanz Fitness</b></font>
</h3>
<hr size="3" color="green">
<p align="justify">
<font face="Georgia" size="6">
  It is located in melur,madursi district. At Thiruvathoor Road Near Old EB Office.
   Opposite to Meenakshi amma illam.
   </font>
</p>
</body>
</html>

hospital.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="white"><b>MELUR</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>Goverment Hospital</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="6">
It is located near railways station,Madurai Main Rd; Azhagarkovil Road, Nagaikadai Bazaar
 Opposite To Taluk Office madurai district.
It is popular for cardiology. It is Sub-District Hospital.
</font>
</p>
</body>
</html>

mobiles.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="brown"><b>MADURAI</b></font>
</h1>
<h3 align="center">
<font color="yellow"><b>Poorvika Mobiles Melur</b></font>
</h3>
<hr size="4" color="black">
<p align="justify">
<font face="Georgia" size="6">
    Poorvika sells a wide category of devices in its showrooms and Online portal.
   It is located at Trichy Main Rd, near Bus Stand,in Arittapatti,Melur, Tamil Nadu
</font>
</p>
</body>
</html>

office.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="white"><b>MELUR</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>RTO office Melur</b></font>
</h3>
<hr size="4" color="white">
<p align="justify">
<font face="Georgia" size="6">
    The RTO Office in Melur, Madurai offers a wide range of services related to vehicle registration, licensing and  t
    the Melur RTO is also responsible for collection of taxes, issuing permits. 
    It is located at Kela St, Kannakudi, Lalkudi,melur at madurai distict.
</font>
</p>
</body>
</html>

theatre.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="blue"><b>MELUR</b></font>
</h1>
<h3 align="center">
<font color="grey"><b>Ganesh Theatre</b></font>
</h3>
<hr size="3" color="pink">
<p align="justify">
<font face="Georgia" size="6">
    Melur Ganesh Complex A C Dts 2k 3d is a chain of theatres in India that exhibit a myriad of movies around the year. 
    Cinema featuring a lineup of Tamil films in 3 air-conditioned theatres, plus a canteen.
    Ganesh Theatre Complex is situated southwest of Granite quarry, and northwest of Vellalore Government Hospital,at melur,madurai district.
    </font>
</p>
</body>
</html>
```
## OUTPUT
![Screenshot (6)](https://github.com/priyadharshini210/NearMe/assets/148514638/4de3ebfa-7c07-4b57-8efb-586ddee72cfa)
![Screenshot 2024-03-24 154257](https://github.com/priyadharshini210/NearMe/assets/148514638/a7cc2bf4-c2d9-4dea-8a1a-57aa9f1c6fda)
![Screenshot 2024-03-24 155855 - Copy](https://github.com/priyadharshini210/NearMe/assets/148514638/c60239f7-35fc-430c-a82d-c461b282fa64)
![Screenshot 2024-03-24 160329](https://github.com/priyadharshini210/NearMe/assets/148514638/37c27692-4f3e-48a0-b4cb-9ff4c0dde1c7)
![Screenshot (8)](https://github.com/priyadharshini210/NearMe/assets/148514638/1e4d08b0-0073-43b8-a8d6-3aa442f4bfeb)
![Screenshot (9)](https://github.com/priyadharshini210/NearMe/assets/148514638/cbd3b47b-a6a8-488e-8402-36c4db8f592e)

## RESULT
The program for implementing image maps using HTML is executed successfully.
