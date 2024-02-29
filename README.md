# charm-chronicles
a solution/idea that can boost the current situation of the tourism industries including hotels, travel and others.
in our website, charmchronicle, we have made this website on travel blog plateform to help people know about places and travel there. We will be working on it more, and add many feautures to it. Also, we put the link of a website from which people can book their tickets and visit places easily. Our mission is to help tourism of our country get promoted and people know abpout tourist places. 
home page:
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <link rel="stylesheet" href="website.css">
  <meta charset="UTF-8">
  <title>Travel Enthusiast Blog</title>
</head>
<body>
  <header>
    <h1>Blog Plateform For Travel Enthusiasts</h1>
    <nav>
      <ul>
        <li><a href="websitehome.html">Home</a></li>
        <li><a href="websiteabout.html">About</a></li>
        <li><a href="websiteblog.html">Blog</a></li>
        <li><a href="blogcontact.html">Contact</a></li>
        
        
      </ul>
    </nav>
  </header>
  
  <main>
    <section id="home">
      <h2>Welcome To CharmChronicle</h2>
      
    </section>
    
    <section id="blog">
      <h2>Latest Blog Posts</h2>
      <div class="blog-posts">
        <article>
          <h3>Exploring Srinagar</h3>
          
          <p> Srinagar - The Jewel of Kashmir</p>
            <p>Srinagar, the summer capital of Jammu and Kashmir, is renowned for its beautiful Dal Lake adorned with colorful Shikaras. </p>
            <P><em><a href="websiteblog.html">read</a></em>more</P>
        </article>
        <article>
          <h3>Exploring Pahalgam</h3>
          <p>Pahalgam - Tranquil and Serene</p>
          <p>Pahalgam, situated at the confluence of Lidder River and Sheshnag Lake, is a haven for nature lovers. </p>
          <p><em><a href="websiteblog.html">read</a></em>more</p>
        </article>
        <article>
          <h3>Exploring Gulmarg</h3>
          <p>Gulmarg - A Winter Wonderland</p>
           <p>Gulmarg, known for its picturesque landscapes and snow-capped peaks, is a paradise for adventure enthusiasts.</p>
           <p><em><a href="websiteblog.html">read</a></em>more</p>
            </p>
        </article>
        <article>
        <h3>Exploring Sonamarg</h3>
        <p>Sonamarg - Meadow of Gold</p>
          <p>Sonamarg, aptly named "Meadow of Gold," is adorned with vibrant flowers, lush meadows, and glaciers.</p>
          <p><em><a href="websiteblog.html">read</a></em>more</p>
          </p>
        </article>

        
      </div>
    </section>
  
        <p>You can book ticket for your favourite places on below given link</p>
      </h3>
      <P><em><a href="https://www.makemytrip.com/tripideas/places-to-visit-in-india">book</a></em>here</P>
    </section>
    <section><strong>About Us</strong></section>
    <p> For any queries, reach out to us at mirshariqshafi@gmai.com</p>
    
  </main>
  
  
  <footer>
    <p>&copy; CharmChronicle</p>
  </footer>
  <body style="background-color: lightblue;"></body>
</body>
</html>

index.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }
  
  header {
    background-color: #333;
    color: #9f0e0e;
    padding: 20px;
    text-align: center;
  }
  
  nav ul {
    list-style: none;
    padding: 0;
  }
  
  nav ul li {
    display: inline;
    margin-right: 20px;
  }
  
  nav ul li a {
    color: #fff;
    text-decoration: none;
  }
  
  main {
    padding: 20px;
  }
  
  .blog-posts {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 20px;
  }
  
  article {
    border: 1px solid #ccc;
    padding: 15px;
  }
  
  footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
  }


  about page:
  index.html
  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Blog About Section</title>
  <link rel="stylesheet" href="websiteabout.css">
