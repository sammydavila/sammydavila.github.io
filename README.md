
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Scorpion Killer Coin</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="logo">
      <img src="scorpion-coin-logo.png" alt="Scorpion Killer Coin Logo">
      <h1>Scorpion Killer Coin</h1>
    </div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#community">Community</a></li>
        <li><a href="#memes">Memes</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="banner">
    <h2>The Scorpion Killer Coin - Killing Scams, One Coin at a Time!</h2>
    <p>We’re here for the community, not the profits. #ScorpionKiller #CommunityFirst</p>
    <button onclick="window.location.href='#memes'">See Memes</button>
  </section>

  <section id="about">
    <h2>About Scorpion Killer Coin</h2>
    <p>Scorpion Killer Coin is a community-driven project focused on eliminating shady crypto practices. We're here to empower our community and make crypto fun again!</p>
  </section>

  <section id="community">
    <h2>We Are Here for the Community</h2>
    <p>Join our community of crypto enthusiasts, meme creators, and meme lovers. Whether you're new to crypto or a seasoned pro, we welcome everyone to be part of this amazing journey!</p>
    <a href="https://discord.com" class="cta-button">Join Our Community</a>
  </section>

  <section id="memes">
    <h2>Scorpion Killer Memes</h2>
    <div class="meme-gallery">
      <div class="meme">
        <img src="scorpion-squash.jpg" alt="Scorpion Squash Meme">
        <p>Scorpions are dead, long live the community!</p>
      </div>
      <div class="meme">
        <img src="community-coin.jpg" alt="Community Coin Meme">
        <p>When the community fights back against scams!</p>
      </div>
    </div>

    <h3>Submit Your Meme</h3>
    <form id="meme-form">
      <input type="text" id="meme-caption" placeholder="Enter your meme caption">
      <input type="file" id="meme-image">
      <button type="submit">Submit Meme</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2024 Scorpion Killer Coin | All Rights Reserved</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
2. CSS (style.css)
This file is for styling your website to give it a fun and engaging look.

css
Copy code
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
  color: #333;
}

header {
  background-color: #333;
  color: white;
  padding: 20px;
  text-align: center;
}

header .logo img {
  max-width: 50px;
  margin-right: 10px;
}

header nav ul {
  list-style-type: none;
  padding: 0;
}

header nav ul li {
  display: inline;
  margin: 0 10px;
}

header nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.banner {
  background-color: #007bff;
  color: white;
  padding: 50px 20px;
  text-align: center;
}

.banner h2 {
  font-size: 2rem;
}

.cta-button {
  background-color: #28a745;
  color: white;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
  display: inline-block;
  margin-top: 10px;
}

section {
  padding: 20px;
  margin-bottom: 20px;
}

section h2 {
  font-size: 1.8rem;
  color: #333;
}

.meme-gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.meme {
  width: 45%;
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  padding: 10px;
}

.meme img {
  width: 100%;
  border-radius: 8px;
}

form {
  margin-top: 20px;
}

form input[type="text"] {
  width: 70%;
  padding: 10px;
  margin-right: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

form input[type="file"] {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

form button {
  background-color: #007bff;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}
