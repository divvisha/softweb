# Ex.07 Software Product Company Website
## Register Number : 212221040044
## Date: 04-11-2023

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
### Website.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="website.css">
    <link rel="icon" href="Softserves.png">   
    <title>Software Development Company</title>
</head>
<body>
    <header>
        <nav>
            <div class="container">
                <img src="Softserves.png" alt="company logo">
                <h1>OFTSERVES</h1>
                <ul>
                    <li><b><a href="#home">HOME</a></b></li>
                    <li><b><a href="#services">SERVICES</a></b></li>
                    <li><b><a href="#Partners">PARTNERS</a></b></li>
                    <li><b><a href="#contact">CONTACT</a></b></li>
                </ul>
            </div>
        </nav>
    </header>

    <section id="hero">
        <div class="container">
            <h1>Welcome to Softserves</h1>
            <p>We Design Your Digital Dreams</p>
            <a href="#contact" class="btn">Get Started</a>
        </div>
    </section>
    
    <section id="home">
        <div class="container">
            <h1>HOME</h1>
            <div class="home">
                <div class="wrapper">

                    <div class="item">
                      <div class="polaroid"><img src="bb1.jpg" alt="bb1">
                      </div>
                    </div>
                    <div class="item">
                      <div class="polaroid"><img src="bb2.jpg" alt="bb2">
                        
                      </div>
                    </div>
                  
                    <div class="item">
                      <div class="polaroid"><img src="bb3.jpg" alt="bb3">
                      </div>
                    </div>
                  
                    <div class="item">
                      <div class="polaroid" id="aboutus">
                        <h2>ABOUT  US</h2>
                        <h3>We design, develop and maintain applications, frameworks or other software components for business.
                            We thrive on pushing the boundaries of what's possible. Our team of skilled professionals is dedicated 
                            to staying ahead of industry trends, adopting the latest technologies, and pioneering new solutions.
                        </h3>
                      </div>
                    </div>
                  
                  </div>
            </div>
        </div>
    </section>
    
    <section id="services">
        <div class="container">
            <h1>SERVICES</h1>
            <div class="web">
                <a href="#"><img src="wd.jpg" alt="Service 1"></a>
                <h3>Web Application Development</h3>
                <p>Design To Describe</p>
            </div>
            <div class="mobile">
                <a href="#"><img src="md.jpg" alt="Service 2"></a>
                <h3>Mobile Application Development</h3>
                <p>Design to access</p>
            </div>
            <div class="blockchain">
                <a href="#"><img src="bd.jpeg" alt="Service 3"></a>
                <h3>Blockchain Development</h3>
                <p>Design to secure</p>
            </div>
        </div>
    </section>

    <section id="Partners">
        <div class="container">
            <h2>PARTNERS</h2>
            <div class="images">
                <div class="google">
                    <img src="google.png" alt="google">
                </div>
                <div class="microsoft">
                    <img src="microsoft.png" alt="microsoft">
                </div>
                <div class="apple">
                    <img src="apple.png" alt="apple">
                </div>
                <div class="realme">
                    <img src="realme.png" alt="realme">
                </div>
                <div class="nokia">
                    <img src="nokia.png" alt="nokia">
                </div>
                <div class="samsung">
                    <img src="samsung.png" alt="samsung">
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>CONTACT US</h2>
            <img src="cu.png" alt="contact us">
            <h3>Queries or Compliments</h3>
            <p>We accept all just contact below</p>
            <br>
            <form>
                <input type="text" placeholder="Your Name">
                <input type="email" placeholder="Your Email">
                <br><br>
                <textarea placeholder="Your Message"></textarea>
                <br>
                <button type="submit" class="btn">Send</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Company Name. All rights reserved.</p>
            <nav class="coninfo">
                <a href="https://www.facebook.com/"><img src="facebook.png" alt="facebook"></a>
                <a href="https://www.instagram.com/"><img src="insta.png" alt="insta"></a>
                <a href="https://www.linkedin.com/"><img src="linkedin.png" alt="linkedin"></a>
                <a href="https://mail.google.com/"><img src="email.png" alt="email"></a>
                <a href="https://twitter.com/"><img src="twitter.png" alt="twitter"></a>
                <a href="https://youtube.com/"><img src="youtube.png" alt="youtube"></a>
                <div class="myDIV"><img src="phone.png" alt="phone"></div>
                <div class="hide">7558125620</div>
            </nav>
        </div>
    </footer>

