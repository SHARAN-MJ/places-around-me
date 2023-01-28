# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
 Clone the github repository into Theia IDE.
### Step 2:
 Create a new Django project
### Step 3:
write the the needed HTML code.
### Step 4:
Run the Django server and execute the HTML files.
 
## Code:
```
mao.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Thirumullaivoyal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SHARAN (22009349)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/temple.html" title="Pachaiamman Temple">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/hos.html" title="Sir Ivan Stedeford Hospital">
<area shape="circle" coords="400,350,50" href="/static/html/ss.html" title="SS Hyderabad Biryani">
<area shape="circle" coords="400,200,75" href="/static/html/msk.html" title="MSK Diamond Mahal">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/rc.html" title="Rakki Cinemas">
</map>
</center>
</body>
</html>

temple.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Pachaiamman Temple</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Thirumullaivoyal</b></font>
</h1>
<h3 align="center">
<img src="/static/images/map.png"
usemap="Thirumullaivoyal"height="420"
width="1100"
<font color="blue"><b></b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
Pachaiamman Temple at Thirumalaivayal is located at the northeast of Arunachala hill, it has the best ambiance of all Amman temples. 
This temple is built amidst a lush forest area with many water bodies running nearby. 
This temple not only serves as a religious spot but, also a place of tranquility and serenity.
</b>
</font>
</p>
</body>
</html>

hos.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Sir Ivan Stedeford Hospital</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Thirumullaivoyal</b></font>
</h1>
<h3 align="center">
<img src="/static/images/map.png"
usemap="Thirumullaivoyal"height="420"
width="1100"
<font color="blue"><b>Sir Ivan Stedeford Hospital</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
Sir Ivan Stedeford Hospital is a multi-speciality hospital in Ambattur, Chennai, India. The hospital is named after Sir Ivan Stedeford, the British industrialist and philanthropist. The hospital was opened on 25 February 1966 and is managed by the AMM Foundation.
</font>
</p>
</body>
</html>

ss.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>SS Hyderabad Biryani</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Thirumullaivoyal</b></font>
</h1>
<h3 align="center">
<img src="/static/images/map.png"
usemap="Thirumullaivoyal"height="420"
width="1100"
<font color="blue"><b>SS Hyderabad Biryani</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
The varied menu based on Chinese and Indian cuisines is what you are offered at this restaurant. You will be able to try nicely cooked biryani here. The efficient staff welcomes visitors all year round. SS Hyderabad Biryani is remarkable for its enjoyable service. 4.1 is what this place got from the Google rating system.
</b>
</font>
</p>
</body>
</html>

msk.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>MSK Diamond Mahal</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Thirumullaivoyal</b></font>
</h1>
<h3 align="center">
<img src="/static/images/map.png"
usemap="Thirumullaivoyal"height="420"
width="1100"
<font color="blue"><b>MSK Diamond Mahal</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
 MSK Diamond Mahal is in Ambattur, Chennai. The building looks majestic and the interiors are magnificent to execute a posh wedding or any other related ceremony.The specialities are:
<ul>
<li> The wedding mahal has steps that lead to a 12,000 sq. ft hall where the lift is provided for guest's convenience. 
<li>The classy, air-conditioned hall has a huge seating capacity of 1000 and a floating capacity of 1500. Accordingly, there are extraordinary facilities for the guests such as air-conditioners, room with safety lockers, generator back up, valet parking for 100 cars, and 200 bikes.
<li> Here kitchen vessels, buffet crockery, cooking fuel are provided. The guests can serve their choice of food as nonveg cooking and service are allowed. If anyone is searching for the best interiors in Thirumullaivoyal which has colorful lights, chandeliers, manamandapam, curtains then MSK Diamond Mahal is the best and ideal venue.
</font>
</p>
</body>
</html>

rc.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Rakki Cinemas</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Thirumullaivoyal</b></font>
</h1>
<h3 align="center">
<img src="/static/images/map.png"
usemap="Thirumullaivoyal"height="420"
width="1100"
<font color="blue"><b>Rakki Cinemas</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Rakki cinemas is the best cinemas in ambathur. It has 4 screens. All the screen has Dolby atmos support. 3D movies are also played here. The ticket cost is 120 rupees. 2 screens are very big and 2 screens are average. But still u can enjoy it. It contains surround speakers which makes the movie even better to look. The bookings are open for
<ul>
<li>Varisu
<li>Thunivu 
<li>Avatar: The way of water
</ul>
</font>
</p>
</body>
</html>

## Output:

## Result:
 The program for implementing image map is executed successfully
