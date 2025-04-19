# landingpage

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Landing Page</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Welcome to My Landing Page</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Services</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Your Journey Starts Here</h2>
    <p>Build beautiful and responsive web pages with just HTML and CSS.</p>
    <a href="#" class="btn">Get Started</a>
  </section>

  <section class="features">
    <div class="feature">
      <h3>Simple</h3>
      <p>Clean and easy-to-read layout using sections and columns.</p>
    </div>
    <div class="feature">
      <h3>Responsive</h3>
      <p>Adaptable design that works across devices and screen sizes.</p>
    </div>
    <div class="feature">
      <h3>Creative</h3>
      <p>Customize the layout with colors, fonts, and spacing.</p>
    </div>
  </section>

  <footer>
    <p>©️ 2025 My Landing Page. All rights reserved.</p>
  </footer>
</body>
</html>

**css**

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  background-color: #f0f4f8;
  color: #333;
}

header {
  background-color: #1e3a8a;
  color: white;
  padding: 20px 0;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
}

.hero {
  background: #e0f2fe;
  text-align: center;
  padding: 60px 20px;
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.btn {
  padding: 10px 20px;
  background-color: #1e40af;
  color: white;
  border: none;
  text-decoration: none;
  border-radius: 5px;
}

.features {
  display: flex;
  justify-content: space-around;
  padding: 40px 20px;
  background-color: white;
}

.feature {
  flex: 1;
  margin: 0 10px;
  padding: 20px;
  background-color: #f9fafb;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  text-align: center;
}

footer {
  background-color: #1e3a8a;
  color: white;
  text-align: center;
  padding: 15px 0;
}
