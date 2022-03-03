# Dummy-Hello-World

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>First Website</title>

    <!--Using font awesomeness link for making social media icon on footer------------>
    <script         src="https://kit.fontawesome.com/c8e4d183c2.js" crossorigin="anonymous"></script>
    <link href="style.css" rel="stylesheet" type="text/css"/>
  </head>

  <body>
    <script src="script.js"></script>
    <header>
      <nav> <!--HTML navigation tag--->

         <!--Font 'menu' link source from google font------------------>
         <link rel="preconnect" href="https://fonts.googleapis.com">
         <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
         <link href="https://fonts.googleapis.com/css2?family=Fredericka+the+Great&display=swap" rel="stylesheet">

       <!--Main menu------------------>

       <!--create unordered list <ul> tag for navigation menu---------------->
       <ul class="main_menu">
        <li>
          <a href="index.html">Home</a> <!--the 'href' attribute------------------->
        </li>
        <li>
          <a href="destinations.html">Destinations</a>
        </li>
        <li class="logo">
          <a href="index.html">hello world logo</a>
        </li>
        <li>
          <a href="travel.html">Travel</a>
        </li>
        <li>
          <a href="gallery.html">Gallery</a>
        </li>
       </ul>
      </nav>
    </header>

     <!--Section element for content highlights------------------->
    <section class="features">
      <figure>
        <img src="images/Cappadocia.png" alt="Turkey - Air balloon Cappadocia"> <!--the 'src' attribute----------------->
        <figcaption>Turkey</figcaption>
      </figure>   
      <figure>
        <img src="images/Borobudur.png" alt="Indonesia - Borobudur Temple">
        <figcaption>Indonesia</figcaption>
      </figure>  
      <figure>
        <img src="images/Komodo.png" alt="Indonesia - Komodo dragon">
        <figcaption>Labuan Bajo</figcaption>
      </figure>
    </section>

    <!--'About me' content----------------------------------->
    <section class="about-container">

     <!--Add image inside the container--------------------------------> 
     <img src="images/about-me.jpg" alt="about  me picture">
     <section class="about-text">
      <!--Paragraphs-------------------------->
      <p>
        Hello!
      </p>
      <p>
        I'm Fenny Wilriani, a 30-something Indonesian-born former head community of happiness and avid traveler in the midst of a never-ending love affair with solo world travel.
      </p>
      <p>
        George Bernard Shaw said, “I dislike feeling at home when I’m abroad” and I completely agree. For me, travel is about immersing ourselves in a destination and seeing as much as possible; eating local food, trying out local bars, and learning a few phrases in the local language.
      </p>
      <p>
        I travel as sustainably as possible, aiming to leave a light footprint on the ground, and a smile on the faces of people I meet.
      </p>
      <p>
        Whether you’re new to travel or a seasoned globetrotter, be sure to check out my content which is full of advice, hacks, and adventures to help and inspire your next trip.
      </p>

      <!--First paragraph font, link source from google font--------------->
      <link rel="preconnect" href="https://fonts.googleapis.com">
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
      <link href="https://fonts.googleapis.com/css2?family=Licorice&display=swap" rel="stylesheet">
      </section>
    </section>

     <!--Footer----------------->
    <footer>
      <p>
        Hello World
      </p>
      <p class="copyright">
        Copyright by Going-To Internet
      </p>

      <!--Social media link-------------->
      <div class="social-icons">
        <a href="#"><i class="fab fa-facebook"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
      </div>
    </footer> 
  </body>
</html>
