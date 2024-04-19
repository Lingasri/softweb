# Ex.07 Software Product Company Website
## Date: 19/04/2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
### softwebcompany:
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SOFTWEB Company - Software Product Development Experts</title>
  <style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  color: #333;
}

header {
  background-color: #222;
  color: #fff;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
header .logo a {
  display: inline-block;
  font-size: 24px;
  font-weight: bold;
  color: #fff;
  text-decoration: none;
}
header nav ul {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
}
header nav li {
  margin-right: 20px;
}
header nav li a {
  color: #fff;
  text-decoration: none;
  font-size: 16px;
  padding: 10px;
  display: inline-block;
}
.hero-banner {
  background-image: url("leone-venter-VieM9BdZKFo-unsplash.jpg");
  background-size: cover;
  background-position: center;
  height: 500px;
  color: #000000;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.hero-banner .content {
  padding: 20px;
  text-align: center;
}
.hero-banner .content h1 {
  font-size: 36px;
  font-weight: bold;
  margin-bottom: 20px;
}
.hero-banner .content p {
  font-size: 18px;
  line-height: 1.5;
  margin-bottom: 20px;
}
.hero-banner .content a.button {
  background-color: #007bff;
  color: #000000;
  padding: 10px 20px;
  border-radius: 5px;
  font-size: 16px;
  text-decoration: none;
}
section {
  padding: 20px;
}
section h2 {
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 20px;
}
.services-container {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
footer {
      background-color: #f1f1f1;
      padding: 20px 0;
      text-align: center;
    }
    footer a {
      color: #333;
      text-decoration: none;
      margin: 0 5px;
    }
    footer a:hover {
      color: #007bff;
    }
    footer .social-icons {
      display: flex;
      justify-content: center;
      margin-top: 10px;
    }
    footer .social-icons img {
      width: 25px;
      height: 25px;
      margin: 0 5px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <a href="#">
        <b>CODAX</b>
      </a>
    </div>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="Services.html">Services</a></li>
        <li><a href="Products.html">Products</a></li>
        <li><a href="About.html">About Us</a></li>
        <li><a href="Contact.html">Contact</a></li>
        <li><a href="login.html">Login</a></li>
      </ul>
    </nav>
  </header>

  <div class="hero-banner">
    <div class="content">
      <h1>Unlock the Power of Software</h1>
      <p align="center"><b>
        We are CODAX, a passionate team of software experts dedicated to
        building innovative and impactful solutions for businesses like yours.<br>
        We don't build cookie-cutter software. We listen to your unique needs and design solutions that fit your business like a glove.<br>
        We push the boundaries of technology, leveraging cutting-edge tools and frameworks to deliver future-proof solutions.<br>
        We work in close partnership with you, ensuring transparency and seamless collaboration throughout the development process.<br>
        We don't just build software; we deliver measurable outcomes that drive your business growth.
      </b>
      </p>
      <br>
      <br>
      <a href="#contact" class="button">Get a Free Consultation</a>
    </div>
  </div>
  <footer>
    <p>&copy; 2023 <a href="#">CODAX</a> All rights reserved.</p>
    <p><b>Designed and Developed by Gokkul (23014201)</b></p>
    <section id="contact">
        <a href="Contact.html"><h2>Contact us</h2></a> 
        <a href="login.html"><h2>Login</h2></a> 
  </section>
    <p>
      <a href="#">Privacy Policy</a> |
      <a href="#">Terms of Service</a>
    </p>
    <div class="social-icons">
      <a href="#"><img src="download.png" alt="Facebook"></a>      
        <a href="#"><img src="download (1).png" alt="Twitter"></a>     
        <a href="#"><img src="download (2).png" alt="LinkedIn"></a>
    </div>
  </footer>
</body>
</html>
        
### service:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Software Company Services</title>
  <style>
body {
    font-family: sans-serif;
    margin: 0;
}
header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}
.services {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 20px;
}
.service-card {
    width: 300px;
    margin: 10px;
    background-color: #f1f1f1;
    border-radius: 5px;
    padding: 20px;
    text-align: center;
}
.service-card img {
    width: 100%;
    border-radius: 5px;
    margin-bottom: 10px;
}
.service-card h3 {
    font-size: 18px;
    margin-bottom: 5px;
}
.service-card p {
    font-size: 14px;
    margin-bottom: 15px;
}
.service-card a {
    color: #333;
    text-decoration: none;
    padding: 5px 10px;
    background-color: #ddd;
    border-radius: 3px;
}
.cta {
    background-color: #ddd;
    padding: 20px;
    text-align: center;
}
.cta h2 {
    font-size: 24px;
    margin-bottom: 10px;
}
.cta a {
    color: #fff;
    background-color: #333;
    padding: 10px 20px;
    border-radius: 5px;
}
footer {
      background-color: #000000;
      padding: 20px 0;
      text-align: center;
      color: #ffffff;
    }
    footer a {
      color: #ffffff;
      text-decoration: none;
      margin: 0 5px;
    }

    footer a:hover {
      color: #007bff;
    }
    footer .social-icons {
      display: flex;
      justify-content: center;
      margin-top: 10px;
    }
    footer .social-icons img {
      width: 25px;
      height: 25px;
      margin: 0 5px;
    }
  </style>
</head>
<body align="center">
  <header>
    </header>
  <main>
    <h1 align="center"><b>Our Services</b></h1>
    <h2 align="center"><p>We offer a variety of software development services to help you achieve your business goals.</p></h2>

    <div class="services-container" align="center">
      <div class="service-card">
        <h3>Web Development</h3>
        <p>We design and develop high-quality, user-friendly websites that are optimized for performance and conversion.</p>
        <a href="#">Learn More</a>
      </div>
      <div class="service-card">
        <h3>Mobile App Development</h3>
        <p>We create innovative and engaging mobile apps for iOS and Android that meet your specific needs.</p>
        <a href="#">Learn More</a>
      </div>
      <div class="service-card">
        <h3>Custom Software Development</h3>
        <p>We build customized software solutions that meet your unique business requirements and workflow.</p>
        <a href="#">Learn More</a>
      </div>
      </div>
    <h2 align="center"><b>Why Choose Us?</b></h2>
    <ul align="center">
      <h3>Experienced team of software developers</h3>
      <h3>Proven track record of success</h3>
      <h3>Focus on quality and customer satisfaction</h3>
      <h3>Competitive pricing</h3>
    </ul>
  </main>
  <footer>
    <p>&copy; 2023 <a href="#">CODAX</a> All rights reserved.</p>
    <p><b>Designed and Developed by Gokkul (23014201)</b></p>
    <section id="contact">
        <a href="Contact.html"><h3>Contact us</h3></a> 
        <a href="login.html"><h3>Login</h3></a> 
  </section>
    <p>
      <a href="#">Privacy Policy</a> |
      <a href="#">Terms of Service</a>
    </p>
    <div class="social-icons">
      <a href="#"><img src="download.png" alt="Facebook"></a>      
        <a href="#"><img src="download (1).png" alt="Twitter"></a>     
        <a href="#"><img src="download (2).png" alt="LinkedIn"></a>
    </div>
  </footer>
</body>
</html>
### product:
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>[Product Name] - CODAX</title>
  <style>
    .products {
      padding: 20px;
    }
    .products h2 {
        font-size: 24px;
        font-weight: bold;
        margin-bottom: 20px;
    }
    .products .product {
        display: inline-block;
        width: 200px;
        height: 200px;
        border-radius: 5px;
        margin-right: 20px;
        margin-bottom: 20px;
        text-align: center;
    }
    .products .product img {
        width:100px;
        height:100px;
        border-radius: 5px;
    }
    .products .product h3 {
        font-size: 18px;
        font-weight
    }
footer {
      background-color: #f1f1f1;
      padding: 20px 0;
      text-align: center;
    }
    footer a {
      color: #333;
      text-decoration: none;
      margin: 0 5px;
    }
    footer a:hover {
      color: #007bff;
    }
    footer .social-icons {
      display: flex;
      justify-content: center;
      margin-top: 10px;
    }
    footer .social-icons img {
      width: 25px;
      height: 25px;
      margin: 0 5px;
    }
  </style>
</head>
<body>
    <section id="products">
        <h1>OUR PRODUCTS</h1>
        <div class="products">
            <div class="product">
                <img src="download (2).jpeg" alt="Product 1">
                <h2>Mobile app development </h2>
                <h3>Leverage our expertise to create tailor-made mobile applications that align with your business objectives. From concept to deployment, we ensure that your app stands out in functionality, design, and user experience.</h3>
                <br>
                <br>
                <br>
                <br>
                <br>
            </div>
            <div class="product">
                <img src="download.jpeg" alt="Product 2">
                <h2>Web development</h2>
                <h3>Design is a crucial aspect of web development, involving the creation of the visual layout and user interface of a website.We ,the Designers use tools like Adobe XD, Sketch, or Figma to create wireframes and mockups, determining the overall look and feel of the site.</h3>
                <br>
                <br>
                <br>
                <br>
                
            </div>
            <div class="product">
                <img src="it.jpeg" alt="Product 3" >
                <h2>IT counsulting</h2>
                <h3>IT consultants begin by conducting a comprehensive assessment of the client's existing IT infrastructure, systems, and processes. This involves evaluating hardware, software, networks, security protocols, and organizational workflows.</h3>
                <br>
                <br>
                <br>
                <br>
            </div>
            <div class="product">
                <img src="cyber.jpeg" alt="Product 4" >
                <h2>cyber security</h2>
                <h3> we understand that in today's interconnected world, safeguarding your digital assets is paramount. Our cybersecurity services are designed to provide robust protection, proactive threat detection, ensuring that your organization stays ahead in the ever-evolving landscape of cyber threats.</h3>
                <br>
            </div>
            <div class="product">
                <img src="A-pathway-that-UIUX-team-follows-before-designing-your-app.png" alt="Product 5" >
                <h2>ui and ux development</h2>
                <h3>we understand that a seamless and engaging user experience is the cornerstone of successful digital products. Our UI/UX development services are meticulously crafted to transform your vision into an intuitive,and user-centric interface that captivates your audience and drives meaningful interactions.</h3>
                <br>
            </div>
  <footer>
    <p>&copy; 2023 <a href="#">CODAX</a> All rights reserved.</p>
    <p>Designed and Developed by Gokkul (23014201)</p>
    <section id="contact">
        <a href="Contact.html"><h2>Contact us</h2></a> 
  </section>
    <p>
      <a href="#">Privacy Policy</a> |
      <a href="#">Terms of Service</a>
    </p>
    <div class="social-icons">
      <a href="#"><img src="download.png" alt="Facebook"></a>      
        <a href="#"><img src="download (1).png" alt="Twitter"></a>     
        <a href="#"><img src="download (2).png" alt="LinkedIn"></a>
    </div>
  </footer>
</body>
</html
### contact:
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - Software Company</title>
  <style>
    body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}
header {
  background-color: #333;
  color: #fff;
  padding: 20px;
}
main {
  padding: 20px;
}
h1 {
  font-size: 2em;
  margin-bottom: 20px;
}
.contact-info {
  display: flex;
  align-items: center;
  margin-bottom: 30px;
}
.contact-info img {
  width: 200px;
  margin-right: 20px;
}
.contact-info ul {
  list-style: none;
  padding: 0;
}
.contact-info li {
  margin-bottom: 10px;
}
.contact-info span.icon {
  display: inline-block;
  width: 30px;
  text-align: center;
  background-color: #ddd;
  border-radius: 50%;
  margin-right: 10px;
}
.contact-info span.icon i {
  font-size: 1.5em;
  color: #333;
}
.contact-form {
  background-color: #f1f1f1;
  padding: 20px;
  border-radius: 5px;
}
.contact-form label {
  display: block;
  margin-bottom: 5px;
  font-weight: bold;
}
.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 5px;
  border: 1px solid #ccc;
  border-radius: 3px;
}
  </style>
