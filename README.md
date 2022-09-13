# kitchenstory<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Importing Google fonts -->
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:wght@600&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Ranchers&display=swap"
      rel="stylesheet"
    />
    <!-- Linking CSS Stylesheets -->
    <link rel="stylesheet" href="./styles/menu.css" />
    <link rel="stylesheet" href="./styles/main.css" />
    <link rel="stylesheet" href="./styles/footer.css" />
    <title>The Tasty Kitchen</title>
    <!-- Importing icons -->
    <script src="https://code.iconify.design/1/1.0.6/iconify.min.js"></script>
  </head>
  <body>
    <!-- Header with logo and nav-bar menu options -->
    <header class="menu-head">
      <nav class="menuBar">
        <a href="./index.html"
          ><img
            id="logo"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTnOLuly95TkQ5Xcoh9x0B0yoSzdJKLwMbX9Q&usqp=CAU"
            alt="Logo"
        /></a>
        <ul class="menu-option">
          <a class="nav-link" href="#"><li>HOME</li></a>
          <a class="nav-link" href="#menu-section"><li>MENU</li></a>
          <a class="nav-link" href="./services.html"><li>SERVICES</li></a>
          <a class="nav-link" href="./contact.html"><li>CONTACT US</li></a>
        </ul>
      </nav>
    </header>

    <!-- Main section with content of the page -->
    <main>
      <!-- About section with title of the resturant -->
      <div class="home">
        <h1 id="head-text">Welcome To The Tasty Kitchen</h1>
        <p id="tagline">
          Laughter is brightest where food is best, we are serving it for you
        </p>
        <br />

        <article class="about">
          <p class="about-content">
            We are the non-veg specialist in the town. We are serving delicious
            food from<br />five years back. Our restuarant is famous for the
            non-veg receipes.<br />Visit our kitchen and feel the taste of our
            food.
          </p>
        </article>
      </div>
      <!-- Recipe menu with 2 recipes and show more button -->
      <div class="menu" id="menu-section">
        <h3 class="sub-title">MENU</h3>
        <section class="recipe-item">
          <div class="recipe">
            <img
              class="biriyani-pic"
              src="https://www.iff.in/sites/iff-netizen/files/home-page/banner-img/product_banner/Biryani-min.jpg"
              alt="biriyani"
              style="width: 400px; height: 300px"
            />
            <h4 class="recipe-title">Chicken Biriyani</h4>
            <p class="about-recipe">
              Biriyani every food lover likes. Here is a Biriyani recipe packed
              with goodness of<br />chicken and flavourful spices all tossed for
              a delightful dish.<br />Get you favourite Chiken Biriyani here<br />
            </p>
            <span class="price-tag">at ₹.129 Only</span>
          </div>
          <div class="recipe">
            <img
              class="tandoori-pic"
              src="https://www.whiskaffair.com/wp-content/uploads/2020/05/Tandoori-Chicken-1-3.jpg"
              alt="tandoori"
              style="width: 400px; height: 300px"
            />
            <h4 class="recipe-title">Tandoori Chicken</h4>
            <p class="about-recipe">
              Who don't loves the roasted chicken. We know you love it. Here is
              a soft,<br />succulent dry dish made by slow roasting spiced and
              marinated chicken in a clay oven<br />Eat the tandoori and take
              the flavour of it<br />
            </p>
            <span class="price-tag">at ₹.199 Only</span>
          </div>
          <div class="btn">
            <button
              class="btn-more"
              type="button"
              onclick="window.location.href='./menu.html'"
            >
              Show More
            </button>
          </div>
        </section>
      </div>

      <div class="secrvice"></div>
    </main>

    <!-- Footer with socail medial icon which dericts to social media account and 
      consist of it aslo copyright and credits section-->
    <footer>
      <div class="footer">
        <h3>FOLLOW US</h3>
        <a href="https://www.instagram.com/darshan_r_27" target="_blank">
          <abbr title="Instagram"
            ><span
              class="iconify"
              data-inline="false"
              data-icon="bx:bxl-instagram-alt"
              style="font-size: 40px; color: #3b3c46; margin-right: 10px"
            ></span>
          </abbr>
        </a>
        <a href="https://twitter.com/darshan_r_27" target="_blank">
          <abbr title="Twitter"
            ><span
              class="iconify"
              data-inline="false"
              data-icon="icomoon-free:twitter"
              style="font-size: 35px; margin-left: 10px; color: #3b3c46"
            ></span>
          </abbr>
        </a>
        <div class="credits">
          <span
            ><br />The Tasty Kitchen &copy; 2020 . Designed by
            <a href="https://www.linkedin.com/in/darshanr27">Darshan R</a></span
          >
        </div>
      </div>
    </footer>
  </body>
</html>