</head>
<body>
  <header>
    <h1>CharmChronicle.</h1>
    <nav>
      <ul>
        <li><a href="websitehome.html">Home</a></li>
        <li><a href="websiteabout.html">About</a></li>
        <li><a href="websiteblog.html">Blog</a></li>
        <li><a href="blogcontact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="about">
      <h2>About Us</h2>
      <div class="about-content">
        
        <img src="C:\Users\mirsh\Downloads\WhatsApp Image 2023-11-30 at 11.07.26 PM.jpeg">
        <img src="C:\Users\mirsh\Downloads\WhatsApp Image 2023-11-30 at 11.03.38 PM.jpeg">
        <img src="C:\Users\mirsh\Downloads\WhatsApp Image 2023-12-01 at 12.03.27 PM.jpeg">
        <p>We welcome you to CharmChronicle. Our blog website is about travel, so if you are travel Enthusiast, we will try our best to cover all the beautiful places you can visit. We will need your support. Thankyou</p>
      </div>
    </section>
   
  </main>

  <footer>
    <p>&copy;CharmChronicle</p>
  </footer>
</body>
</html>

index.css

body, h1, h2, h3, p, ul {
    margin: 0;
    padding: 0;
  }
  

  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
  }
  
  header {
    background-color: #f2f2f2;
    padding: 20px;
    text-align: center;
  }
  
  header h1 {
    margin: 0;
    color: #333;
  }
  
  nav ul {
    list-style: none;
    margin-top: 10px;
  }
  
  nav ul li {
    display: inline;
    margin-right: 20px;
  }
  
  nav ul li a {
    text-decoration: none;
    color: #333;
  }
  
  main {
    width: 80%;
    margin: 20px auto;
  }
  
  .about {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }
  
  .about h2 {
    margin-bottom: 10px;
    color: #333;
  }
  
  .about-content {
    display: flex;
    align-items: center;
  }
  
  .about-content img {
    width: 150px;
    height: auto;
    border-radius: 100%;
    margin-right: 20px;
  }
  
  .about-content p {
    color: #555;
  }
  
  footer {
    background-color: #f2f2f2;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
  }


  blog page:
  index.html<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Blog Section</title>
  <link rel="stylesheet" href="websiteblog.css">
</head>
<body>

<header>
  
  <h1>Welcome to CharmChronicle</h1>
  <nav>
    <ul>
      <li><a href="websitehome.html">Home</a></li>
      <li><a href="websiteabout.html">About</a></li>
      <li><a href="websiteblog.html">Blog</a></li>
      <li><a href="blogcontact.html">Contact</a></li>
    </ul>
  </nav>
</header>