</head>
<body>
  <header>
    </header>
  <main>
    <h1>Get In Touch</h1>
    <section class="contact-info">
      <img src="contact us.jpeg" alt="Contact us illustration">
      <p>We'd love to hear from you! Please fill out the form below to send us a message.</p>
      <ul>
        <li>
          <span class="icon"><i class="fas fa-phone-alt"></i></span>
          <a href="tel:+1234567890">+1 (234) 567-890</a>
        </li>
        <li>
          <span class="icon"><i class="fas fa-envelope"></i></span>
          <a href="mailto:info@example.com">info@example.com</a>
        </li>
        <li>
          <span class="icon"><i class="fas fa-map-marker-alt"></i></span>
          <address>123 Main Street, Anytown, CA 90210</address>
        </li>
      </ul>
    </section>
    <section class="contact-form">
      <h2>Contact Form</h2>
      <form action="" method="post">
        <label for="name">Your Name:</label>
        <input type="text" name="name" id="name" required>
        <label for="email">Your Email:</label>
        <input type="email" name="email" id="email" required>
        <label for="message">Your Message:</label>
        <textarea name="message" id="message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>
  <footer>
    </footer>
</body>
</html>
### about:
<html>
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OUR PRESTIGIOUS FOUNDER</title>
    <style>
    header {
      background-color: #222;
      color: #fff;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .founder-page {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 50px;
      background-color: #eee;
    }
    .founder-image {
      width: 100px;
      height: 100px;
      margin-right: 0px;
      border-radius: 5px;

    }
    .founder-content {
      width: 60%;
      margin-right: 200px;
      line-height: 1.5;
    }
    h2 {
      font-size: 24px;
      margin-bottom: 10px;
    }
    p {
      font-size: 16px;
      margin-bottom: 20px;
    }
    .founder-achievements {
      list-style: none;
      padding: 0;
      margin-bottom: 20px;
    }
    .founder-achievements li {
      font-size: 16px;
      margin-bottom: 5px;
    }
    .button {
      padding: 10px 20px;
      background-color: #007bff;
      color: #fff;
      border-radius: 5px;
      font-size: 16px;
    }
    .button:hover {
      background-color: #0067cc;
    }
    footer {
      background-color: #f1f1f1;
      padding: 20px 0;
      text-align: center;
    }
    footer a {
      color: #333;
      text-decoration: none;
      margin: 0 5px;
    }

    footer a:hover {
      color: #007bff;
    }
    footer .social-icons {
      display: flex;
      justify-content: center;
      margin-top: 10px;
    }
    footer .social-icons img {
      width: 25px;
      height: 25px;
      margin: 0 5px;
    }
    </style>
    </head>
    <body>
        <header>
        <h2> OUR PRESTIGIOUS FOUNDER</h2>
        </header>
        <section class="founder-page">
            <div class="founder-image">
              <img src="download (1).jpeg" alt="Founder Photo">
            </div>
            <div class="founder-content">
              <h2>Meet our TONY STARK, Our Visionary Leader</h2>
              <h3><p>Bio: His journey in the world of technology began early. Always fascinated by the potential of code and innovation, he spent countless hours tinkering with circuits, building programs, and dreaming of the future. This passion led him to success at a very young age, laying the foundation for a remarkable career in the tech industry.</p></h3>
              <ul class="founder-achievements">
                <li><b>Achievement:Revolutionized the education landscape with a groundbreaking AI-powered learning platform, increasing student engagement by 75% and closing the achievement gap in underserved communities. </b></li>
              </ul>
            </div>
          </section>
          <section class="founder-page">
            <div class="founder-image">
              <img src="download (3).jpeg" alt="Founder Photo">
            </div>
            <div class="founder-content">
              <h2>Meet BRUCE WAYNE, Our CTO</h2>
              <p>Bio: Bruce Wayne, born into a family of engineers and visionaries, exhibited an innate curiosity for technology from a young age. He earned his stripes in computer science at Cyberspace University, where he quickly became known for his unconventional approach to problem-solving. After completing his education, he delved into the startup scene, co-founding a series of successful ventures that caught the attention of tech enthusiasts and investors alike.</p>
              <ul class="founder-achievements">
                <li>Achievement: Bruce Wayne spearheaded the development of NeuralSprint, a groundbreaking framework that revolutionized machine learning deployment. This innovative framework enables seamless integration of machine learning models into diverse applications, making AI more accessible and user-friendly for developers.</li>
              </ul>
            </div>
          </section>
          <section class="founder-page">
            <div class="founder-image">
              <img src="images (1).jpeg" alt="Founder Photo">
            </div>
            <div class="founder-content">
              <h2>Meet CISCO RAMON, Our Director</h2>
              <p>Bio: Cisco, born into a family of software enthusiasts, displayed an early fascination with coding and problem-solving. He embarked on his academic journey at TechGenius University, earning a degree in Computer Science with honors. His insatiable curiosity and leadership potential quickly set him apart, catching the attention of industry leaders.</p>
              <ul class="founder-achievements">
                <li>Achievement: Under Cisco's leadership, Quantum Dynamics embraced a DevOpsInnovate culture, fostering collaboration between development and operations teams. This cultural shift has resulted in faster release cycles, improved software deployment processes, and enhanced overall product quality.</li>
               
              </ul>
            </div>
          </section>
    </body> 
    <footer>
        <p>&copy; 2023 <a href="#">CODAX</a> All rights reserved.</p>
        <p>Designed and Developed by Gokkul (23014201)</p>
        <section id="contact">
            <a href="Contact.html"><h2>Contact us</h2></a> 
      </section>
        <p>
          <a href="#">Privacy Policy</a> |
          <a href="#">Terms of Service</a>
        </p>
        <div class="social-icons">
          <a href="#"><img src="download.png" alt="Facebook"></a>      
            <a href="#"><img src="download (1).png" alt="Twitter"></a>     
            <a href="#"><img src="download (2).png" alt="LinkedIn"></a>
        </div>
      </footer>
