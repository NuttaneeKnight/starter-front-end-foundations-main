# Navigation

Take a few moments to read through the HTML and CSS and make sure that you understand how it all works. Use VSCode Live Server to launch a local development server to serve the `index.html` file.


Single Page Navigation
<header>
  <div class="title">Your Name</div>
  <nav>
    <ul id="menu">
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#portfolio">Portfolio</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>
<main>
  <section id="home">
    <!-- All the Home section can be placed here. -->
  </section>
  <section id="about">
    <!-- All the About section can be placed here. -->
  </section>
  <section id="portfolio">
    <!-- All the Portfolio section can be placed here. -->
  </section>
  <section id="contact">
    <!-- All the Contact section can be placed here. -->
  </section>
</main>

Multi-Page Navigation
<header>
  <div class="title">Your Name</div>
  <nav>
    <ul id="menu">
      <li><a href="/">Home</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="portfolio.html">Portfolio</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>
</header>

Tip
Websites usually set the home page link to the public root ("/"). This is because index.html is the default file in that directory, so it hides the /index.html filename from displaying in the browser address.