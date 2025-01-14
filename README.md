# Ex04 Places Around Me
## Date: 19-10-2024

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
map.html
```
<html>
    <head>
        <title>
            My City
        </title>
    </head>
    <body>
        <h1 align="center">
            <font color="magenda"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>D S Mohammad Wasim</b> (212221040034)</b></font>
        </h3>
        <center>
            
<map name="MyCity">
    <area shape="rect" coords="100,100,900,900" href="expmap.html" title="My Home Town"</map>
    

    <img src="Screenshot 2024-10-19 082617.png" usemap="#image-map">

<map name="image-map">
    <map name="image-map">    
    
            <area target="_blank" alt="Kadapa Airport" title="Kadapa Airport" href="airport.html" coords="231,77,47" shape="rect">
            <area target="_blank" alt="Ameen Peer Darga" title="Ameen Peer Draga" href="darga.html" coords="720,174,71" shape="circle">
            <area target="_blank" alt="Machupalle" title="machupalle" href="machupalle.html" coords="1156,263,1284,318" shape="poly">
            <area target="_blank" alt="Viswanathapuram" title="Viswanathapuram" href="viswanathapuram.html" coords="563,547,775,619" shape="rect">    
    </map>
</map>
        </center>
    </body>

</html>
```
airport.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Kadapa Airport</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Kadapa Airport (IATA: CDP, ICAO: VOCP) is a domestic airport serving Kadapa (formerly Cuddapah) in Andhra Pradesh, India.The airport was one of the 70 airports selected under the government's UDAN scheme to increase regional air connectivity. In March 2017, TruJet reintroduced daily flights to Hyderabad in September 2017, to Mysore via Chennai in November 2017, and to Vijayawada in March 2018.[10] The airport is now connected by IndiGo with Bengaluru, Hyderabad, and Visakhapatnam.
        </font>
        </p>
    </body>
</html>
```
darga.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Ameen Peer Darga</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Ameen Peer Dargah in Cuddapah also known as Badi Peer Dargah is a century old mausoleum believed to fulfill wish of every pilgrim who visits the site.Followers of the ameenpeer  dargah believe that any wish that one makes at the shrine is always fulfilled. A large number of Hindus, Muslims and people of different faiths are disciples of the shrine. The family’s descendants identify themselves with a saffron dresss and the disciples wear a saffron cap.
        </font>
        </p>
    </body>
</html>
```
machupalle.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Machupalle</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Machupalli is a Village in Sidhout Mandal in Cuddapah District of Andhra Pradesh State, India. It belongs to Rayalaseema region.In this village there is lot of Hindu festivals doing in that one of the best festival in this village only they will make that is YELLAMMA THIRUNALA with this God we have lot of blessing getting from this God and lot of people they us to come and donate lot of money and every one pray this God.
        </font>
        </p>
    </body>
</html>
```
viswanathapuram.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Viswanathapuram</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Viswanathapuram is a small Village/hamlet in Chintakomma Dinne Mandal in Cuddapah District of Andhra Pradesh State, India. It comes under Viswanathapuram Panchayath. It belongs to Rayalaseema region . It is located 4 KM towards west from District head quarters Kadapa. 385 KM from State capital Hyderabad.It is a very good place for greenery and devotional. Which is very near to the Sri Madvirat Veera Bramendra Swamy temple
        </font>
        </p>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-10-19 082617.png>)
![alt text](<Screenshot 2024-10-19 083929.png>)
![alt text](<Screenshot 2024-10-19 084150.png>)
![alt text](<Screenshot 2024-10-19 084604.png>)
![alt text](<Screenshot 2024-10-19 090215.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
