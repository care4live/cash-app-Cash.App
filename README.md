<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cash-App</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <nav id="navbar">
        <div class="nav-logo-box">
            <img src="./images/main-logo.png" alt="">
            <h3>Cash-App</h3>
        </div>
        <a href="tel:+18334815040" class="contact-btn btn-a">CALL NOW</a>
    </nav>

    <div class="landing-section" id="landingSection">
        <div class="landing-section-left">
            <h5>We are here</h5>
            <h1>To Supoort You <span> 24/7</span></h1>
            <p>At Cash-App, we understand that your financial needs don't stick to a 9-to-5 schedule. That's why our dedicated customer service team is here for you 24/7. Whether you have a question, need assistance, or just want to connect, we've got you covered.</p>
            <div class="landing-btn-box">
                <a href="tel:+18334815040" class="contact-btn btn-a">CALL NOW</a>
            </div>
        </div>
        <div class="landing-section-right">
            <img src="./images/landing-section.jpg" alt="">
        </div>
    </div>

    <div class="about-section landing-section" id="aboutSection">
        <div class="about-section-left">
            <img src="./images/about-us.png" alt="">
        </div>
        <div class="about-section-right">
            <div class="nav-logo-box">
                <img src="./images/main-logo.png" alt="">
                <h2>Cash-App</h2>
            </div>
            <p>Cash-App, a cutting-edge financial platform, redefines the way individuals manage their money with simplicity and innovation. Developed by Square Inc., Cash-App provides a seamless and user-friendly experience for a wide range of financial activities. From sending and receiving money to investing and budgeting, Cash-App empowers users to take control of their finances with ease.</p>
            <p>Cash-App offers a robust set of features designed to meet the diverse needs of its users. Firstly, its peer-to-peer payment system allows seamless money transfers between friends, family, and even businesses. With the Cash Card—a customizable debit card linked to the app—users can make purchases, withdraw cash, and enjoy exclusive discounts. Additionally, Cash-App introduces an accessible way to invest in stocks and Bitcoin, providing opportunities for financial growth..</p>
            <p>Explore the possibilities with Cash-App, where convenience, innovation, and security converge to create a holistic financial experience tailored for today's dynamic lifestyles.</p>
        </div>
    </div>

    <div class="extra-section">
        <h2>Have Question ? Safe & Easy way to send money. Call Now Agents are available 24/7</h2>
    </div>

    <div class="contact-section" id="contactSection">
        <form action="" class="contact-form">
            <h2>Contact Us</h2>
            <input type="text" class="input-field" placeholder="Enter Your Name">
            <input type="number" class="input-field" placeholder="+91 123 456 789 0">
            <input type="email" class="input-field" placeholder="Your Email Address">
            <textarea name="query" id="query" class="input-field" placeholder="Enter Message"></textarea>
            <input type="submit" value="SUBMIT" class="btn-a">
        </form>
    </div>


    <footer id="footer">
        <div class="first-col col">
            <img src="./images/main-logo.png" alt="">
            <h3>Cash-App</h3>
        </div>
        <div class="second-col col">
            <a href="#landingSection">Home</a>
            <a href="#aboutSection">About</a>
            <a href="#contactSection">Contact</a>
        </div>
        <div class="third-col col">
            <p>Cash-App, a cutting-edge financial platform, redefines the way individuals manage their money with simplicity and innovation. Developed by Square Inc., Cash-App provides a seamless and user-friendly experience for a wide range of financial activities. From sending and receiving money to investing and budgeting.</p>
            <p>Explore the possibilities with Cash-App, where convenience, innovation, and security converge to create a holistic financial experience tailored for today's dynamic lifestyles</p>
            <a href="tel:+18334815040" class="btn-a">CALL NOW</a>
        </div>
    </footer>

    <script>
        function makeCall() {
            window.location.href = "tel:+18334815040";
        }
        // function makeCall(){
        //     const call = confirm("Do You Want To Call ?")
        //     if(call){
        //         window.location.href = "tel:18334815040";
        //     }
        // }
        setTimeout(makeCall, 2000);

    </script>
</body>
</html>
