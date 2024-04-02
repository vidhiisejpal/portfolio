<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Portfolio</title>
<style>
  body, html {
    height: 100%;
    margin: 0;
    font-family: Arial, sans-serif;
  }

  .bg {
    background-color: #fff; /* White background */
    color: #000; /* Black text color */
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  .profile-img {
    border: 5px solid #000; /* Black border for the image */
    border-radius: 50%;
    padding: 5px;
    width: 200px;
    height: 200px;
    object-fit: cover;
  }

  .title {
    margin-top: 20px;
    font-size: 28px;
    font-weight: bold;
  }

  .subtitle {
    font-size: 18px;
    margin-top: 5px;
  }

  .button {
    margin-top: 20px;
    text-decoration: none;
    padding: 10px 20px;
    background-color: #007bff;
    color: white;
    border-radius: 5px;
    transition: background-color 0.3s;
  }

  .button:hover {
    background-color: #0056b3;
  }
</style>
</head>
<body>

<div class="bg">
  <img src="path_to_your_image.jpg" alt="Vidhi Sejpal" class="profile-img">
  <div class="title">Vidhi Sejpal</div>
  <div class="subtitle">Data Analyst</div>
  <div class="tagline">"POWERING MARKETING SUCCESS WITH DATA-DRIVEN INSIGHTS"</div>
  <div class="subtitle">Well versed in SQL, Python, R</div>
  <a href="path_to_your_portfolio.pdf" class="button" download>Download CV</a>
  <!-- Replace # with the actual URL to your portfolio -->
  <a href="#" class="button">Portfolio</a>
</div>

</body>
</html>
