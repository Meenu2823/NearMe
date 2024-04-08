# Ex04 Places Around Me
## Date: 08.04.24

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
### Map.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="text-align: center; background-color: beige;">
    <h1 style="color: brown;"><b>Mugalivakkam</b></h1>
    <img src="Mugalivakkam Map.png" width="80%" height="60%" usemap="#MapNew" ><br>
    <MAP name="MapNew">
         <AREA shape="RECT" coords="895,195,1015,220" href="mkm.html" Title="MKM Matriculation School"> </AREA>
         <AREA shape="RECT" coords="430,390,540,420" href="McKingstown.html" Title="McKingstown Men's Grooming"> </AREA>
         <AREA shape="RECT" coords="1013,120,1150,165" href="acebadminton.html" Title="ACE Badminton Academy"> </AREA>
         <AREA shape="RECT" coords="210,340,315,380" href="asischool.html" Title="Anand Singapore International School"> </AREA>
         <AREA shape="RECT" coords="135,90,230,135" href="ss.html" Title="Swamy's School"> </AREA>
    </MAP>
    <h2 style="text-align: right;color: brown;">-Meenu.S(212223230124)</h2>
</body>
</html>
~~~
### mkm.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="text-align: center;background-color: darkslateblue;color: wheat;">
    <h1 style="font-family: 'Times New Roman', Times, serif;"><b>MKM HIGHER SECONDARY SCHOOL</b></h1>
    <h2 style="font-family: 'Times New Roman', Times, serif;">(Mugalivakkam,Chennai-600125)</h2>
    <p style="font-style: italic;font-size: 25px;"><b>M.K.M. Matriculation Higher Secondary School</b> is a partial realisation of the vision of <b>Shri. S. Kalyanasundaram Pillai Educational Trust</b> which is a registered body providing the best possible education for the children of all class and society.The founder trustee <b>Mr. K. Muthusamy</b> also runs a school at his native village Udayathoor in Tirunelveli district.M.K.M. Matriculation Higher Secondary School was founded in June 2003 with classes from L.K.G. to std VI. The school is affiliated under the Matriculation system, under the Board of the Matriculation Schools, Tamilnadu. The school is a co-educational institution and has been achieving excellent results year after year. It has been upgraded to Higher Secondary, catering the needs of education, knowledge and discipline of the children since 2009.Located in the beautiful residential locality of Mugalivakkam, Chennai, the school has a three- storeyed building which houses the kindergarten, primary and secondary classes. The school has a total strength of 900 students and a faculty of more than 60 teaching and 20 admin and auxiliary staff.The school is well known for its discipline, character formation and excellence in academics, sports, intra-curricular and extracurricular activities.The school is set in the path of progress and today can boast of the appreciation of not only various guests who have presided over our school celebration, but also from numerous pioneering educationists.The school aims to educate the youth to take their productive place as leaders in the global community by offering our pupils a comprehensive education from kindergarten to class 12th.</p>
</body>
</html>
~~~

## OUTPUT
![image](https://github.com/Meenu2823/NearMe/assets/139416219/0fda1acb-036a-4660-b641-44be2e64e7e9)
![image](https://github.com/Meenu2823/NearMe/assets/139416219/7ece54e7-5c91-4a53-8ead-cc1b525c770e)
![image](https://github.com/Meenu2823/NearMe/assets/139416219/07748a5a-e688-42f7-84f2-6fa07c326995)
![image](https://github.com/Meenu2823/NearMe/assets/139416219/03e57aaa-c69e-467d-9470-2d4f37e9a5cb)
![image](https://github.com/Meenu2823/NearMe/assets/139416219/aee6a837-1dac-4727-b1e1-484d067d96ce)
![image](https://github.com/Meenu2823/NearMe/assets/139416219/8b092d49-b705-42eb-9423-f490a8203f45)

## RESULT
The program for implementing image maps using HTML is executed successfully.
