<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Creative Landing Page</title>
<style>
  /* Reset and base styles */
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    background-color: #f5f7fa;
    color: #333;
  }
  a {
    text-decoration: none;
    color: inherit;
  }
  /* Header styles */
  header {
    background-color: #344a72;
    color: #fff;
    padding: 20px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  header h1 {
    margin: 0;
    font-weight: 700;
    font-size: 1.8rem;
  }
  nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 25px;
  }
  nav li {
    font-weight: 600;
    font-size: 1rem;
  }
  nav li:hover {
    text-decoration: underline;
    cursor: pointer;
  }
  /* Hero Section */
  .hero {
    background: linear-gradient(135deg, #6a9bc9, #344a72);
    color: white;
    padding: 120px 40px 80px;
    text-align: center;
  }
  .hero h2 {
    font-size: 2.8rem;
    margin-bottom: 15px;
    font-weight: 700;
  }
  .hero p {
    max-width: 600px;
    margin: 0 auto 30px;
    font-size: 1.2rem;
    font-weight: 300;
  }
  .hero button {
    background-color: #f7b733;
    border: none;
    color: #344a72;
    font-weight: 700;
    padding: 15px 35px;
    border-radius: 30px;
    font-size: 1.1rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  .hero button:hover {
    background-color: #f3a91f;
  }
  /* Features Section - 3 columns */
  .features {
    display: flex;
    justify-content: space-around;
    padding: 60px 40px;
    background-color: #ffffff;
    gap: 30px;
    flex-wrap: wrap;
  }
  .feature {
    background-color: #e9f0f8;
    border-radius: 12px;
    flex: 1 1 280px;
    max-width: 320px;
    padding: 30px 25px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    text-align: center;
    transition: transform 0.3s ease;
  }
  .feature:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    cursor: default;
  }
  .feature h3 {
    margin-bottom: 15px;
    font-size: 1.4rem;
    color: #344a72;
  }
  .feature p {
    font-weight: 300;
    font-size: 1rem;
  }
  /* Info Section with Box Layout */
  .info-section {
    background-color: #f0f4f9;
    padding: 70px 40px;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
  }
  .info-box {
    background-color: #344a72;
    color: white;
    padding: 30px 25px;
    border-radius: 15px;
    box-shadow: 0 6px 15px rgba(52,74,114,0.2);
    transition: background-color 0.3s ease;
  }
  .info-box:hover {
    background-color: #2a3b5a;
  }
  .info-box h4 {
    margin-top: 0;
    margin-bottom: 12px;
    font-size: 1.3rem;
  }
  .info-box p {
    font-weight: 300;
    font-size: 1rem;
  }
  /* Footer */
  footer {
    background-color: #2c3e50;
    color: #bdc3c7;
    text-align: center;
    padding: 20px 40px;
    font-size: 0.9rem;
  }
  @media (max-width: 780px) {
    header {
      flex-direction: column;
      text-align: center;
    }
    nav ul {
      gap: 15px;
      margin-top: 12px;
      justify-content: center;
      flex-wrap: wrap;
    }
    .hero h2 {
      font-size: 2rem;
    }
    .hero p {
      font-size: 1rem;
    }
  }
</style>
</head>
<body>
<header>
  <h1>CreativeLanding</h1>
  <nav>
    <ul>
      <li><a href="#hero">Home</a></li>
      <li><a href="#features">Features</a></li>
      <li><a href="#info">About</a></li>
      <li><a href="#footer">Contact</a></li>
    </ul>
  </nav>
</header>

<section class="hero" id="hero">
  <h2>Welcome to Your Creative Space</h2>
  <p>Unleash your creativity with a beautifully designed landing page using simple HTML and CSS. Learn layout, colors, and alignment.</p>
  <button>Get Started</button>
</section>

<section class="features" id="features">
  <div class="feature">
    <h3>Responsive Design</h3>
    <p>Our layouts adapt to any screen size for the best user experience on desktop and mobile.</p>
  </div>
  <div class="feature">
    <h3>Easy to Customize</h3>
    <p>Change colors, fonts, and sections easily to make the page truly yours.</p>
  </div>
  <div class="feature">
    <h3>Modern Aesthetic</h3>
    <p>Clean and modern design geared towards a professional and engaging look.</p>
  </div>
</section>

<section class="info-section" id="info">
  <div class="info-box">
    <h4>Learn HTML & CSS</h4>
    <p>Master the foundation of web development by creating structured pages and stylish layouts.</p>
  </div>
  <div class="info-box">
    <h4>Boost Creativity</h4>
    <p>Experiment with colors, shapes, and compositions to find your unique style.</p>
  </div>
  <div class="info-box">
    <h4>Build Confidence</h4>
    <p>Practice makes perfect — the more you build, the more skilled and confident you become.</p>
  </div>
</section>

<footer id="footer">
  &copy; 2024 CreativeLanding. All rights reserved. | Designed for beginners.
</footer>
</body>
</html>

