# Ex04 Places Around Me
## Date:09/12/2025

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
places.html

<html>
<head>
<title>My city</title>
</head>
<body>
<h1 style ="text-align: center;">
    <b>Yelagiri</b>
</h1>
<h3 style ="text-align: center;">
<b>Thaarakeshwar</b>
</h3>
<center>
<img src="c:\Users\acer\OneDrive\Near Me\Screenshot_2025-12-10-09-10-55-458_com.google.android.apps.maps.jpg">
<map name="Mycity">
<area target="" alt="Boat House" title="Boat House" href="Boat House.html" coords="365,158,470,219" shape="rect">
<area target="" alt="Nature Park" title="Nature Park" href="Nature Park.html" coords="243,520,401,568" shape="rect">
<area target="" alt="Water Falls" title="Water Falls" href="Water Falls.html" coords="409,61,532,107" shape="rect">
</map>
</center>
</body>
</html>
```
```
Boat House.html

<html>
<head>
<title>Boat House</title>
</head>
<body bgcolor="orange">
<h1 align ="centre">
<front colour="red"><b>Boat House</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="Boat House" size="5">
The Yelagiri Boat House sits on the scenic Punganoor Lake, offering peaceful pedal and row boat rides.
Surrounded by gardens and walking paths, it’s a favorite spot for families and couples.
The calm waters and cool breeze make boating a relaxing experience.
Evenings are especially charming with sunset views reflecting on the lake.
</p>
</body>
</html>
```
```
Nature Park.html

<html>
<head>
<title>Nature Park</title>
</head>
<body bgcolor="white">
<h1 align ="centre">
<front colour="red"><b>Nature Park</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="Nature Park" size="5">
   The Yelagiri Nature Park is a lush 12-acre green space near Punganoor Lake, designed for leisure and family outings.
It features a musical fountain, an artificial waterfall, an aquarium, and a bamboo house.
Children can enjoy the dedicated play area while visitors stroll through landscaped gardens.
</p>
</body>
</html>
```

```
Water Falls.html

<html>
<head>
<title>Water Falls</title>
</head>
<body bgcolor="green">
<h1 align ="centre">
<front colour="red"><b>Water Falls</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="Water Falls" size="5">
The Jalagamparai Waterfalls near Yelagiri are a scenic natural attraction, located about 14 km from the hill station.
Formed by the Attaru River, the falls cascade down rocky terrain, creating a refreshing sight.
They are best visited after the monsoon season, when the water flow is strong and vibrant.
</p>
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot (46).png>)
![alt text](<Screenshot (47).png>)
![alt text](<Screenshot (48).png>)
![alt text](<Screenshot (49).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.