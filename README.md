# Ex04 Places Around Me
## Date:29.11.24 

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
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
        <font color="red"><b>Walajapet</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>sandhiya M (24011750)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" >
            <map name="MyCity"
                    <area target="" alt="My Home Town" title="My Home Town" href="home.html" coords="810,398,1000,484" shape="rect">
                    <area target="" alt="Arignar Anna govt arts and science college" title="Arignar Anna govt arts and science college" href="College.html" coords="1490,485,1716,583" shape="rect">
                    <area target="" alt="Balaji Mahal" title="Balaji Mahal" href="Mahal.html" coords="1670,647,1815,701" shape="rect">
                    <area target="" alt="Sri kubera veera anjaneyar temple" title="Sri kubera veera anjaneyar temple" href="temple.html" coords="843,127,999,175" shape="rect">
                    <area target="" alt="Chinna lake" title="Chinna lake" href="lake.html" coords="1208,199,1351,106" shape="rect"> 
            </map>
        </center>
    </body>
</html>

college.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="yellow">
    <h1 align="center">
        <font color="red"><b>Walajapet</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Arignar Anna govt arts and science college</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Walajapet"size="5">
            Arignar Anna Government Arts college for women, walajapet is the only women government institution in pioneering higher education in Vellore District.
            Thiru. Belliappa, IAS the then collector of vellore with the help of public and academician interested in women education initiated for this institution.
            The campus is spreaded in 40 acres and the foundation stone was laid by the then education minister honourable V.R. Nedunchezhian in 20th April 1968. 
            The building was opened by the then Honourable Chief Minister M.Karunanidhi in the name of then Honourable Chief Minister Perarignar Anna. Peace, Purity and knowledge is the motto of the college.


        </font>
    </p>
</body>
</html>

home.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="black">
    <h1 align="center">
        <font color="red"><b>Walajapet</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>My Home Town</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Walajapet"size="5">
            Walajapet is a municipality and taluk of Ranipet district, in the state of Tamil Nadu.
            It was used for business purposes and one of the biggest trade centres during the time of British rule. 
            Walajapet is one of the oldest town in the North Arcot Region. It is famous for silk weaving and has a nickname, "Walajapet-The Silk City". 
            It is situated in the belt of the Ranipet SIPCOT Industrial Complex as a public limited company wholly owned by the Government.
            Walajapet is one of the noted centre for the production of silk weaving and bamboo furniture making centre. 
            The commercial activities is concentrated at Thoppai street, Annaicut Road, Bazaar street, Thirumalai Street. 
            There is a daily market available in this town.


        </font>
    </p>
</body>
</html>

lake.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="blue">
    <h1 align="center">
        <font color="red"><b>Walajapet</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Chinna lake</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Walajapet"size="5">
            The Ranipet District Collector surveyed this lake in 2019 to assess its condition and to plan rejuvenation work.
            It is located on the banks of the Palar River
            


        </font>
    </p>
</body>
</html>

mahal.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="cyan">
    <h1 align="center">
        <font color="red"><b>Walajapet</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Balaji Mahal</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Walajapet"size="5">
            Balaji Mahal specializes in hosting a variety of events, offering ample space for large gatherings as well as intimate celebrations.
            Balaji mahal has been serving the community for many years as leading Banquet halls in thangal,vellore.


        </font>
    </p>
</body>
</html>

temple.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="green">
    <h1 align="center">
        <font color="red"><b>Walajapet</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Sri kubera veera anjaneyar temple</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Walajapet"size="5">
            This temple’s history dates back many years. The place Walajapet is revered as a sacred place as sage Agasthiya, used to be Anjaneyar temple on all four directions of walajapet, in those days.
            It is noted in history that people were worshiping Anjaneya Temple, which is situated in the North direction and named Sri Kubere Veera Anjaneyar.
            North direction is believed to be the direction of kubera, the controller and distribution of wealth.


        </font>
    </p>
</body>
</html>

```


## OUTPUT
![alt text](<Screenshot 2024-12-03 144829.png>)
![alt text](<Screenshot 2024-12-03 144856.png>)
![alt text](<Screenshot 2024-12-03 144931.png>)
![alt text](<Screenshot 2024-12-03 144943.png>)
![alt text](<Screenshot 2024-12-03 144956.png>)
![alt text](<Screenshot 2024-12-06 085802.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
