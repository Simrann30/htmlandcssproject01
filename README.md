# htmlandcssproject01
This is restaurant website 


![white-logo](https://user-images.githubusercontent.com/122850285/216804386-d3ccd1ce-c29a-4f2b-819b-1eefcbf93973.png)




<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />

    <!-- Red Rose Font -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Red+Rose:wght@300;400;500;600;700&display=swap"
      rel="stylesheet"
    />
    <!-- Dela Font -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Dela+Gothic+One&display=swap"
      rel="stylesheet"
    />
    <title>Document</title>
  </head>
  <body>
    <div class="container">
      <section aria-label="navbar">
        <nav class="navbar">
          <div>
            <img src="white-logo.png" alt="logo" class="logo" />
          </div>
          <div>
            <ul class="list">
              <li class="list-item">Our Menu</li>
              <li class="list-item">Maps</li>
              <li class="list-item">About</li>
              <li class="list-item">Contact</li>
            </ul>
          </div>
          <div>
            <button class="button-small">Order</button>
          </div>
        </nav>
      </section>
      <!-- Hero Section -->
      <section aria-label="hero">
        <div class="hero">
          <h1 class="hero-heading">
            A Restaurant That Only Serves Delicious Food
          </h1>
          <button class="button-large">Read Our Menu</button>
          <div class="bottom">
            <div>
              <img src="scrool.png" alt="bottom-logo" />
            </div>
          </div>
        </div>
      </section>
    </div>
  </body>
</html>


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Red Rose", cursive;
}

body {
  width: 100%;
  height: 100%;
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url("restaurant.png");
  background-size: cover;
  background-attachment: fixed;
}

/* ------------------------------ */
/* ---------- NAVBAR ------------ */
/* ------------------------------ */

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 60px 0 60px;
  margin-top: 55px;
}

.list {
  display: flex;
  align-items: center;
  gap: 63px;
  list-style: none;
  font-family: "Red Rose";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 22px;
  color: #ffc233;
}

.logo,
.list-item {
  cursor: pointer;
}

.button-small {
  padding: 12px 40px;
  background-color: #ff505f;
  border: none;
  font-family: "Red Rose";
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 30px;
  color: #ffffff;
  cursor: pointer;
}

/* ------------------------------ */
/* ---------- HERO ------------ */
/* ------------------------------ */

.hero {
  max-width: 1154px;
  margin: 0 auto;
  text-align: center;
  margin-top: 119px;
}

.hero-heading {
  font-family: "Dela Gothic One", cursive;
  font-style: normal;
  font-weight: 400;
  font-size: 104px;
  line-height: 114px;
  /* or 110% */
  color: #ffc233;
}

.button-large {
  background: #ff505f;
  font-family: "Red Rose";
  font-style: normal;
  font-weight: 700;
  font-size: 32px;
  line-height: 40px;
  color: #ffffff;
  border: none;
  padding: 24px 56px;
  margin-top: 64px;
  cursor: pointer;
}

.bottom {
  position: absolute;
  bottom: 20px;
  right: 40px;
}
![white-logo](https://user-images.githubusercontent.com/122850285/216804402-223347cb-4f18-4533-8818-6142bcda6aac.png)
![scrool](https://user-images.githubusercontent.com/122850285/216804403-2aa5d81f-290f-42f3-87b2-b39e65f4d526.png)
![restaurant](https://user-images.githubusercontent.com/122850285/216804404-c4ad0db9-f3e7-4765-bd33-64718ccb6257.png)

   
   


