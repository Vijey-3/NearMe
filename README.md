# Ex04 Places Around Me
## Date: 27.03.2024

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
### map.html
```
<html>
<head>
<title>MY CITY</title>   
</head>
<body bgcolor="#FF69B4">
<h1 align="center">
<font color="#00FFFF"><b>Krishnagiri</b></font>
</h1>
<h3 align="center">
<font color="cyan"><b>VIJEY K S (212223040239)</b></font>
</h3>
<center>
<img src="Screenshot (22).png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="POORVIKA" title="POORVIKA" href="poorvika.html" coords="10,14,264,80" shape="rect">
    <area target="" alt="APSARA THEATRE" title="APSARA THEATRE" href="apsara.html" coords="1145,273,1376,378" shape="rect">
    <area target="" alt="SHANTHI THEATRE" title="SHANTHI THEATRE" href="shanthi.html" coords="1316,550,1525,636" shape="rect">
    <area target="" alt="ROYAL ENFIELD SERVICE CENTER" title="ROYAL ENFIELD SERVICE CENTER" href="service.html" coords="1589,353,1816,454" shape="rect">
    <area target="" alt="NATHANS HOSPITAL" title="NATHANS HOSPITAL" href="hospital.html" coords="776,540,1015,627" shape="rect">
</map>
</center>
</body>
</html>
```
### poorvika.html
```
<html>
    <head>
        <title>POORVIKA</title>
    </head>
    <body bgcolor="skyblue">
        <h1 align="center">
            <font color="black"><b>KRISHNAGIRI</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>POORVIKA MOBILES</b></font>
        </h2>
        <hr size="3" color=="cyan">
        <p align="justify">
            <font face="Times New Roman" size="6" color="white">
                Poorvika Mobiles is a leading mobile shop nestled in the heart of Krishnagiri, offering an extensive range of mobile phones, accessories, and related services. Renowned for its exceptional customer service and wide selection of products, Poorvika Mobiles caters to the diverse needs and preferences of tech enthusiasts and smartphone users in the area. Whether you're looking to upgrade your current device, purchase a gift for a loved one, or explore the latest mobile trends, Poorvika Mobiles is your go-to destination in Uthangarai for all things mobile-related.
            </font>
        </p>
    </body>
</html>
```
### apsara.html
```
<html>
    <head>
        <title>APSARA THEATRE</title>
    </head>
    <body bgcolor="darkblue">
        <h1 align="center">
            <font color="lavender"><b>KRISHNAGIRI</b></font>
        </h1>
        <h2 align="center">
            <font color="plum"><b>APSARA THEATRE</b></font>
        </h2>
        <hr size="3" color=="red">
        <p align="justify">
            <font face="Times New Roman" size="6" color="white">
                "Apsara Theatre" in Krishnagiri is a vibrant cultural hub nestled in the heart of the town, renowned for its rich history and captivating performances. Built with a blend of traditional and modern architectural elements, the theatre stands as a testament to the town's dedication to the arts.
            </font>
        </p>
    </body>
</html>
```
### shanthi.html
```
<html>
    <head>
        <title>SHANTHI THEATRE</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="yellow"><b>KRISHNAGIRI</b></font>
        </h1>
        <h2 align="center">
            <font color="plum"><b>SHANTHI THEATRE</b></font>
        </h2>
        <hr size="3" color=="plum">
        <p align="justify">
            <font face="Times New Roman" size="6" color="white">
                "Shanthi Theatre" in Krishnagiri is a cultural hub and a prominent entertainment destination within the region. Nestled in the heart of Krishnagiri, this theater is renowned for its vibrant atmosphere and high-quality cinematic experience.The theater offers state-of-the-art facilities and amenities to enhance the movie-watching experience of its patrons.Shanthi Theatre boasts an impressive architectural design that combines modernity with functionality. The exterior façade is adorned with vibrant lights and signage, drawing the attention of passersby. The interior is spacious and well-designed, featuring comfortable seating arrangements and excellent sightlines from every angleSituated centrally within Krishnagiri, Shanthi Theatre enjoys excellent accessibility, making it convenient for both locals and visitors to access. Its strategic location ensures that it serves as a focal point for entertainment activities within the city.
        </p>
    </body>
</html>
```
### service.html
```
<html>
    <head>
        <title>ROYAL ENFIELD SERVICE CENTER</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="blue"><b>KRISHNAGIRI</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>ROYAL ENFIELD SERVICE CENTER</b></font>
        </h2>
        <hr size="3" color=="plum">
        <p align="justify">
            <font face="Times New Roman" size="6" color="red">
                The Royal Enfield Service Center is more than just a place where motorcycles are repaired; it's a sanctuary for enthusiasts of the iconic Royal Enfield brand.Typically situated in urban or semi-urban areas, Royal Enfield Service Centers are strategically located for easy accessibility by customers. Whether nestled within a bustling commercial district or situated on the outskirts of town, these service centers are conveniently positioned for riders seeking maintenance or repairs.Royal Enfield Service Centers boast modern facilities and infrastructure designed to cater to the needs of Royal Enfield motorcycle owners. These centers are equipped with specialized tools, diagnostic equipment, and genuine spare parts to ensure high-quality servicing and repairs.
        </p>
    </body>
</html>
```
### hospital.html
```
<html>
    <head>
        <title>NATHANS HOSPITAL</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="blue"><b>KRISHNAGIRI</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>NATHANS HOSPITAL</b></font>
        </h2>
        <hr size="3" color=="blue">
        <p align="justify">
            <font face="Times New Roman" size="6" color="black">
                Nathans Hospital is ideally located in Krishnagiri, ensuring easy accessibility for patients seeking quality healthcare services. Situated in a strategic location within the city, the hospital is easily reachable by both residents and visitors alike.Nathans Hospital prides itself on its modern infrastructure and state-of-the-art facilities. The hospital is equipped with advanced medical equipment, cutting-edge technology, and well-appointed patient rooms to ensure the highest standards of care and comfort.At Nathans Hospital, patients can expect a comprehensive range of medical services across various specialties. From general medicine and surgery to specialized fields such as cardiology, orthopedics, obstetrics, and pediatrics, the hospital caters to the diverse healthcare needs of the community.
            </font>
        </p>
    </body>
</html>
```

## OUTPUT

![Screenshot (26)](https://github.com/Vijey-3/NearMe/assets/158477768/450adfe0-df51-4c0a-9224-501d072cdbad)
![Screenshot (33)](https://github.com/Vijey-3/NearMe/assets/158477768/e83b4269-c1c9-46e4-969a-e03dbf0e0e09)
![Screenshot (31)](https://github.com/Vijey-3/NearMe/assets/158477768/4a4a471e-5aa2-403a-806b-8112c1ec4e02)
![Screenshot (30)](https://github.com/Vijey-3/NearMe/assets/158477768/85fab87a-afa8-4ce5-8a79-61e0e8e1874b)
![Screenshot (29)](https://github.com/Vijey-3/NearMe/assets/158477768/b6355f3e-140f-45ce-8cb3-a5b020fab1c9)
![Screenshot (32)](https://github.com/Vijey-3/NearMe/assets/158477768/2927c47f-ae06-432e-850f-f6e4cab7ee8f)







## RESULT
The program for implementing image maps using HTML is executed successfully.
