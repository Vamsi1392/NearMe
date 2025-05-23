# Ex04 Places Around Me
## Date: 23/04/2025

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
<body>
<h1 align="center">
<font color="maroon"><b>THIRUPATHI</b></font>
</h1>
<h3 align="center">
<font color="sky blue"><b>VAMSI REDDY</b></font>
</h3>
<center><img src="map.jpg" usemap="#image-map"></center>
<map name="image-map">
    <area target="" alt="Kalyani dam" title="Kalyani dam" href="Kalyani dam.html" coords="636,470,468,371" shape="rect">
    <area target="" alt="Naravaripalli waterfalls" title="Naravaripalli waterfalls" href="Naravaripalli waterfalls.html" coords="513,526,655,608" shape="rect">
    <area target="" alt="Sri venkateswara swamy temple" title="Sri venkateswara swamy temple" href="Sri venkateswara swamy temple.html" coords="844,305,650,372" shape="rect">
    <area target="" alt="Sri venkateswara zoological park" title="Sri venkateswara zoological park" href="Sri venkateswara zoological park.html" coords="753,577,920,489" shape="rect">
    <area target="" alt="ISKCON temple" title="ISKCON temple" href="ISKCON.html" coords="1077,489,925,430" shape="rect">
</map>
</body>

Kalyani dam.html

<!DOCTYPE html>
<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalyani dam</title>
  

</head>
<body bgcolor="lavender">
    <h1 style="font-family: cursive; color: rgb(3, 43, 189);">Kalyani dam</h1>
    <h2 style="font-family: serif;">The Kalyani Dam is a gravity dam constructed across the Swarnamukhi river at Tirupati city 
        and located in Tirupati District of Andhra Pradesh, India. This dam is one of the major sources of water supply for Tirupati 
        city and its catchment areas.
    </h2>
    
</body>
</html>

Sri ventakeswara swamy temple.html

<!DOCTYPE html>
<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sri venkateswara swamy temple</title>


</head>
<body bgcolor="lavender">
    <h1 style="font-family: cursive; color: rgb(3, 43, 189);">Sri venkateswara swamy temple</h1>
    <h2 style="font-family: serif;">The deity is believed to be as old as the "Shila thoranam" in Tirumala. 
        Tirumala has tremendous fame from the ancient period. The deity is referred to as 'Balaji' by North Indians. 
        The scriptures state that Venkateshwara is the saviour of all suffering people in the Kali Yuga.
    </h2>
    
</body>
</html>

Sri ventakeswara zoological park.html

<!DOCTYPE html>
<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sri venkateswara zoological park</title>
    

</head>
<body bgcolor="lavender">
    <h1 style="font-family: cursive; color: rgb(3, 43, 189);">Sri venkateswara zoological park</h1>
    <h2 style="font-family: serif;">Sri Venkateswara Zoological Park has been established on modern concepts 
        of Zoo Management where in the animals are exhibited in wider and near natural enclosures resembling to their natural habitat. 
        The Parks named after “Sri Venkateswara” the Lord of Seven Hills in Tirupati.Sri Venkateswara Zoological Park is developed on Mythological theme.
        Sri Venkateswara Zoological Park spreads over an area of 1254.71 hectares in which 289 hectares is developed so far. Presently, zoo houses 31 species 
        of mammals, 46 species of birds and 7 species of reptiles.
    </h2>
    
</body>
</html>

Naravaripalli waterfalls.html

<!DOCTYPE html>
<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Naravaripalli waterfalls</title>

</head>
<body bgcolor="lavender">
    <h1 style="font-family: cursive; color: rgb(3, 43, 189);">Naravaripalli waterfalls</h1>
    <h2 style="font-family: serif;">Naravari Palli Waterfalls, a popular tourist attraction, is located near Tirupati,
         known for its beauty and cool, refreshing ambiance. It's a relatively short distance from the road, requiring a walk through the forest. 
        One review on Google mentions the water being very cool, while another on Yappe.in notes it as a "most beautiful water falls".
    </h2>
    
</body>
</html>

ISKCON.html
<!DOCTYPE html>
<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ISKCON temple</title>


</head>
<body bgcolor="lavender">
    <h1 style="font-family: cursive; color: rgb(3, 43, 189);">ISKCON temple</h1>
    <h2 style="font-family: serif;">Its architecture and location makes it is even more attractive to the devotees. 
        The idea for this temple germinated in the year of 1974 – 1975, when his holy Srila Prabhupada visited
         Tirumala- Tirupati on the request of Andhra Pradesh Government.
    </h2>
    
</body>
</html>

```


## OUTPUT
![alt text](<Screenshot (3)-1.png>) 
![alt text](<Screenshot (4)-1.png>) 
![alt text](<Screenshot (5)-1.png>) 
![alt text](<Screenshot (6)-1.png>) 
![alt text](<Screenshot (7)-1.png>) 
![alt text](<Screenshot (8)-1.png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