<main>
  <section class="blog-section">
    <article class="blog-post">
        <h1>Jammu & Kashmir</h1>
        <p class="post-metadata">Posted on November 27, 2023 by Mir Shariq Shafi</p>
        <div><img src="https://www.tripsavvy.com/thmb/-AzEW7DpVfnzFwXRy0LISt5RH8c=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/GettyImages-1432005421-5c0bc8d84cedfd0001fa5acb.jpg"</div>
        <p>Nestled in the northernmost part of India, Jammu and Kashmir, often referred to as "Paradise on Earth," is a region renowned for its breathtaking landscapes, snow-capped mountains, serene lakes, and rich cultural heritage. Let's embark on a virtual journey to explore some of the mesmerizing tourist spots in this heavenly destination:</p>
        <h3>Srinagar - The Jewel of Kashmir</h3>
        <div><img src="https://img.veenaworld.com/wp-content/uploads/2023/01/Things-To-Do-in-Srinagar.jpg"</div>
        <p>Srinagar, the summer capital of Jammu and Kashmir, is renowned for its beautiful Dal Lake adorned with colorful Shikaras, serene houseboats, and Mughal gardens such as Shalimar Bagh and Nishat Bagh. Enjoy a soothing Shikara ride while witnessing the scenic beauty that surrounds this city.</p>
        <p>Sringar finds a place on this list because it is one of the most famous tourist destinations in Jammu and Kashmir as well as the top honeymoon destination. Srinagar, often referred to as “Heaven on Earth,” is located in the union territory of Jammu & Kashmir, on the banks of the Jhelum River between the Hari Parbat and Shankaracharya hills. Srinagar is notable for its stationary houseboats and gondola-style rowboats known as Shikaras in Dal Lake. It is Jammu and Kashmir’s largest city and summer capital.
 The presence of many Mughal Gardens, religious & historical sites as well as Dal & Nigeen Lakes has led Srinagar to being called the “Land of Gardens and Lakes.” Among the other things that will surprise you, is the floating vegetable market on Dal Lake. Shikaras are used by tourists to visit sites such as the Floating Vegetable Market and the Mir Bahris, a vibrant community of people who live on the lakeside itself. Several houseboats on the lake offer a wonderful and unique stay experience. Srinagar is home to some of India’s most beautiful Mughal-era gardens, including Nishat Bagh, Shalimar Bagh, and Chashm-e-Shahi Garden. The largest Tulip gardens in Asia are also in Srinagar.</p>
        <div><img src="https://assets.cntraveller.in/photos/621361f7c78f51616154fbf8/16:9/w_1920,h_1080,c_limit/houseboats%20in%20srinagar%20lead.jpg"</div>
        <h3> Gulmarg - A Winter Wonderland</h3>
        <div><img src="https://img.veenaworld.com/wp-content/uploads/2023/09/Gulmarg-Sightseeing-Visit-The-Winter-Wonderland-of-India.jpg"</div>
        <p>Gulmarg, known for its picturesque landscapes and snow-capped peaks, is a paradise for adventure enthusiasts. Experience the thrill of skiing, snowboarding, or simply take a Gondola ride offering panoramic views of the snow-clad Himalayas.</p>
        <p> Gulmarg is located at an elevation of 2730 metres above sea level and is a notified area committee in the Indian Union territory of Jammu and Kashmir’s Baramulla district. It is 31 kilometres (19 miles) from Baramulla and 49 kilometres (30 miles) from Srinagar. Gulmarg has everything going for it: snow-dressed mountains, greenery, lakes, pine & fir forests and different types of flowers. It is snug in a valley in the Pir Panjal Range of the Western Himalayas, within the Gulmarg Wildlife Sanctuary.

          Gulmarg very well justifies its name, the meadows of flowers, and you will come across a lot of meadows decorated with daisies. A beautiful aspect of the meadow is the 1890s Anglican Church of St. Mary’s, which is situated on a lonely hill and accessible by a dead-end road connecting the 1965 neo-colonial Hotel Highlands Park and the famous Gulmarg Golf Club.
          
          Most of all though, Gulmarg has the highest green golf course in the world as well as the highest cable car project. Gulmarg has also grown as one of the best adventure destinations, with the Indian Institute of Skiing and Mountaineering based here. Hiking, mountaineering, skiing, and snowboarding courses are all available at IISM. Numerous other private tour companies in Gulmarg offer similar skiing and snowboarding courses and facilities. Gulmarg, known for its scenic splendour, has also been a favourite location for the filming of several Bollywood films.
          
          Gulmarg has a tropical climate with considerable snowfall throughout the wet winter season, which is unusual for its latitude. Summers are pleasant in temperature and length, whereas other seasons are cold.</p>
        <h3>Pahalgam - Tranquil and Serene</h3>
        <div><img src="https://media.radissonhotels.net/image/radisson-golf-resort-pahalgam/exterior/16256-126773-f72693279_3xl.jpg?impolicy=HomeHero&gravity=North"</div>
        <p>Pahalgam. Located in the Anantnag district, about 90 km away from Srinagar and it is located on the banks of the River Lidder. One of the most well-liked trekking areas is the Kolahoi Glaciers trip, which passes via the lovely settlement of Aru village, Pahalgam. Pahalgam in Kashmir Valley is a compassionate and beautiful reflection of nature. This small village is located at the intersection of two streams flowing from the beautiful Sheshnag Lake and the Lidder River and offers many breathtaking landscapes. Pahalgam is also known as the Valley of Shepherds.

          Pahalgam was the location for the classic Bollywood film Betaab, starring Sunny Deol and Amrita Singh. As a result, the valley was renamed Betaab Valley. It is a visual treat with its meadows, forests and pristine environment. Aru Valley, Betab Valley and Baisaran are some of the places which make Pahalgam the best in Kashmir for a sightseeing tour. Remember to purchase authentic Kashmiri saffron from Pampore when at Pahalgam.</p>
        <p>Pahalgam, situated at the confluence of Lidder River and Sheshnag Lake, is a haven for nature lovers. Take a stroll amidst lush green meadows, visit Betaab Valley, or embark on the Amarnath Yatra, a revered pilgrimage route.</p>
        <p>There are lot of other beautiful places in Kashmir like Sonamarg, Vaishno Devi temple, Mughal Road, Gurez valley, etc. You can visit all those places and explore the beautiful nature.</p>
    </article>

    <footer>
      <p>&copy; CharmChronicle</p>
    </footer>
    <body style="background-color: lightblue;"></body>
 