</body>
</html>

```
### Website.css:
```
body, h1, h2, h3, p {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    
}

/* Header styles */
header {
    color: black;
    position: fixed;
    width: 1512px;
    height: 160px;
    box-shadow: 0 8px 6px -4px #111111;
    background-color: #0000003a;
    backdrop-filter: blur(50px);
    z-index: 1;
}

header img{
    position: relative;
    width: 300px;
    margin-left: -160px;
    margin-top: -60px;
}
header h1 {
    margin-top: -190px;
    font-size: 60px;
    margin-left: 40px;
    color: #fff;
}

nav ul {
    list-style: none;
    text-align: right;
    margin-top: -50px;
    padding: 2px;
    margin-right: -70px;  
}

nav ul li {
    display: inline;
    padding: 6px 15px;
    border-radius: 10px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-size: large;  
}
nav ul :hover{
  text-decoration: underline;
}

/* Hero section styles */
#hero {
    padding-top: 60px;
    color: #fff;
    text-align: center;
    padding-bottom: 50px;
    padding-top: 230px;
    background-image:url("bg.jpeg");
}

#hero h1 {
    font-size: 50px;
}

#hero p {
    font-size: 22px;
    margin-top: 10px;
    margin-bottom: 30px;
}

.btn {
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    opacity: 60%;
}
.btn:hover{
    opacity: 100%;
}
/* Services section styles */
#home {
    padding: 50px 0;
    background-image:url("bg.jpeg");
}
#home h1{
    text-align: center;
    font-size: 60px;
    font-weight: bolder;
    color: #fff;
}
#home h1:hover{
    text-decoration: underline;
}
#services {
  margin-top: -40px;
  background-color: #e9e5e5;
  padding-bottom: 30px;
}
#services h1{
    text-align: center;
    margin-top: 50px;
    font-size: 60px;
    padding-top: 20px;
}

.web h3 {
    margin-top: 20px;
    margin-left: -20px;
}
.web p {
    margin-top: 5px;
    margin-left: 60px;
}

.web img {
    width: 400px;
    box-shadow: 20px 20px 10px  gray;
    margin-left: -50px;
    margin-top: 60px;
}

.mobile h3 {
  margin-top: -120px;
  margin-left: 430px;
}
.mobile p {
  margin-left: 530px;
  margin-top: 5px;
}

.mobile img {
  width: 400px;
  box-shadow: 20px 20px 10px  gray;
  margin-left: 406px;
  margin-top: -290px;
  margin-bottom: 140px;
  height: 210px;
}

.blockchain h3 {
  margin-top: -215px;
  margin-left: 921px;
}
.blockchain p {
  margin-top: 5px;
  margin-left: 985px;
}

.blockchain img {
  width: 400px;
  box-shadow: 20px 20px 10px  gray;
  margin-left: 862px;
  margin-top: -290px;
  margin-bottom: 240px;
  height: 210px;
}

/* Portfolio section styles */
#Partners {
    background-color: #e9e5e5;
    margin-top: 10px;
}
#Partners h2{
    text-align: center;
    font-size: 60px;
    padding-top: 20px;
    margin-bottom: -600px;
}

/* Contact section styles */
#contact {
    background-color: #fff;
    margin-left: 300px;
    padding-bottom: 50px;
}
#contact h2{
    font-size: 60px;
    padding-top: 20px;
    margin-left: 40px;
}
#contact h3{
  margin-left: 90px;
  margin-top: -350px;
}
#contact p{
  margin-left: 80px;
}
#contact img{
  margin-left: 600px;
  width: 500px;
  height:500px;
  margin-top: -80px;
}

form input{
    width: 200px;
    padding: 10px;
}
form textarea {
    width: 430px;
    padding: 10px;
}