</html>
### login:
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software Company Login</title>
<style>
    body {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
}
.container {
    width: 400px;
    margin: 50px auto;
    padding: 30px;
    border-radius: 5px;
    background-color: #f2f2f2;
}
header {
    text-align: center;
    margin-bottom: 20px;
}
h1 {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 5px;
}
p {
    font-size: 16px;
    color: #777;
}
form {
    display: flex;
    flex-direction: column;
    align-items: center;
}
label {
    margin-bottom: 5px;
    font-size: 14px;
}
input {
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 3px;
    margin-bottom: 15px;
    width: 100%;
}
button {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 3px;
    font-size: 16px;
    cursor: pointer;
}
button:hover {
    opacity: 0.8;
}
a {
    text-decoration: none;
    color: #777;
    font-size: 14px;
    margin-top: 10px;
}
</style>
</head>
<body>
    <div class="container">
        <header>
            <h1><b>CODAX</b></h1>
            <h1>Login</h1>
            <p>Welcome back!</p>
        </header>
        <form action="/login" method="post">
            <label for="username">Username:</label>
            <input type="text" name="username" id="username" required>
            <label for="password">Password:</label>
            <input type="password" name="password" id="password" required>
            <button type="submit">Login</button>
            <a href="/forgot-password">Forgot Password?</a>
        </form>
    </div>
</body>
</html>
```
## OUTPUT:
![Alt text](1.png)
![Alt text](2.png)
![Alt text](3.png)
![Alt text](4.png)
![Alt text](5.png)
![Alt text](6.png)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
