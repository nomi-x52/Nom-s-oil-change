<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nom's Oil Change - Car Maintenance & Accessories</title>
  <link rel="stylesheet" href="styles.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <div class="container">
      <h1>Nom's Oil Change</h1>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#about">About Us</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="home" class="hero">
    <div class="container">
      <h2>Your Trusted Partner for Car Maintenance</h2>
      <p>We specialize in oil changes, car accessories, and premium rims.</p>
      <a href="#services" class="btn">Explore Services</a>
    </div>
  </section>

  <section id="services" class="services">
    <div class="container">
      <h2>Our Services</h2>
      <div class="service-grid">
        <div class="service-item">
          <h3>Oil Change</h3>
          <p>Fast and reliable oil change services to keep your engine running smoothly.</p>
        </div>
        <div class="service-item">
          <h3>Car Accessories</h3>
          <p>Upgrade your car with our premium accessories, including seat covers, mats, and more.</p>
        </div>
        <div class="service-item">
          <h3>Car Rims</h3>
          <p>Enhance your car's look with our stylish and durable rims.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="about" class="about">
    <div class="container">
      <h2>About Us</h2>
      <p>At Nom's Oil Change, we are passionate about cars. With years of experience, we provide top-notch maintenance services and high-quality car accessories to keep your vehicle in perfect condition.</p>
    </div>
  </section>

  <section id="contact" class="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <p>Have questions or need a service? Reach out to us!</p>
      <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 Nom's Oil Change. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
/* General Styles */
body {
  font-family: 'Roboto', sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
}

/* Header Styles */
header {
  background: #333;
  color: #fff;
  padding: 20px 0;
}

header h1 {
  margin: 0;
  font-size: 2rem;
}

nav ul {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  justify-content: flex-end;
}

nav ul li {
  margin-left: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

/* Hero Section */
.hero {
  background: url('car-hero.jpg') no-repeat center center/cover;
  color: #fff;
  padding: 100px 0;
  text-align: center;
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 30px;
}

.hero .btn {
  background: #ff6f61;
  color: #fff;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
}

/* Services Section */
.services {
  padding: 60px 0;
  background: #f4f4f4;
}

.services h2 {
  text-align: center;
  margin-bottom: 40px;
}

.service-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}

.service-item {
  background: #fff;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.service-item h3 {
  margin-bottom: 15px;
}

/* About Section */
.about {
  padding: 60px 0;
  text-align: center;
}

.about p {
  max-width: 800px;
  margin: 0 auto;
}

/* Contact Section */
.contact {
  padding: 60px 0;
  background: #333;
  color: #fff;
  text-align: center;
}

.contact form {
  max-width: 600px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
}

.contact input,
.contact textarea {
  margin-bottom: 20px;
  padding: 10px;
  border: none;
  border-radius: 5px;
}

.contact button {
  background: #ff6f61;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

/* Footer */
footer {
  background: #222;
  color: #fff;
  text-align: center;
  padding: 20px 0;
}