/* Footer styles */
footer {
    background-color: #111111a3;
    color: #fff;
    text-align: center;
    margin-top: 50px;
    padding-bottom: 30px;
    padding-top: 10px;
}
.hide {
  display: none;
}
.myDIV{
  margin-top: -75px;
  margin-left: 450px;
}
.myDIV:hover + .hide {
  display: block;
  color: rgb(0, 191, 255);
  margin-left: 450px;
}
.coninfo{
  margin-left: -70px;
}
.coninfo img{
  padding-top:20px;
  padding-left: 10px;
  width:50px;
  height:50px;
}
.home{
    display: flex;
    justify-content: space-between;
}
/* Container for centering content */
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
    
}
  .wrapper {
    width: 100%;
    padding: 0 2rem;
    text-align: center;
  }
  .polaroid {
    background: #fff;
    padding: 1rem;
    box-shadow: 0 0.2rem 1.2rem rgba(0,0,0,0.2);
  }
  .polaroid h2{
    font-size: 50px;
  }
  .polaroid > img{
    max-width: 100%;
    height: 300px;
  }
  
  .item {
    width: 30%;
    display: inline-block;
    margin-top: 2rem;

  }
#aboutus{
    width:600px;
    margin-left: -150px;
  }
  .item .polaroid:before {
    content: '';
    position: absolute;
    z-index: -1;
    transition: all 0.35s;
  }
  .item:nth-of-type(4n+1) {
    transform: scale(0.8, 0.8) rotate(5deg);
    transition: all 0.35s;
  }
  .item:nth-of-type(4n+1) .polaroid:before {
    transform: rotate(6deg);
    height: 20%;
    width: 47%;
    bottom: 30px;
    right: 12px;
    box-shadow: 0 2.1rem 2rem rgba(0,0,0,0.4);
  }
  .item:nth-of-type(4n+2) {
    transform: scale(0.8, 0.8) rotate(-5deg);
    transition: all 0.35s;
  }
  .item:nth-of-type(4n+2) .polaroid:before {
    transform: rotate(-6deg);
    height: 20%;
    width: 47%;
    bottom: 30px;
    left: 12px;
    box-shadow: 0 2.1rem 2rem rgba(0,0,0,0.4);
  }
  .item:nth-of-type(4n+4) {
    transform: scale(0.8, 0.8) rotate(3deg);
    transition: all 0.35s;
  }
  .item:nth-of-type(4n+4) .polaroid:before {
    transform: rotate(4deg);
    height: 20%;
    width: 47%;
    bottom: 30px;
    right: 12px;
    box-shadow: 0 2.1rem 2rem rgba(0,0,0,0.3);
  }
  .item:nth-of-type(4n+3) {
    transform: scale(0.8, 0.8) rotate(-3deg);
    transition: all 0.35s;
  }
  .item:nth-of-type(4n+3) .polaroid:before {
    transform: rotate(-4deg);
    height: 20%;
    width: 47%;
    bottom: 30px;
    left: 12px;
    box-shadow: 0 2.1rem 2rem rgba(0,0,0,0.3);
  }
  .item:hover {
    filter: none;
    transform: scale(1, 1) rotate(0deg) !important;
    transition: all 0.35s;
  }
  .item:hover .polaroid:before {
    content: '';
    position: absolute;
    z-index: -1;
    transform: rotate(0deg);
    height: 90%;
    width: 90%;
    bottom: 0%;
    right: 5%;
    box-shadow: 0 1rem 3rem rgba(0,0,0,0.2);
    transition: all 0.35s;
  }
  .images{
    margin-top: 650px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    margin-left: 80px;
    align-items: center;
    justify-content: space-evenly;
  }
  .google img{
    width: 350px;
    height:150px;
  }
  .microsoft img{
    width: 350px;
    height: 200px;
  }
  .apple img{
    width: 350px;
    height: 200px;
  }
  .realme img{
    width: 350px;
    height: 100px;
  }
  .nokia img{
    width: 400px;
    height:250px;
  }
  .samsung img{
    width: 300px;
    height:100px;
  }
```


## OUTPUT:

![image](https://github.com/Catty12384/softweb/assets/120629225/84c5a960-dffd-4247-933f-e4ea43114413)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
