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
</head>
<body style="text-align: center;background-color: darkslateblue;color: wheat;">
    <h1 style="font-family: 'Times New Roman', Times, serif;"><b>MKM HIGHER SECONDARY SCHOOL</b></h1>
    <h2 style="font-family: 'Times New Roman', Times, serif;">(Mugalivakkam,Chennai-600125)</h2>
    <p style="font-style: italic;font-size: 25px;"><b>M.K.M. Matriculation Higher Secondary School</b> is a partial realisation of the vision of
 <b>Shri. S. Kalyanasundaram Pillai Educational Trust</b> which is a registered body providing the best possible education for the children of
all class and society.The founder trustee <b>Mr. K. Muthusamy</b> also runs a school at his native village Udayathoor in Tirunelveli district.
M.K.M. Matriculation Higher Secondary School was founded in June 2003 with classes from L.K.G. to std VI. The school is affiliated under the
Matriculation system, under the Board of the Matriculation Schools, Tamilnadu. The school is a co-educational institution and has been achieving
excellent results year after year. It has been upgraded to Higher Secondary, catering the needs of education, knowledge and discipline of the
children since 2009.Located in the beautiful residential locality of Mugalivakkam, Chennai, the school has a three- storeyed building which houses
 the kindergarten, primary and secondary classes. The school has a total strength of 900 students and a faculty of more than 60 teaching and 20
admin and auxiliary staff.The school is well known for its discipline, character formation and excellence in academics, sports, intra-curricular
and extracurricular activities.The school is set in the path of progress and today can boast of the appreciation of not only various guests who
have presided over our school celebration, but also from numerous pioneering educationists.The school aims to educate the youth to take their
productive place as leaders in the global community by offering our pupils a comprehensive education from kindergarten to class 12th.</p>
</body>
</html>
~~~
### acebadminton.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="text-align: center; background-color: blanchedalmond;">
    <h1 style="font-family: 'Times New Roman', Times, serif; color: darkgoldenrod;"><b>ACE BADMINTON ACADEMY</b></h1>
    <h2 style="font-family: 'Times New Roman', Times, serif;color: darkgoldenrod; ">(Mugalivakkam,Chennai)</h2>
    <p style="font-style: italic;color: darkgreen;font-size: 25px;">At ACE BADMINTON ACADEMY, their vision is to provide an education which
nurtures intellectual curiosity and which is challenging and fun, balancing academic excellence with fulfilment of individual potential in
the arts and sports. Create a badminton community that is friendly, supportive, encouraging and competitive.No matter what their age or
background, will have an opportunity to reach their potential.</p>
    <p style="font-style: italic;color: darkgreen;font-size: 25px;">They are committed to providing exceptional coaching and ensuring that
every players is satisfied with their game. Their team is always available to answer any questions you may have and help you find the
perfect gear for your needs.They offer monthly membership and hourly slot bookings. With flexible timings. Kids coaching available by former 
TN State veterans Champion Mr. Francis Thomas </p>
</body>
</html>
~~~
### McKingstown.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
</head>
<body style="text-align: center;background-color: black;color: gold">
    <h1 style="font-family: 'Times New Roman', Times, serif;"><b>McKingstown</b></h1>
    <h2 style="font-family: 'Times New Roman', Times, serif;">(Men's Grooming at Madhanandhapuram)</h2>
    <p style="font-style: italic;color: silver;font-size: 25px;">McKingstown Men's Grooming appears to be a brand catering to men's grooming
needs, offering products and potentially barber services.Their lineup likely includes essentials like shaving cream and razors, as well as
specialized items such as beard oils and skincare products.Emphasizing quality ingredients and keeping up with trends like beard grooming,
they may target a modern, discerning clientele. With an online presence, they likely engage customers through e-commerce platforms and social
media. Exploring customer reviews and their product range can offer insights into their reputation and unique offerings within the
competitive men's grooming market.</p>
</body>
</html>
~~~
### asischool.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
</head>
<body style="text-align: center;background-color: lightseagreen;color: rgb(0, 88, 139);">
    <h1 style="font-family: 'Times New Roman', Times, serif;"><b>ANAND SINGAPORE INTERNATIONAL SCHOOL(ASIS)</b></h1>
    <h2 style="font-family: 'Times New Roman', Times, serif;">(Mugalivakkam,Chennai-600125)</h2>
    <p style="font-style: italic;font-size: 25px;color: darkblue;">The Anand International School in Chennai (ASIS) is one of the best
international schools in Chennai, which is formed from a partnership between one of Singapore's leading education groups, SIS Group of
Schools, and the highly respected Kalasalingam and Anandam Ammal Charities.The SIS Group of Schools  is a premier chain of K-12
(Pre-school to Grade 12) private international schools. Its mission is to bring the world’s best education system from Singapore to
cities across the world.SIS was established in 1996, with the impetus provided by the then Ministers from the Singapore government as
well as assistance from Singapore's premier school Raffles Institution. SIS is in a strategic partnership with the International
Finance Corporation, IFC (World Bank) and has premier schools in Indonesia, Korea, Myanmar and now India. It is looking to expand into
other cities.SIS students constantly perform well on the world stage. They have moved on to top universities in the world including the
National University of Singapore, Oxford University, and Imperial College, London. Their participation in debates in Model United Nation
conferences, in community work, in entrepreneurial projects, in sports and the performing arts has shown that SIS students are among the
best out there.SIS is an award-winning school group, being named in 2019 by the Financial Times and the International Finance Corporation
(World Bank) as a leader in education for its transformational work. The SIS Group is constantly invited to world conferences from Cape
Town to San Francisco to share its success story for other schools to emulate.In India, SIS seeks to expand its presence through its
investment and management arm, Cambrian. Cambrian’s main philosophy is to educate young people holistically by attending to their
physical and intellectual growth and by incorporating international and Indian teaching and learning methodologies balanced with Indian
and inter-cultural values.
</body>
</html>
~~~
### ss.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="text-align: center; background-color: rgb(64, 29, 14)">
    <h1 style="font-family: 'Times New Roman', Times, serif; color: lightcoral"><b>SWAMY'S SCHOOL</b></h1>
    <h2 style="font-family: 'Times New Roman', Times, serif;color: lightcoral;">(Porur,Chennai)</h2>
    <p style="font-style: italic;color: darkgoldenrod;font-size: 25px;">Swamy's School was founded in 1995 and has successfully
established itself as a premier educational institution in Chennai.The school is dedicated to nurturing the moral, spiritual,
and ethical growth of our students.As a CBSE-affiliated institution, they offer a diverse and flexible approach to education.
Their teaching methods go beyond the conventional. They prioritize individual attention and foster teamwork and leadership
through group activities.We believe in making learning enjoyable, helping students discover their passions, and empowering
them to pursue their dreams.</p>
    <p style="font-style: italic;color: darkgoldenrod;font-size: 25px;">The inception of the School was in the year 1995,
when Porur was a suburb. The school was started with classes LKG to V and it was named "Gitanjali". The building was
inaugurated by Shri. Cho. Ramaswamy and Father Lawrence Sundaram of Loyola College
    </p>
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
