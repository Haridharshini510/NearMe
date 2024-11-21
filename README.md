# Ex04 Places Around Me
## Date: 

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
mapmap.html

<html>
    <style>
        body{
            background-color:#9855aa;
        }
        img{
            width: 1000px; 
            display: flex;
            align-items: center;
            
        }
        .imgDiv{
            display: flex;
  justify-content: center;
  align-items: center;
        }
        .title{
            display: flex;
  justify-content: center;
  align-items: center;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-variant: small-caps;
  font-size: 20px;
        }
        .subtitle{
            display: flex;
  justify-content: center;
  align-items: center;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-weight: 700;

        }
    </style>
    <body>
        <div class="title">
            <h1>Chennai city</h1>
        </div>
        <div class="subtitle">
            <h3>Haridharshini J(24900163)</h3>
        </div>
        <hr>
        <section class="imgDiv">
            <img src="web.png" usemap="#image-map">
        </section>

        <map name="image-map">
            <area target="_blank" alt="Adyar" title="Adyar" href="adyar.html" coords="665,325,35" shape="circle">
            <area target="_blank" alt="Guindy" title="Guindy" href="guindy.html" coords="595,312,35" shape="circle">
            <area target="_blank" alt="Velachery" title="Velachery" href="velachery.html" coords="598,381,43" shape="circle">
            <area target="_blank" alt="Tnagar" title="Tnagar" href="tnagar.html" coords="632,246,44" shape="circle">
            <area target="_blank" alt="Annanagar" title="Annanagar" href="annanagar.html" coords="582,172,38" shape="circle">
        </map>
    </body>
</html>

velachery.html

<html>
    <style>
        body{
            background-color:orchid;
        }
        p{
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: 20px;
            font-weight: 700;
        }
        h1{
            display: flex;
  justify-content: center;
  align-items: center;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-variant: small-caps;
  font-size: 40px;
        }
        h3{
            display: flex;
  justify-content: center;
  align-items: center;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-weight: 700;
        }
    </style>
    <body>
        <h1>Chennai City</h1>
        <h3>Velachery</h3>
        <hr>
        <p>Velachery is an established residential locality situated in South Chennai and surrounded by prominent areas such as Guindy, Perungudi, Taramani, Madipakkam and Nanganallur.<br>
         The locality is dominated by independent residential houses and low-rise apartment projects.<br>
         Presence of civic amenities, proximity to significant IT hubs and excellent connectivity are the main factors driving residential demand here.</p>
        </p>
    </body>
</html>

annanagar.html

<html>
    <style>
        body{
            background-color:cornflowerblue;
        }
        p{
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: 20px;
            font-weight: 700;
        }
        h1{
            display: flex;
  justify-content: center;
  align-items: center;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-variant: small-caps;
  font-size: 40px;
        }
        h3{
            display: flex;
  justify-content: center;
  align-items: center;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-weight: 800;

        }
    </style>
    <body>
        <h1>Chennai City</h1>
        <h3>Annanagar</h3>
        <hr>
        <p> Anna Nagar is one of the most expensive, premium and well-planned residential locality comprising excellent social infrastructure and a sound arrangement of internal roads.<br>
             Anna Nagar is known for bungalows, independent residential houses and apartments.<br>
              It is surrounded by established locales of Villivakkam, Ayanavaram, Kilpauk, Arumbakkam and Koyambedu</p>
        </p>
    </body>
</html>

tnagar.html

<html>
    <style>
        body{
            background-color:rgb(144, 189, 216);
        }
        p{
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: 20px;
            font-weight: 700;

        }
        h1{
            display: flex;
  justify-content: center;
  align-items: center;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-variant: small-caps;
  font-size: 40px;
        }
        h3{
            display: flex;
  justify-content: center;
  align-items: center;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-weight: 700;

        }
    </style>
    <body>
        <h1>Chennai City</h1>
        <h3>TNagar</h3>
        <hr>
        <p>T Nagar is short for Thyagaraya Nagar, which is a premium commercial and residential locality of Chennai.<br>
         It is one of the most planned and well-established localities of Chennai. <br>
         The area of T Nagar is famous for retail outlets offering a variety of merchandise. <br>
         The Chennai International airport is just 13 KM away from T Nagar.</p>
        </p>
    </body>
</html>

adyar.html

<html>
    <style>
        body{
            background-color: pink;
        }
        p{
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: 20px;
            font-weight: 700;

        }
        h1{
            display: flex;
  justify-content: center;
  align-items: center;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-variant: small-caps;
  font-size: 40px;
        }
        h3{
            display: flex;
  justify-content: center;
  align-items: center;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-weight: 700;

        }
    </style>
    <body>
        <h1>
            Chennai city
        </h1>
        <h3>Adyar</h3>
        <hr>
        <p>
        Adyar is a neighbourhood located in southern Chennai.<br>
        The name of this locality comes from the Adyar river, flowing to its estuary through the broken bridge in the east.<br>
        The locality is strategically located to be in proximity to major employment hubs in the city.
        </p>
    </body>
</html>

guindy.html

<html>
    <style>
        body{
            background-color:coral;
        }
        p{
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: 20px;
            font-weight: 700;

        }
        h1{
            display: flex;
  justify-content: center;
  align-items: center;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-variant: small-caps;     
  font-size: 40px;
        }
        h3{
            display: flex;
  justify-content: center;
  align-items: center;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-weight: 700;

        }
    </style>
    <body>
        <h1>Chennai City</h1>
        <h3>Guindy</h3>
        <hr>
        <p>Guindy is a luxury locality situated in the southern part of Chennai. <br>The pincode of this locality is 600032.<br>
         This locality is near SIDCO Industrial Estate, Guindy, Race View Colony and Guindy Institutional Area. </p>
        </p>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (11).png>)
![alt text](<Screenshot (12).png>)
![alt text](<Screenshot (13).png>)
![alt text](<Screenshot (14).png>)
![alt text](<Screenshot (15).png>)
![alt text](<Screenshot (16).png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
