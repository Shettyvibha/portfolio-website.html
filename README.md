<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Your Portfolio</title>
</head>
<style>
    /* Basic styles for the fixed navigation menu */
.fixed-menu {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: #ec09ecec;
    z-index: 100;
}

.fixed-menu ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: space-around;
}

.fixed-menu li {
    margin: 0;
    padding: 0;
}

.fixed-menu a {
    text-decoration: none;
    color: #0e0b0b;
    padding: 15px 20px;
    display: block;
    transition: background-color 0.3s, color 0.3s;
}

/* Change background color and font color on hover */
.fixed-menu a:hover {
    background-color: #fff;
    color: #dc0e0e;
}

</style>
</style>
<header>
    <nav class="fixed-menu">
        <ul>
            <li><a href="#"><b>HOME</b></a></li>
            <li><a href="portfolio.html"><b>ABOUT ME</b></a></li>
            <li><a href="#"><b>PORTFOLIO</b></a></li>
            <li><a href="services.html"><b>SERVICES</b></a></li>
        </ul>
    </nav>
    </nav>
    <!-- main banner -->
    <section class="bgimage" id="home">
        <div class="container-fluid">
            <div class="row">
            <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12 hero-text">
                <h2 class="hero_title">Hi, it's me Vibha Shetty</h2>
                <p class="hero_desc">I am a WEB DEVELOPER</p>
            </div>
            </div>
        </div>
    </section>
    <style>
        /* web background image */
.bgimage {
    height:100vh;
    background: url("developer.webp");
    background-size:cover;
    position:relative;
}
/* text css above hero image*/
.hero_title {
    font-size: 4.5rem;
}
.hero_desc {
    font-size: 2rem;
}
.hero-text {
    text-align: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
}
    </style>
   
</body>
</html>

ABOUT ME
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Your Name - Web Developer</title>
</head>
<style>
    /* Reset some default styles */
body, h1, h2, p {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
}

/* Header */
header {
    background-color: #089aee;
    color: #09cdf5;
    padding: 10px 0;
}

nav ul {
    list-style-type: none;
    text-align: center;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: #040111ea;
}

/* Home Section */
#home {
    text-align: center;
    padding: 100px 0;
}

#home h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

#home img {
    border-radius: 50%;
    width: 200px;
    height: 200px;
    margin: 20px 0;
}
/* Add this to your styles.css file */
.home-bg {
    background-color: #3498db; /* Replace with your desired background color */
    color: #06e7eae7; /* Set the text color to contrast with the background */
    background-image: url("web.webp"); /* Replace with the path to your background image */
    background-size: cover; /* Ensures the image covers the entire section */
    background-position: center; /* Center the image horizontally and vertically */
    color: #082de8; /* Set the text color to contrast with the background */
    text-align: center; /* Center-align text within the section */
    padding: 300px 0; /* Adjust padding as needed for content placement */
    width: 100%; /* Set the width to cover the entire viewport width */
    height: 30vh; /* Set the height to cover the entire viewport height */
}


/* About Section */
#about {
    background-color: #48f006;
    padding: 50px 0;
}

#about h2 {
    font-size: 2rem;
}

/* Projects Section */
#projects {
    padding: 50px 0;
}

#projects h2 {
    font-size: 2rem;
}  
 
#projects {
    background-color: #aaf006;
    padding: 50px 0;
}


/* Contact Section */
#contact {
    background-color: #333;
    color: #fff;
    padding: 50px 0;
}

#contact h2 {
    font-size: 2rem;
}

/* Footer */
footer {
    text-align: center;
    background-color: #333;
    color: #fff;
    padding: 10px 0;
}


</style>
<body>
    
        
           
    <header>
        <nav>
            <ul>
                <li><a href="#about"><b>ABOUT ME</b></a></li>
                <li><a href="#projects"><b>PROJECTS</b></a></li>
                <li><a href="#contact"><b>CONTACT</b></a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <section id="home" class="home-bg">
    <!-- Content of the home section goes here -->
</section>

        <div class="container">
            <h1>WEB DEVELOPER</h1>
            <div class="container">
                <div class="logo">
                    <img src="vibha.jpeg.jpeg" alt="Your Logo">
    
            <p><H2>VIBHA SHETTY</H2></p>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            
            <p>Hello, I'm Vibha Shetty , a passionate web developer with a strong background in front-end and back-end development. Currently persuading my studies in Thakur College Of Engineering and Technology, where I gained a solid foundation in programming and problem-solving.</p>
        
        <p>Throughout my career, I've had the privilege of working on various web projects, ranging from e-commerce platforms to content management systems. I specialize in technologies such as HTML, CSS, JavaScript, and have experience with frameworks like React and Node.js.</p>

        <p>My goal is to create user-friendly, efficient, and visually appealing websites and applications that meet the unique needs of clients. I'm a lifelong learner, always eager to stay updated with the latest web development trends and best practices.</p>

        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>My Project</h2>
    </p>
        <p>Description: This project is a Donation website built using HTML,CSS, and JavaScript. It allows users to donate also to raise funds for charitable,educational,or humanitarion purposes.Nonprofit Organizations,foundations and social enterprises also rely on these platforms to generate finanacial support for their programs,events and iniatives.
    <img src="donation1.jpg.jpeg" width="500" height="400" alt="Project 1 Screenshot">
    <img src="donation2.jpg.jpeg" width="500" height="400"  alt="Project 1 Screenshot">
    <img src="donation3.jpg.jpeg" width="500" height="400" alt="Project 1 Screenshot">
    <img src="donation4.jpg.jpeg" width="500" height="400" alt="Project 1 Screenshot">
    
    <p>Technologies Used: HTML, CSS, JavaScript</p>
    <p>Your Role: Web Developer</p>
    <p>Project Date: January 2022 - Present</p>

           
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Email: vibhashetty@5412</p>
            <p>Phone: 9674589198</p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/vibha-shetty-7b8b6227b/" ></a>YOUR LINKEDIN PROFILE</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 personal portfolio by- Vibha Shetty</p>
    </footer>
