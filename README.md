# Tech-Genius
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tech~Genius</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f0f0f;
      color: #fff;
    }
    header {
      background: #000;
      padding: 20px;
      text-align: center;
      font-size: 28px;
      font-weight: bold;
      color: gold;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background: #111;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(black, #222);
    }
    .slider {
      width: 80%;
      margin: 40px auto;
      overflow: hidden;
      border-radius: 10px;
    }
    .slides {
      display: flex;
      animation: slide 12s infinite;
    }
    .slides img {
      width: 100%;
    }
    @keyframes slide {
      0% { transform: translateX(0); }
      25% { transform: translateX(-100%); }
      50% { transform: translateX(-200%); }
      75% { transform: translateX(-100%); }
      100% { transform: translateX(0); }
    }
    .section {
      padding: 40px;
      text-align: center;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .card {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
    }
    footer {
</html>
