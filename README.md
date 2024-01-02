# Places Around Me
## AIM:
To develop a website to display details about the places around my house.
## Design Steps:
### Step 1:
Fork the repository to your github and clone it into a
folder in github.

### Step 2:
Then make sure that django is activated and then start a
new django project.

### Step 3:
Now create a folder called static and within that folder
create a folder called html.

### Step 4:
Now create a file called map.html in that folder.

### Step 5:
Now open google maps and take a screenshot of your
hometown.

### Step 6:
Now open "imagemap.org" and upload your image there
and generate image maps of that using the rectangular
or circle tool.

### Step 7:
Now inside the html folder create the necessary html files
that you've included in the href of the image maps.

### Step 8:
Now push the folder and commit the changes in the
github.

### Code:
## HTML:
map.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        imagemaps demo
    </title>
</head>
<body>
    <img src="Screenshot 2023-11-20 135608.png" usemap="#image_map">
<map name="image_map">
  <area alt="JEYA CHRIS MAHAL" title="JEYA CHRIS MAHAL" href="mahal.html" coords="319,77,607,323" shape="rect">
  <area alt="Abropets" title="Abropets" href="Abropets.html" coords="1041,179,99" shape="circle">
  <area alt="HINDU COLLEGE" title="HINDU COLLEGE" href="hindu.html" coords="782,5,143" shape="circle">
  <area alt="VALLAR NAGAR" title="VALLAR NAGAR" href="vallalar.html" coords="32,5,130" shape="circle">
  <area alt="THANDURAI SCHOOL" title="THANDURAI SCHOOL" href="school.html" coords="253,392,116" shape="circle">

</map>
    
</body>
</html>
```
Abropets.html
```
<!DOCTYPE html>
<html >
<head>
    <title>ABROPETS</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;400;700&display=swap" rel="stylesheet">
    <style>
        body{
            margin: 0;
        }
        .header{
            height: 140px;
            width: 100%;
            border: none;
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            background-color: palegreen;
        }
        .header p{
            font-family: 'poppins';
            font-size: 30px;
            font-weight: 700;
        }
        .body{
            display: flex;
            justify-content: center;
            
        }
        .body img{
            margin-top: 20px;
            margin-right: 20px;
            width: 700px;
            border: 5px solid black;
        }
        .body p{
            font-size: 40px;
            text-align: start;
            justify-content: first baseline;
            align-items: baseline;
        }
    </style>
</head>
<body>
    <div class="header">
        <p>ABROPETS</p>
    </div>
    <div class="body">
        <img src="images/pets.avif">
        <p>
            Abropets Shop is a haven for pet enthusiasts seeking top-notch products and services. Located in the heart of the city, this pet emporium offers a diverse range of high-quality pet supplies, from premium pet food and grooming essentials to stylish accessories and toys. The knowledgeable and friendly staff at Abropets is dedicated to assisting customers in finding the perfect items for their furry friends. Beyond being a retail destination, Abropets also organizes community events, promoting pet health awareness and building a sense of camaraderie among local pet owners. It's more than a shop; it's a hub for the thriving pet-loving community.</p>
    </div>
    
</body>
</html>
```
hindu.html
```
<!DOCTYPE html>
<html >
<head>
    <title>HINDU COLLEGE</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;400;700&display=swap" rel="stylesheet">
    <style>
        body{
            margin: 0;
        }
        .header{
            height: 140px;
            width: 100%;
            border: none;
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            background-color: burlywood;
        }
        .header p{
            font-family: 'poppins';
            font-size: 50px;
            font-weight: 700;
        }
        .body{
            display: flex;
            justify-content: center;
            
        }
        .body img{
            margin-top: 20px;
            margin-right: 20px;
            width: 700px;
            border: 5px solid black;
        }
        .body p{
            font-size: 30px;
            text-align: start;
            justify-content: first baseline;
            align-items: baseline;
        }
    </style>
</head>
<body>
    <div class="header">
        <p>HINDU COLLEGE</p>
    </div>
    <div class="body">
        <img src="images/hindudr.avif">
        <p>As of my last knowledge update in January 2022, I don't possess specific information about a college referred to as "drbcc Hindu College." It's important to note that educational institutions often undergo changes, and details may vary based on their location and affiliation. If "drbcc" is an acronym for a specific organization or trust associated with the college, additional context could provide a clearer understanding. To acquire the most accurate and current information about drbcc Hindu College, I recommend visiting the official college website, reaching out to the college administration for inquiries, or consulting local educational directories. Exploring these sources should offer a more comprehensive overview, including details on academic programs, faculty, infrastructure, cultural activities, and any unique attributes associated with the institution.</p>
    </div>
    
</body>
</html>
```
mahal.html
```
<!DOCTYPE html>
<html >
<head>
    <title>JEYA CHRIS MAHAL</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;400;700&display=swap" rel="stylesheet">
    <style>
        body{
            margin: 0;
        }
        .header{
            height: 140px;
            width: 100%;
            border: none;
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            background-color: aqua;
        }
        .header p{
            font-family: 'poppins';
            font-size: 30px;
            font-weight: 700;
        }
        .body{
            display: flex;
            justify-content: center;
            
        }
        .body img{
            margin-top: 20px;
            margin-right: 20px;
            width: 700px;
            border: 5px solid black;
        }
        .body p{
            font-size: 25px;
            text-align: justify;
        }
    </style>
