# Ex04 Places Around Me
# Date:01:12:2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html
<!DOCTYPE html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>orikkai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>mahalakshmi</b></font>
</h3>
<center>
<img src="map.png" usemap="my city" height="610" width="1450"                                   
<map name="MyCity">
<area shape="rect" coords="700,250,850,400," href="home.html" title="My Home Town">
<area shape="circle"coords="570,230,45" href="temple.html" tittle="">
<area shape="circle"coords="640,200,30"href="lake.html" tittle="koladi lake">
<area shape="circle"coords="1120,360,25" href="garden.html"tittle="rmk chola garden">
<area shape="rect"coords="950,120,1100,140" href="stone.html"tittle="DR.B.R ambedkarstatue">
</map>
</center>
</body>
</html>
temple html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Manimandapam Temple — Overview</title>
  <meta name="description" content="Manimandapam Temple — history, places of interest, visiting information and image map." />
  <style>
body {
  margin: 0;
  padding: 20px;
  font-family: "Poppins", sans-serif;
  background: linear-gradient(to bottom right, #89f7fe, #66a6ff);
  color: #333;
}
header {
  text-align: center;
  padding: 25px;
  background: rgba(255, 255, 255, 0.3);
  backdrop-filter: blur(10px);
  border-radius: 15px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
}
h1 {
  color: #004aad;
  text-shadow: 2px 2px 4px rgba(255, 255, 255, 0.6);
}
.card {
  background: rgba(255, 255, 255, 0.35);
  backdrop-filter: blur(12px);
  border-radius: 20px;
  padding: 20px;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
  margin: 30px auto;
  max-width: 850px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  text-align: center;
}
.card:hover {
  transform: scale(1.02);
  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.25);
}
.card img {
  width: 60%; /* 🔹 Smaller image size */
  max-width: 350px; /* 🔹 Limit max size */
  height: auto;
  display: block;
  margin: 0 auto 15px auto;
  border-radius: 15px;
  border: 3px solid rgba(255, 255, 255, 0.6);
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
  transition: transform 0.3s ease;
}
.card img:hover {
  transform: scale(1.05);
}
.section-title {
  color: #006400;
  font-weight: bold;
  text-transform: uppercase;
  margin-top: 15px;
  position: relative;
  display: inline-block;
}
.section-title::after {
  content: '';
  position: absolute;
  bottom: -5px;
  left: 0;
  width: 70%;
  height: 3px;
  background: linear-gradient(90deg, #004aad, #00ff9c);
  border-radius: 2px;
}
 {
  color: #333;
  line-height: 1.6;
  font-weight: normal;
  background: rgba(2

  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>Manimandapam Temple</h1>
      <p class="lead">A short guide to the temple — history, important sites, and visiting information with an interactive map.</p>
    </div>
  </header>

  <div class="container">
    <main>
      <section class="card hero" aria-labelledby="overviewTitle">
        <img  src="temple.jpg" alt="Manimandapam Temple overview (satellite / drone view)" usemap="#templemap">

        <div class="info">
          <h2 id="overviewTitle" class="section-title">Temple Overview</h2>
           <h3>The **Orikkai Manimandapam**, located near Kanchipuram in Tamil Nadu, is a magnificent stone monument built in memory of **Sri Chandrasekharendra Saraswathi Swamigal**, the 68th Shankaracharya of Kanchi Kamakoti Peetam. Consecrated in **2011**, this sacred structure stands gracefully on the banks of the river Vegavathi. Entirely made of white granite, the mandapam features a towering **100-foot vimana** and a beautifully crafted **100-pillar hall**, showcasing the richness of South Indian temple architecture. The sanctum enshrines the **Padukas (holy sandals)** of Maha Periyava, symbolizing his eternal presence and blessings. The walls are adorned with intricate sculptures depicting the **Guru Parampara** and divine forms like **Lord Shiva’s Pradosha Tandavam**. Serene and spiritual, Orikkai Manimandapam is not just a memorial but a place of peace and meditation, attracting devotees seeking inspiration from the life and wisdom of the revered sage.
 </h3>
</body>
</html>
statue.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
     <meta name="description" content="Father of the Indian Constitution Dr BR Ambedkar." />
</head>
<style>
body {
  margin: 0;
  padding: 20px;
  background: linear-gradient(to bottom, #fdfbfb, #ebedee);
  font-family: "Quicksand", sans-serif;
  color: #2f4f4f;
}
header {
  text-align: center;
  background: #a8e6cf;
  color: #004d40;
  padding: 25px;
  border-radius: 15px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}
h1 {
  font-family: "Pacifico", cursive;
  letter-spacing: 1px;
}
.card {
  background-color: #ffffff;
  border: 3px solid #a8e6cf;
  border-radius: 20px;
  box-shadow: 0 8px 15px rgba(0,0,0,0.1);
  padding: 20px;
  margin: 30px auto;
  max-width: 850px;
  transition: transform 0.3s ease;
}
.card:hover {
  transform: scale(1.03);
}
.card img {
  width: 70%;
  border-radius: 20px;
  border: 2px solid #ffd3b6;
  box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}
.section-title {
  color: #004d40;
  border-bottom: 3px dotted #ffaaa5;
  display: inline-block;
  padding-bottom: 5px;
  margin-bottom: 10px;
}

</style>
<body>
<header>
    <div class="container">
    <h1>Dr BR Ambedkar</h1>
    <p class="lead">Father of the Indian Constitution Dr BR Ambedkar
    </p>
    </div>
</header>
 <div class="container">
    <main>
      
      <section class="card hero" aria-labelledby="overviewTitle">
       
        <img  src="statue .jpg" alt="statue" usemap="#statuemap"
         style="width:400px; height:250px; border-radius:15px; box-shadow:0 4px 8px rgba(0,0,0,0.3);">
        <div class="info">
          <h2 id="overviewTitle" class="section-title">
        <h3>Dr. Bhimrao Ramji Ambedkar, popularly known as Dr. B. R. Ambedkar, was a great social reformer, jurist, economist, and the chief architect of the Indian Constitution. Born on April 14, 1891, he dedicated his life to fighting against social discrimination, caste inequality, and untouchability. A strong advocate for education and equal rights, he worked tirelessly for the upliftment of the marginalized sections of society. He also played a key role in shaping India’s democracy and legal system. Dr. Ambedkar’s vision of equality, justice, and fraternity continues to inspire millions across the world.</h3>
</body>
</html>
river.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Vegavathi River Bank - Overview</title>
    <meta name="description" content="Vegavathi river - history,some intresting fatcs about the river"
</head>
    <style>
   <style>
   <style>
body {
  font-family: 'Poppins', sans-serif;
  background: #e0f7fa;
  color: #333;
  text-align: center;
  padding: 20px;
}

header {
  background: #00796b;
  color: white;
  padding: 25px;
  border-radius: 12px;
  margin-bottom: 20px;
}

h1 {
  margin: 0;
  font-size: 2em;
}

.card {
  background: #ffffff;
  border-radius: 12px;
  padding: 20px;
  margin: 0 auto 30px;
  max-width: 600px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transition: transform 0.3s;
}
.card:hover { transform: scale(1.02); }

.card img {
  width: 70%;
  max-width: 300px;
  border-radius: 12px;
  margin-bottom: 15px;
}

.section-title {
  color: #00796b;
  margin-bottom: 10px;
}

.card h3 {
  color: #2e7d32;
  line-height: 1.6;
}

.card h3 span {
  color: #43a047; /* highlight keywords */
  font-weight: 600;
}
</style>


    </style>
<body>
    <header>
    <div class="container">
    <h1>Vegavathi River Bank</h1>
    <p class="lead">Vegavathi river - history,some facts intresting facts abouts the river
    </p>
    </div>
</header>
 <div class="container">
    <main>
      <section class="card hero" aria-labelledby="overviewTitle">
        <img  src="river.jpg" alt="Vegavathiriver usemap="#rivermap"
         style="width:400px; height:250px; border-radius:15px; box-shadow:0 4px 8px rgba(0,0,0,0.3);">
        <div class="info">
          <h2 id="overviewTitle" class="section-title">River Overview</h2>
           <h3>The Vegavathi River Bank in Orikkai, near Kanchipuram, is a serene and sacred spot known for its peaceful atmosphere and spiritual charm. Flowing gently through the region, the Vegavathi River has long been associated with meditation and divine presence. It is believed that Sri Chandrasekharendra Saraswathi Swamigal (Maha Periyava) often spent time here in deep reflection and prayer, making the place highly revered among his followers. The riverbank, surrounded by lush greenery and calm breezes, offers a perfect setting for meditation, spiritual practices, and quiet contemplation. Many devotees visit this spot after offering prayers at the nearby Orikkai Manimandapam, finding solace and inspiration in the tranquil beauty of nature and the sacred vibrations of the place.</h3>
</div>
</body>
</html>
park.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Government children park - Overview</title>
    <meta name="description" content="let's known about the children park in our area"
    <style>
     <style>
body {
  background: linear-gradient(to bottom right, #d4fc79, #96e6a1);
  color: #333;
  font-family: 'Poppins', sans-serif;
}
h1 {
  color: #2e8b57;
  text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
}
.card {
  background-color: #fff;
  border-radius: 15px;
  box-shadow: 0 6px 12px rgba(0,0,0,0.1);
  padding: 20px;
  transition: transform 0.3s ease;
}
.card:hover {
  transform: scale(1.02);
}

img {
  border: 3px solid #a8e063;
  border-radius: 20px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.3);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
img:hover {
  transform: scale(1.05);
  box-shadow: 0 6px 12px rgba(0,0,0,0.4);
}
.section-title {
  position: relative;
  display: inline-block;
  padding-bottom: 5px;
}
.section-title::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  width: 60%;
  height: 3px;
  background: linear-gradient(90deg, #2e8b57, #a8e063);
  border-radius: 2px;
}

header {
  background: linear-gradient(to right, #83a4d4, #b6fbff);
  padding: 20px;
  border-radius: 15px;
  text-align: center;
  box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}
</style>

    </style>
</head>
<body>
    <header>
    <div class="container">
    <h1>Government children park</h1>
    <p class="lead">Government children park-let's known something intrest about this park
    </p>
    </div>
</header>
 <div class="container">
    <main>
      <section class="card hero" aria-labelledby="overviewTitle">
        <img  src="park.jpg" alt="children park usemap="#parkmap"
         style="width:400px; height:250px; border-radius:15px; box-shadow:0 4px 8px rgba(0,0,0,0.3);">
        <div class="info">
          <h2 id="overviewTitle" class="section-title">children park</h2>
           <h3>A Government Park is a public place maintained by the local government for recreation and relaxation. It usually features lush green lawns, walking paths, benches, flowering plants, fountains, and play areas for children. People visit the park to enjoy nature, exercise, and spend quality time with family and friends. These parks also help improve air quality and provide a peaceful environment amidst city life. Government parks play an important role in promoting health, happiness, and community well-being.</h3>
        </div>
</body>
</html>
shop.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>kanchi super market - Details</title>
<meta name="description" content="super market overview,essential things gallery"    
</head>
<style>
body {
  background: radial-gradient(circle, #141e30, #243b55);
  color: white;
  font-family: 'Trebuchet MS', sans-serif;
  text-align: center;
  padding: 30px;
}
header {
  background: rgba(255,255,255,0.1);
  border: 2px solid #00ffff;
  border-radius: 15px;
  padding: 20px;
  box-shadow: 0 0 15px #00ffff;
}
h1 {
  text-shadow: 0 0 10px #00ffff, 0 0 20px #00ffcc;
}
.card {
  background: rgba(255,255,255,0.08);
  border: 1px solid #00ffff;
  border-radius: 15px;
  padding: 20px;
  margin: 30px auto;
  max-width: 850px;
  box-shadow: 0 0 20px #00ffcc;
}
.card img {
  width: 50%;
  border-radius: 10px;
  border: 2px solid #00ffff;
  box-shadow: 0 0 10px #00ffff;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.card img:hover {
  transform: scale(1.05);
  box-shadow: 0 0 25px #00ffcc;
}
.section-title {
  color: #00ffff;
  text-transform: uppercase;
  letter-spacing: 1px;
  text-shadow: 0 0 8px #00ffcc;
  margin-bottom: 10px;
}

</style>

<body>
 <header>
    <div class="container">
    <h1>kanchi super market</h1>
    <p class="lead">famous super market must visit in Kanchipuram
    </p>
    </div>
</header>
 <div class="container">
    <main>
      <section class="card hero" aria-labelledby="overviewTitle">
        <img  src="shop.jpg" alt="supermarket" usemap="#shopmap"
         style="width:400px; height:250px; border-radius:15px; box-shadow:0 4px 8px rgba(0,0,0,0.3);">
        <div class="info">
          <h2 id="overviewTitle" class="section-title">super market Overview</h2>
           <h3>Kanchi Super Market is a popular shopping destination in Kanchipuram, known for its wide range of groceries, household items, stationery, and personal care products. Established in 2003, it has several branches across the city, making shopping convenient for locals. With clean stores, friendly service, and home delivery options, Kanchi Super Market is a one-stop destination for all daily needs in Kanchipuram.
</body>
</html>
```
# OUTPUT
<img width="1916" height="994" alt="map" src="https://github.com/user-attachments/assets/92e60de8-3f0b-4de7-9960-ae8deda595f5" />
<img width="1920" height="1080" alt="Screenshot 2025-10-01 183031" src="https://github.com/user-attachments/assets/cd601cd1-28bc-4846-97eb-29e1fc57a32c" />
<img width="1920" height="1080" alt="Screenshot 2025-10-01 183100" src="https://github.com/user-attachments/assets/beaa1af3-62b5-4af4-847c-d0dc20c55a72" />
<img width="1920" height="1080" alt="Screenshot 2025-10-01 183143" src="https://github.com/user-attachments/assets/25ab583f-c066-4ce6-93c4-7bf9c99de88d" />
<img width="1920" height="1080" alt="Screenshot 2025-10-01 183159" src="https://github.com/user-attachments/assets/892acd89-f9de-4b28-98ae-a90176be1157" />
<img width="1920" height="1080" alt="Screenshot 2025-10-01 183217" src="https://github.com/user-attachments/assets/48bf00a0-e688-436d-acc7-10e5fe5e3ac8" />
# RESULT
The program for implementing image maps using HTML is executed successfully.
