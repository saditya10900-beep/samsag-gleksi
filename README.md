
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Aditya Galaxy | Samsung Store</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background: #080811;
  color: white;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 22px 8%;
  background: #10101c;
  border-bottom: 1px solid #25253d;
}

.logo {
  font-size: 25px;
  font-weight: bold;
  color: #b69aff;
}

nav a {
  text-decoration: none;
  color: white;
  margin-left: 22px;
}

nav a:hover {
  color: #b69aff;
}

.hero {
  min-height: 85vh;
  padding: 60px 8%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 40px;
  background:
    radial-gradient(circle at 75% 45%, #35205f, transparent 45%),
    #080811;
}

.content {
  max-width: 550px;
}

.tag {
  color: #b69aff;
  letter-spacing: 4px;
  font-size: 13px;
}

h1 {
  font-size: clamp(42px, 7vw, 78px);
  margin: 22px 0;
  line-height: 1.08;
}

h1 span {
  color: #b69aff;
}

.content p {
  color: #c3c3d5;
  line-height: 1.8;
  margin-bottom: 22px;
}

.price {
  font-size: 24px;
  margin: 25px 0;
}

button {
  padding: 14px 27px;
  border: 0;
  border-radius: 30px;
  background: #b69aff;
  color: #100a20;
  font-size: 15px;
  font-weight: bold;
  cursor: pointer;
  transition: .3s;
}

button:hover {
  background: white;
  transform: translateY(-3px);
}

.hero-img {
  width: min(40%, 390px);
  min-width: 220px;
  border-radius: 20px;
  box-shadow: 0 0 55px #a17aff30;
}

.products {
  padding: 75px 8%;
  text-align: center;
}

.products h2 {
  font-size: 38px;
  margin-bottom: 40px;
}

.products h2 span {
  color: #b69aff;
}

.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 25px;
}

.card {
  padding: 25px;
  border-radius: 20px;
  background: #151522;
  border: 1px solid #292940;
  transition: .3s;
}

.card:hover {
  transform: translateY(-8px);
  border-color: #b69aff;
}

.card img {
  width: 100%;
  height: 220px;
  object-fit: contain;
  margin-bottom: 20px;
}

.card p {
  color: #aaaac0;
  margin: 15px 0;
}

.card h3 {
  font-size: 22px;
}

.about {
  padding: 70px 8%;
  text-align: center;
  background: #10101c;
}

.about h2 {
  margin-bottom: 20px;
  font-size: 34px;
}

.about p {
  color: #c3c3d5;
  line-height: 1.9;
  max-width: 700px;
  margin: auto;
}

footer {
  padding: 25px;
  text-align: center;
  color: #aaa;
  line-height: 2;
}

footer span {
  color: #b69aff;
}

@media(max-width: 750px) {
  nav {
    padding: 18px 5%;
  }

  nav a {
    margin-left: 9px;
    font-size: 12px;
  }

  .hero {
    flex-direction: column-reverse;
    text-align: center;
  }

  .hero-img {
    width: 75%;
  }

  .grid {
    grid-template-columns: 1fr;
  }
}
</style>
</head>

<body>

<nav>
  <div class="logo">GALAXY ✦</div>
  <div>
    <a href="#home">Home</a>
    <a href="#phones">Phones</a>
    <a href="#about">About</a>
  </div>
</nav>

<main>
<section class="hero" id="home">

  <div class="content">
    <div class="tag">WELCOME TO THE GALAXY</div>

    <h1>Samsung<br><span>Galaxy S24</span></h1>

    <p>
      Discover a world of innovation.
      Experience premium design, powerful performance
      and Galaxy AI features.
    </p>

    <div class="price">Explore Galaxy</div>

    <button onclick="explore('Samsung Galaxy S24 Ultra')">
      Explore Now →
    </button>
  </div>

  <img
    class="hero-img"
    src="https://placehold.co/500x650/171326/b69aff?text=Galaxy+S24+Ultra"
    alt="Samsung Galaxy S24 Ultra demo image"
  >

</section>

<section class="products" id="phones">

  <h2>Explore <span>Galaxy</span></h2>

  <div class="grid">

    <div class="card">
      <img
        src="https://placehold.co/400x300/171326/ffffff?text=Galaxy+S24"
        alt="Galaxy S24 demo image"
      >
      <h3>Galaxy S24</h3>
      <p>Smart. Stylish. Powerful.</p>
      <button onclick="explore('Galaxy S24')">
        Explore
      </button>
    </div>

    <div class="card">
      <img
        src="https://placehold.co/400x300/171326/ffffff?text=Galaxy+S24+Ultra"
        alt="Galaxy S24 Ultra demo image"
      >
      <h3>Galaxy S24 Ultra</h3>
      <p>Power meets innovation.</p>
      <button onclick="explore('Galaxy S24 Ultra')">
        Explore
      </button>
    </div>

    <div class="card">
      <img
        src="https://placehold.co/400x300/171326/ffffff?text=Galaxy+Z+Flip"
        alt="Galaxy Z Flip demo image"
      >
      <h3>Galaxy Z Flip</h3>
      <p>Unfold your possibilities.</p>
      <button onclick="explore('Galaxy Z Flip')">
        Explore
      </button>
    </div>

  </div>
</section>

<section class="about" id="about">
  <h2>About Aditya Galaxy</h2>
  <p>
    Welcome to Aditya Galaxy, a fan-made smartphone
    showcase created by Aditya Singh.
    Discover smartphone designs and explore the Galaxy lineup.
  </p>
</section>
</main>

<footer>
  <p>Made with ❤️ by <span>Aditya Singh</span></p>
  <p>Independent demo website. Not affiliated with Samsung.</p>
  <p>Product images and prices are placeholders.</p>
</footer>

<script>
function explore(phone) {
  alert(
    "Welcome to Aditya Galaxy! 🚀\n\n" +
    "Selected: " + phone +
    "\n\nThis is a demo website. Online ordering is not enabled."
  );
}
</script>

</body>
</html>
