<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fixed Nav Menu</title>
  <style>
    /* Reset default margin */
    body, ul {
      margin: 0;
      padding: 0;
    }

    /* Fixed navigation bar */
    nav {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      background-color: #333;
      padding: 1rem;
      z-index: 1000;
    }

    /* Navigation menu list */
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }

    /* Navigation links */
    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 1.1rem;
      padding: 8px 12px;
      transition: background-color 0.3s, color 0.3s, transform 0.3s;
    }

    /* Hover effect */
    nav ul li a:hover {
      background-color: #555;
      color: #ffcc00;
      transform: scale(1.1);
      border-radius: 4px;
    }

    /* Dummy content to scroll */
    .content {
      margin-top: 80px;
      padding: 20px;
      height: 2000px;
      background: linear-gradient(#f0f0f0, #ccc);
    }
  </style>
</head>
<body>

  <!-- Fixed Navigation -->
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Services</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <!-- Content Section -->
  <div class="content">
    <h1>Welcome to the Page</h1>
    <p>Scroll down to see the fixed navigation bar stay in place.</p>
  </div>

</body>
</html>
