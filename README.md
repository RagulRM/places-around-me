# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Open up a terminal in your preffered location, and start a django project using djang-admin startproject Next setup an app inside the project folder using django-admin startapp.
### Step 2:
Once Created ,link your app to the project by adding it in the list of apps in settings.py file located inside the project folder. Add access to your host in allowed host setting and add static folders path to your settings.py file.
### Step 3:
Create a static folder and template folder and add all your required files for the project - Images .etc in your static folder. In the Template folder add your html files required for the pages.
### Step 4:
Head to the views.py in your app folder and create required functions to render a particular page or template when requested by the client. Next go to the urls.py and route the correct view functions to each particular request as needed.
### Step 5:
Next start the server from the projects main directory using python3 manage.py runserver 0:. Now the pages can be accessed from all the routed addresses in urls.py.
## Code:
### map.html
```html
<!DOCTYPE html>
<html>
    <head>
        <title>
            Image Map
        </title>
    </head>
    <body >
        <h1 align="center" >
            <font color="red" >
                    Image Map Of My Home Town
            </font>


            
        </h1>
        <h3 align="center">
        <font color="blue" face ="cursive">
            RAGUL R (212222100040)
        </font>
            
        </h3>
        <center>
            <img id="Image-Maps-Com-image-maps-2023-05-25-035604" src="../images/MAP1.png" border="0" width="1776" height="811" orgWidth="1776" orgHeight="811" usemap="#image-maps-2023-05-25-035604" alt="" />
            <map name="image-maps-2023-05-25-035604" id="ImageMapsCom-image-maps-2023-05-25-035604">
            <area  alt="" title="Temple" href="temple.html" shape="rect" coords="851,603,901,653" style="outline:none;" target="_self"     />
            <area  alt="" title="School" href="school.html" shape="rect" coords="1561,47,1611,97" style="outline:none;" target="_self"     />
            <area  alt="" title="Hotel" href="hotel.html" shape="rect" coords="606,167,656,217" style="outline:none;" target="_self"     />
            <area  alt="" title="Shop" href="shop.html" shape="rect" coords="1121,346,1171,396" style="outline:none;" target="_self"     />
            <area  alt="" title="Home" href="home.html" shape="rect" coords="272,260,305,297" style="outline:none;" target="_self"     />
            <area shape="rect" coords="1774,809,1776,811" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
            </map>



        </center>
        <p align="center">
            <font color="maroon"  face="Comic Sans MS" >
                This Image Map shows various locations around my home.<br>
                Click the location and get information about it.
            </font>
        </p>


    </body>
</html>
```
### home.html
```html
<!DOCTYPE html>
<html>
<head>
    <title>
        HOME
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        MY HOME
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is my home where I live happy with my family.<br></LI>     
            <LI>My mother and Father take cares of me and I have fun with my siblings and my pets.<br></LI>
            <LI>My pets are the loved ones because they keep me always engaging.<br></LI>
            <LI>When I feel stress, I used to visit my farms around my house and the nature and its beauty makes me to feel better.<br></LI>
        </OL>


    </font>
    <font color ="red" face = "cursive" size="16" > 
    "HOME IS WHERE OUR STORY BEGINS"
    </font>




</p>


</body>


</html>

```
### hotel.html
```html
<!DOCTYPE html>
<html>
<head>
    <title>
        Hotel
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        Hotel
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is a cafe in my neighbourhood.<br></LI>     
            <LI>I used to hangout here with my friends often.<br></LI>
            <LI>I have lot of memories there.<br></LI>
            <LI>The burger there tastes dso good that makes me visit often.<br></LI>
        </OL>


    </font>
    <font color ="red" face = "cursive" size="16" > 
    "HOTEL A PLACE I LIKE A LOT"
    </font>




</p>


</body>


</html>

```
### school.html
```html
<!DOCTYPE html>
<html>
<head>
    <title>
        SCHOOL
    </title>
</head>
<body bgcolor="Pink" >
<h1 align="center">
    <font color="blue" face="cursive">
        MY SCHOOL
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24" >
        <OL  TYPE="1" START="1">
            <LI>This is my school.<br></LI>     
            <LI>This is where i studied till tenth standard.<br></LI>
            <LI>I learnt a lot and had a lot of fun.<br></LI>
            <LI>I've got many friends there .<br></LI>
        </OL>
    </font>


    <font color ="red" face = "cursive" size="16" > 
    "SCHOOL IS PLACE WHERE WE LEARN OUR FIRST LESSONS BOTH IN ACADEMIC AND IN LIFE"
    </font>
</p>
</body>
</html>
```
### temple.html
```html
<!DOCTYPE html>
<html>
<head>
    <title>
        TEMPLE
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        TEMPLE
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <ol  TYPE="1" START="1">
            <li>This is a temple near my house<br></LI>     
            <li>We as a family use to visit there very often for every occasions and festivals<br></LI>
            <LI>It is a very famous temple in the surroundings<br></LI>
            <LI>Going to temple brings us good energy and positive vibes<br></LI>
        </ol>


    </font>
    <font color ="red" face = "cursive" size="16" > 
    "TEMPLE IS PLACE WHERE WE FIND PEACE"
    </font>
</p>
</body>
</html>

```
## Output:

## Result:
Hence a website has been developed to display details about places around my house.