index.css



body,
h1,
h2,
h3,
p,
ul {
  margin: 0;
  padding: 0;
}


body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
}

header {
  background-color: #444;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 32px;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #fff;
}

nav ul li a:hover {
  color: #ffd700; 
}

.blog-section {
  padding: 20px;
}

.blog-post {
  margin-bottom: 30px;
}

.blog-post h1 {
  font-size: 28px;
  margin-bottom: 10px;
}

.blog-post h2 {
  font-size: 24px;
  margin-bottom: 8px;
}

.blog-post h3 {
  font-size: 20px;
  margin-bottom: 6px;
}

.blog-post p {
  margin-bottom: 15px;
}

.blog-post img {
  max-width: 100%;
  height: auto;
  display: block;
  margin-bottom: 15px;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.1); 
}

contact page
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Blog Contact Section</title>
  <link rel="stylesheet" href="blogcontact.css">
</head>
<body>

<header>
  
  <h1>Welcome to CharmChronicle</h1>
  <nav>
    <ul>
      <li><a href="websitehome.html">Home</a></li>
      <li><a href="websiteabout.html">About</a></li>
      <li><a href="websiteblog.html">Blog</a></li>
      <li><a href="blogcontact.html">Contact</a></li>
    </ul>
  </nav>
</header>

<main>
  <section class="contact-section">
    <h2>Contact Us</h2>
    <p>Feel free to reach out to us using the form below:</p>

    <form action="post" method="post">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="4" required></textarea>

      <input type="submit" value="Submit">
    </form>
  </section>
</main>

<footer>
  <p>&copy; CharmChronicle</p>
</footer>
<body style="background-color: lightblue;"></body>

</body>
</html>

index.css

body, h1, h2, p, ul {
    margin: 0;
    padding: 0;
  }
  

  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
  }
  
  header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
  }
  
  header h1 {
    margin: 0;
    font-size: 2em;
  }
  
  nav ul {
    list-style: none;
  }
  
  nav ul li {
    display: inline;
    margin-right: 20px;
  }
  
  nav ul li a {
    color: #fff;
    text-decoration: none;
  }
  
  main {
    padding: 20px;
  }
  
  .contact-section {
    background-color: #fff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  
  .contact-section h2 {
    margin-bottom: 10px;
  }
  
  .contact-section label,
  .contact-section input,
  .contact-section textarea,
  .contact-section input[type="submit"] {
    display: block;
    width: 100%;
    margin-bottom: 10px;
  }
  
  .contact-section input[type="submit"] {
    width: auto;
    cursor: pointer;
    background-color: #333;
    color: #fff;
    border: none;
    padding: 8px 20px;
    border-radius: 3px;
  }
  
  .contact-section input[type="submit"]:hover {
    background-color: #555;
  }

  
