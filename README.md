# Online-Banking-Web-Application-Project
Created using HTML, CSS and JSP(Java Servlet Pages)
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="description" content="post Banco onlinebanking">
	  <meta name="keywords" content="professional web design">onlinebanking web
  	<meta name="author" content="Brad Traversy">
    <title>Acme Web Deisgn | Welcome</title>
    <link rel="stylesheet" href="./css/style.css">
    <link rel="icon" href="img/favicon.png">
  </head>
  <body>
    <header>
      <div class="container">
        <div id="branding">
          <h1><span class="highlight">Acme</span> Web Design</h1>
        </div>
        <nav>
          <ul>
            <li class="current"><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="services.html">Services</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <section id="showcase">
      <div class="container">
        <h1>Affordable Professional Web Design</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam eu luctus ipsum, rhoncus semper magna. Nulla nec magna sit amet sem interdum condimentum.</p>
      </div>
    </section>

    <section id="newsletter">
      <div class="container">
        <h1>Subscribe To Our Newsletter</h1>
        <form>
          <input type="email" placeholder="Enter Email..." required>
          <button type="submit" class="button_1">Subscribe</button>
        </form>
      </div>
    </section>

    <section id="boxes">
      <div class="container">
        <div class="box">
          <img src="./img/logo_html.png">
          <h3>HTML5 Markup</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus mi augue, viverra sit amet ultricies</p>
        </div>
        <div class="box">
          <img src="./img/logo_css.png">
          <h3>CSS3 Styling</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus mi augue, viverra sit amet ultricies</p>
        </div>
        <div class="box">
          <img src="./img/logo_brush.png">
          <h3>Graphic Design</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus mi augue, viverra sit amet ultricies</p>
        </div>
      </div>
    </section>

    <footer>
      <p>Acme Web Deisgn, Copyright &copy; 2019</p>
    </footer>
  </body>
</html>