</head>
<body>
    <div class="header">
        <p>JEYA CHRIS MAHAL</p>
    </div>
    <div class="body">
        <img src="images/mahal.jpg">
        <p>Jeyaa Chris Mahal, an influential and charismatic figure, stands tall as a beacon of inspiration in the ever-changing landscape of industry and innovation. Known for a remarkable ability to foresee trends and harness the power of emerging technologies, Mahal has left an indelible mark on various sectors. With a keen eye for opportunity and an entrepreneurial spirit, Jeyaa Chris Mahal has steered enterprises toward success, demonstrating a unique blend of business acumen and creative thinking. Beyond the boardroom, Mahal's commitment to philanthropy has shaped a legacy of positive social impact. The Mahal Foundation, established under Jeyaa Chris's visionary leadership, has championed causes ranging from education to healthcare, leaving communities uplifted and empowered. As a thought leader, Mahal's speeches and writings resonate with a profound wisdom that transcends conventional boundaries, influencing not just the business realm but also the broader spheres of culture and society. The story of Jeyaa Chris Mahal unfolds as a saga of resilience, foresight, and a relentless pursuit of excellence, enriching the narrative of contemporary leadership.</p>
    </div>
    
</body>
</html>
```
school.html
```
<!DOCTYPE html>
<html >
<head>
    <title>THANDURAI ELEMENTARY SCHOOL</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;400;700&display=swap" rel="stylesheet">
    <style>
        body{
            margin: 0;
        }
        .header{
            height: 140px;
            width: 100%;
            border: none;
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            background-color: brown;
        }
        .header p{
            font-family: 'poppins';
            font-size: 30px;
            font-weight: 700;
        }
        .body{
            display: flex;
            justify-content: center;
            
        }
        .body img{
            margin-top: 20px;
            margin-right: 20px;
            width: 700px;
            border: 5px solid black;
        }
        .body p{
            font-size: 40px;
            text-align: start;
            justify-content: first baseline;
            align-items: baseline;
        }
    </style>
</head>
<body>
    <div class="header">
        <p>THANDURAI ELEMENTARY SCHOOL</p>
    </div>
    <div class="body">
        <img src="images/schoolt.avif">
        <p>Thanduai Elementary School in Pattabiram, Chennai, stands as a cornerstone of education, fostering a vibrant learning environment for students. Dedicated to academic excellence, the school, with its experienced faculty, imparts knowledge and values that extend beyond the classroom. Through a holistic approach to education, Thanduai Elementary School strives to shape well-rounded individuals, instilling a love for learning and community engagement in the young minds of Pattabiram, Chennai.</p>
    </div>
    
</body>
</html>
```
nagar.html
```
<!DOCTYPE html>
<html >
<head>
    <title>VALLALAR NAGAR</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;400;700&display=swap" rel="stylesheet">
    <style>
        body{
            margin: 0;
        }
        .header{
            height: 140px;
            width: 100%;
            border: none;
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            background-color: blueviolet;
        }
        .header p{
            font-family: 'poppins';
            font-size: 30px;
            font-weight: 700;
        }
        .body{
            display: flex;
            justify-content: center;
            
        }
        .body img{
            margin-top: 20px;
            margin-right: 20px;
            width: 700px;
            border: 5px solid black;
        }
        .body p{
            font-size: 25px;
            text-align: justify;
        }
    </style>
</head>
<body>
    <div class="header">
        <p>VALLALAR NAGAR</p>
    </div>
    <div class="body">
        <img src="images/nagar.jpg">
        <p>As of my last knowledge update in January 2022, I don't have specific information about a place named "Vallalar Nagar" that is widely recognized or known globally. It's possible that it might be a local or regional name, and information about it may not be readily available in widely accessible sources.If "Vallalar Nagar" is a specific location, it could be helpful to provide additional context or details such as the country, state, or region it is located in. This will help me provide more accurate and relevant information based on the available data.</p>
    </div>
    
</body>
</html>
```

### Output:
## Imagemap :
![map](https://github.com/jabezs2005/places-around-me/assets/147473463/f2e385f5-0297-44c0-971e-65937ccff049)

## Jeya Chris Mahal :
![mahal1](https://github.com/jabezs2005/places-around-me/assets/147473463/7417987c-e77f-496d-add2-334db783dece)

## Hindu College :
![hindu](https://github.com/jabezs2005/places-around-me/assets/147473463/afc6d883-d9c3-4bbe-8455-053bf381bc2e)

## Thandurai Elementary School :
![thandurai](https://github.com/jabezs2005/places-around-me/assets/147473463/a73d470d-2fea-49fc-85cf-6632b371d1d5)

## Abropets :
![abro](https://github.com/jabezs2005/places-around-me/assets/147473463/59916da6-a0c2-41fd-b213-b65edf84a65a)

## Vallalar Nagar :
![vallalar](https://github.com/jabezs2005/places-around-me/assets/147473463/e143ad8d-479e-4ed3-8656-6ed93ea91e48)


### Result:
Image maps have been sucessfully developed
