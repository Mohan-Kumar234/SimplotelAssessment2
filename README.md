<!DOCTYPE html>
<html>
<head>
  <title>Navigation Bar Example</title>
  <style>
    /* Add your CSS styles here */
    body {
      margin: 0;
      padding: 0;
    }

    .nav-container {
      background-color:orangered;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px;
    }

    .nav-logo {
      height: 50px;
    }

    .nav-links {
      display: flex;
      list-style-type: none;
      padding: 0;
      margin: 0;
    }

    .nav-links li {
      margin-right: 20px;
    }

    .nav-links a {
      color: #fff;
      text-decoration: none;
      font-size: 18px;
      font-weight: bold;
      padding: 5px 10px;
      border-radius: 5px;
    }

    .nav-links a:hover {
      color: #ccc;
      background-color: #444;
    }

    .active {
      color: #ccc;
      background-color: #444;
    }

    .click-me {
      width: 150px;
      height: 50px;
      background-color: orangered;
      text-align: center;
      display: block;
      margin: 20px auto;
      border-radius: 5px;
      cursor: pointer;
    }

    .click-me img {
      width: 100%;
      height: 100%;
    }

    .stage {
      background-color: lightcoral;
      padding: 20px;
      text-align: center;
      margin: 20px auto;
      border-radius: 5px;
      width: fit-content;
    }

    .set-ademir {
      width: 150px;
      height: 50px;
      background-color: #007bff;
      text-align: center;
      display: inline-block;
      border-radius: 5px;
      cursor: pointer;
    }

    .set-ademir img {
      width: 100%;
      height: 100%;
    }
    .left {
    width: 50%;
    float: left;
    background-color: #f2f2f2;
    height: 100vh; /* Adjust as per your requirement */
  }

  /* Styles for right part */
  .right {
    width: 50%;
    float: right;
    background-color: #e0e0e0;
    height: 100vh; /* Adjust as per your requirement */
  }

  /* Media query for smaller screens */
  @media (max-width: 768px) {
    .left, .right {
      width: 100%; /* Make both divs take full width */
      float: none; /* Remove float to stack them vertically */
      height: auto; /* Reset height */
    }
  }
  /* Styles for the entire page */
  body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
  }

  /* Styles for top section */
  .top {
    width: 100%;
    height: 50vh;
    background-color: #f2f2f2;
  }

  /* Styles for bottom section */
  .bottom {
    width: 100%;
    height: 50vh;
    background-color: #e0e0e0;
  }

  /* Styles for left part */
  .left {
    width: 50%;
    height: 100%;
    float: left;
    background-color: #cccccc;
  }

  /* Styles for right part */
  .right {
    width: 50%;
    height: 100%;
    float: right;
    background-color: #aaaaaa;
  }

  /* Media query for smaller screens */
  @media (max-width: 768px) {
    .left, .right {
      width: 100%; /* Make both divs take full width */
      float: none; /* Remove float to stack them vertically */
      height: 50%; /* Adjust height for smaller screens */
    }
  }
  .h1{
    background-color: lightcoral;
  }
  .thick-black-line {
      width: 100%; /* Set the width to 100% */
      height: 10px; /* Set the height to your desired thickness */
      background-color: black; /* Set the background color to black */
    }


  </style>
</head>
<body>
  <div class="nav-container">
    <div class="nav-logo">
      
    </div>
    <ul class="nav-links">
      <li><a href="#">Home</a></li>
      <li><a href="#">Order</a></li>
      <li><a href="#">Food</a></li>
      <li><a href="#">Restaurant</a></li>
      <li><a href="#">Testimonials</a></li>
      <li><a href="#">Contact Us</a></li>
      <li><img src="C:\Users\Mohan\AppData\Local\Temp\6bc9fbc6-0ba6-476e-9ab5-832d8554df26_HTML CSS Assignment- (2) .zip.f26\HTML CSS Assignment\menu-bar.png"></li>
    </ul>
  </div>
  <div class="top">
    <div class="left">
      <h2 color="black"> LOREM IPSUM</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus
        id est vitae dolor rhoncus tristique. Maecenas metus quam,
        rhoncus euismod lorem in, sollicitudin viverra eros. Donec
        dictum luctus quam ut tristique. Curabitur nec faucibus purus.
        Quisque congue sem nec justo mollis, in tincidunt erat pretium.
        Sed pulvinar, massa ac porta viverra.</p>
        <button color:'oranged'>Click Me</button>
    </div>
    <div class="right">
      <img src="https://th.bing.com/th/id/OIP.CE-u1p6IkSBatXUQ2zX2FAHaE7?rs=1&pid=ImgDetMain">
    </div>
  </div>
  <div class="thick-black-line"></div>
  <div class="bottom">
    <div class="left">
      <img src="file:///C:/Users/Mohan/AppData/Local/Temp/cbb0e911-9673-427e-9992-2ae9ad2d2900_HTML%20CSS%20Assignment-%20(2)%20.zip.900/HTML%20CSS%20Assignment/pexels-rachel-claire-6752433.jpg">
    </div>
    <div class="right">
      <div class="center">
        <h1> LOREM IPSUM
          SET ADEMIR</h1>
      </div>
    </div>
  </div>
</style>
</head>
</body>
</html>
