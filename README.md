<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Code Practice</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <section id="Hero">
        <div class="container">
            <header class="flex-container">
                <h1 id="Site-Title">Roberto Rivera Creative. Graphic Design and Web Development.</h1>
                <img src="img/zodiaclogo.png" alt="Logo" id="Logo">
                <nav>
                    <ul class="flex-container uppercase">
                        <li><a href="#">Home</a></li>
                        <li><a href="#">About</a></li>
                        <li><a href="#">Portfolio</a></li>
                        <li><a href="#">Hire Me</a></li>
                    </ul>
                </nav>
            </header>
            <div id="Hero-Content">
                <p class="uppercase"><strong>Designer and Developer who creates Awsome art and design!</strong></p>
                <button class="btn-primary">Hire Me</button>
                <button class="btn-secondary">Learn More</button>
            </div>
            
        </div>
    </section>
    <section id="About">
        <div class="container">
            <h2>About Roberto</h2>
            <div id="Profile"><img src="img/selfie_thumb.png" alt="Profile Picture"></div>
            <div id="About-Text"></div>
            
            <h3>Roberto Rivera</h3>
            <p>Designer and Developer</p>
            <p>Louisville, KY</p>
            <div class="row">
                <p>My name is Roberto Rivera. I am a Graphic Designer and Front-End Web Developer currently living in Louisville, KY. I am passionate about creating stunning desings and awesome web experiences. Having graduated from Western Kentucky University have a code louisville certification as of 2019, I am seeking opportunities to work with clients on fulfilling coding and design.</p>
            </div>
        </div>
    </section>
    <section id="Portfolio">
        <div class="container">
            <h2>Portfolio</h2>
            <div class="flex-container">
                <a href="#"><img src="img/lac_thumb.png" alt="Louisville Anime Community Project"></a>
                <a href="#"><img src="img/zodiaclogo_thumb.png" alt="Louisville Anime Community Project"></a>
                <a href="#"><img src="img/olympic_thumb.png" alt="Louisville Anime Community Project"></a>
            </div>
        </div>
        </section>
    <section id="Hire">
        <div class="container">
            <p>Hire Me</p>
        </div>
    </section>
    <footer>
        <div class="container">
            <section id="footerSection">
            <h3>Roberto Rivera. Graphic Designer and Front-End Developer</h3>
            <p>&copy; 2019 All Rights Revserved</p>
        </section>
        </div>
    </footer>
</body>
</html>

@import url('https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,700&display=swap');

* {
  box-sizing: border-box;
}

body{
  margin: 0;
  padding: 0;
  font-family: 'Source Sans Pro', sans-serif;
}

h1, h2, h3, h4, h5, h6, p, ul {
  margin: 0;
}

a, button {
    transition: all 150ms ease-in-out;
    cursor: pointer;
}

img { width: 100%; height: auto;}

#Site-Title {
  display: none;
}

#Logo {
    max-width: 80px;
}

#Hero {
    background: #f6a800 url('../img/hero-img.jpg') no-repeat top center;
    background-size: cover;
    background-blend-mode: multiply;
    position: relative;
    padding-top: 40px;
    padding-bottom: 40px;
    color: white;
    font-size: 3rem;
}

#Hero-Content {
    max-width: 600px;
    margin-top: 6rem;
    margin-bottom: 6rem;
}

#About {background-color: #00234d; color: white;}
#Portfolio {background-color: #00234d; color: white;}
#Hire {background-color: #f6a800;}
footer {background-color: #000000; color: white;}

.container {
  max-width: 1140px;
  width: 80%;
  margin: 0 auto; 
}

.uppercase {text-transform: uppercase;}

.flex-container { 
    display: flex;
    justify-content: space-between;
}

.btn-primary,
.btn-secondary {
    width: 280px;
    padding: 5px 10px;
    color: white;
    font-size: 1.5rem;
    font-weight: bold;
    text-transform: uppercase;
}

.btn-primary {
    background-color: #000000;
    padding: 9px 14px;
    border: 0;
}

.btn-primary:hover {
    background-color: #CA942F;
}

.btn-secondary {
    background-color: transparent;
    border: 5px solid white;
}

.btn-secondary:hover {
    background-color: rgba(255, 255, 255, .4);
}

nav ul {
    padding-left: 0;
}

nav ul li {
    list-style: none;
    margin-right: 18px;
}

nav a {
    text-decoration: none;
    display: block;
    font-size: 24px;
    color: white;
}

nav a:hover {
    color: black;
}

#brand {
    max-width: 900px;
    
}

#Profile {
  max-width: 500px;
}

#About-Text {width: 100%;}
  

#Portfolio .flex-container {
  flex-flow: row wrap-reverse;
  justify-content: center;
}

#Portfolio img:hover {
  border: 5px solid #777;
}

#Portfolio img {
  max-width: 250px;
  width: 100%;
  height: auto;
  background-color: white;
  border-radius: 8px;
  border: 5px solid transparent;
  margin: 5px;
  flex: auto;
}

div.desc {
  padding: 15px;
  text-align: center;
}

p {
    column-count: 2;
    column-gap: 10px;
}

.column {
    background: #ccc;
    display: table-cell;
    padding: 10px;
    width: 33.33333%;
    text-align: center;
 }
© 2020 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog

