# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
clone the github repository into Theia IDE

### Step 2:
create  a new django project

### step 3:
write the needed html code

### step 4:
run the django server and execute the html files.

## Code:

```python

map.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Tiruttani-Temple city</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Yuva krishna (22007191)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/ghs.html" title="Govt. Higher Secondary School">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/rto.html" title="RTO Office">
<area shape="circle" coords="400,350,50" href="/static/html/vk.html" title="Washerman's Lake">
<area shape="circle" coords="400,200,75" href="/static/html/bus.html" title="Hi-Tech Bus Stand">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/park.html" title="Eco-Park">
</map>
</center>
</body>
</html>

bus.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Bus Stand</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Tiruttani-temple city</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Hi-Tech Bus Stand</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
Tiruttani is a town in Tiruvallur district, suburb of Chennai within Chennai Metropolitan Area
limit in state of Tamil Nadu, India.This town is famous for Tiruttani Murugan Temple which is one of the 
Arupadaiveedu and is dedicated to(Kartikeya) Murugan.In October 2022 Tiruttani is a part of Chennai
Metropolitan Area.
Thiruthani has more to offer than just the Subramanyaswamy Temple.
The Santhana Venugopalapuram Temple is another popular shrine where devotees
and tourists numbering in thousands visit each year. The school where India’s first President,
late Dr. Sarvapalli Radha Krishnan, studied can also be viewed in Tiruttani.

Nature lovers can spend an hour or even a day on the banks of the small yet
beautiful Nandi River that flows through the town. Close by is the Kumara Teertha, 
which is also known locally as Saravana Poikai. This man-made water body at the foot of the hill, 
atop which the temple is perched, is believed to be full of holy water with therapeutic powers.
</b>
</font>
</p>
</body>
</html>

park.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Eco-Park</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Tiruttani-temple city</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Eco-Park</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
A very nice park near tirutani bus stand. It is located surrounding the temple Lake. 
Very superb calm place in ariyalur. Best for walking. Nice playing place for kids.
Well maintained with jogging track. Source of ground water.
Good place play with children.  In Banyan Tree lot of parrot stay like house. 
Good sound and Air. Lake view park looks awesome.
Very nice place at tirutani.
Simple and relax with play area.
</font>
</p>
</body>
</html>


rto.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>RTO Office</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Tiruttani-temple city</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>RTO Office</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
RTO office or the Regional Transport Office is a government body specifically established to
oversee all transport-related operations in the country. RTOs are located throughout the country in 
each state and union territory. RTOs are responsible for enforcing the rules as laid down by the Motor Vehicle Act of 1988.
The department also maintains a database of all the vehicles operating in the country as well as
issues licenses for drivers. Besides, the RTO office also collects road taxes, 
supervises pollution checks, and ensures the enforcement of all road transportation rules. 
If you own or drive a vehicle in India, you will need to visit the RTO to get your vehicle registered, obtain a 
driver’s license or renew your driver’s license, etc.RTOs are also responsible for improving road and vehicle 
safety, especially to avoid accidents and other road fatalities.
</b>
</font>
</p>
</body>
</html>

ghs.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Govt. High. Sec. School</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Tiruttani-temple city</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Government Higher Secondary School</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The main objectives of Tiruttani Government Higher Secondary School are 
<ul>
<li>To impart proper and qualified training to teachers and give them an attractive salary and incentives so that they are not tempted to quit and look elsewhere for jobs.</li>
<li>To provide financial aids and grants wisely and judiciously.</li>
<li>To Frame of syllabus and curriculum.</li>
<li>To set aims and objectives of education.</li>
</ul>
</font>
</p>
</body>
</html>

vk.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Washerman’s Lake</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>tiruttani-temple city</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Washerman's Lake</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The uses of Washerman's Lake in tiruvallur District are 
<ol type="1">
<li>Lake is used for rain water harvesting.</li>
<li>It is used for drinking.</li>
<li>Pisculture.</li>
<li>For bathing, washing clothes etc.</li>
</ol>
</font>
</p>
</body>
</html>

```

## Output:

![output](./screenshots/output1.png)

![output](./screenshots/output2.png)

![output](./screenshots/output3.png)

![output](./screenshots/output4.png)

![output](./screenshots/output5.png)

![output](./screenshots/output6.png)

## HTML VALIDATOR:

![HTML VALIDATOR](./screenshots/validation.png)

## Result:

the program fot implementing image map is executed successfully.