</body>
</html>

SERVICES
<!-- services section-->
<section id="services">
    <div class="container">
        <h1 class="text-center">Services</h1>
        <div class="row">
            <div class="col-lg-4 mt-4">
                <div class="card servicesText">
                    <div class="card-body">
                        <i class="fas servicesIcon fa-clock"></i>
                        <h4 class="card-title mt-3">Website Development</h4>
                        <p class="card-text mt-3">Website development services encompass the creation, design, and maintenance of websites. These services involve the use of various technologies and programming languages to build responsive, user-friendly, and visually appealing websites that cater to clients' specific needs. From e-commerce platforms to informational sites, website development services play a crucial role in establishing a strong online presence for businesses and individuals.
                        </p>
                    </div>
                </div>  
            </div>
            <div class="col-lg-4 mt-4">
                <div class="card servicesText">
                    <div class="card-body">
                        <i class='fas servicesIcon fa-layer-group'></i>
                        <h4 class="card-title mt-3">Website Design</h4>
                        <p class="card-text mt-3">
                <P>Website design services involve creating visually appealing, user-friendly, and functional websites tailored to a client's needs and brand identity. Skilled designers utilize a combination of layout, graphics, typography, and interactive elements to enhance the online presence and user experience, ultimately helping businesses and individuals reach their digital goals.</P>
                    </div>
                </div>  
            </div>

            <div class="col-lg-4 mt-4">
                <div class="card servicesText">
                    <div class="card-body">
                        <i class='far servicesIcon fa-check-circle'></i>
                        <h4 class="card-title mt-3">Website Deployment</h4>
                        <p class="card-text mt-3">A website deployment service is a platform or solution that simplifies the process of taking a web application or website from development to being accessible online. It typically involves activities such as configuring servers, deploying code, managing databases, and ensuring the website is accessible to users on the internet. These services help streamline the deployment process, making it more efficient and reliable for developers and organizations.
                        </p>
                    </div>
                </div>  
            </div>
        </div>

        <div class="row">
            <div class="col-lg-4 mt-4">
                <div class="card servicesText">
                    <div class="card-body">
                        <i class='fas servicesIcon fa-search'></i>
                        <h4 class="card-title mt-3">SEO</h4>
                        <p class="card-text mt-3">Search Engine Optimization (SEO) is a crucial digital marketing service aimed at enhancing a website's visibility and ranking on search engines like Google. By optimizing on-page and off-page factors, SEO helps drive organic traffic, improve user experience, and ultimately increase online presence and business growth.
                        </p>
                    </div>
                </div>  
            </div>

            <div class="col-lg-4 mt-4">
                <div class="card servicesText">
                    <div class="card-body">
                        <i class='fas servicesIcon fa-shield-alt'></i>
                        <h4 class="card-title mt-3">DevOps</h4>
                        <p class="card-text mt-3">DevOps, short for Development and Operations, is a set of practices that promote collaboration and communication between software development and IT operations teams. It aims to automate and streamline the software delivery process, enabling faster and more reliable application development and deployment. DevOps services encompass a range of tools and methodologies, such as continuous integration, continuous delivery, and infrastructure as code, to help organizations deliver software more efficiently and with higher quality.
                        </p>
                    </div>
                </div>  
            </div>

            <div class="col-lg-4 mt-4">
                <div class="card servicesText">
                    <div class="card-body">
                        <i class='fas servicesIcon fa-wrench'></i>
                        <h4 class="card-title mt-3">QA</h4>
                        <p class="card-text mt-3">Quality Assurance (QA) service plays a critical role in ensuring the reliability and functionality of software and applications. It involves rigorous testing, meticulous bug identification, and performance evaluation to deliver products that meet the highest standards of quality and user satisfaction.





                        </p>
                    </div>
                </div>  
            </div>
        </div>
    </div>
</section>
<style>
    /* services section css */
.servicesText.card {
    height: 280px;
    cursor: pointer;
  }
.servicesIcon {
    font-size: 36px;
    text-align: center;
    width: 100%;
}
.card-title {
    text-align: center;
}
</style>

