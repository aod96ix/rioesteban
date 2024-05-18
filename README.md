<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rio Esteban Professional Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #333;
        }
        header {
            position: fixed;
            top: 0;
            width: 100%;
            background-color: rgba(255, 255, 255, 0.9);
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            z-index: 1000;
        }
        header nav {
            display: flex;
            justify-content: space-around;
            padding: 1em 0;
        }
        header nav a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            padding: 0.5em 1em;
            position: relative;
        }
        header nav a:hover::after {
            content: "";
            position: absolute;
            bottom: -5px;
            left: 50%;
            width: 0;
            height: 2px;
            background-color: #f0c674;
            transition: all 0.3s;
        }
        header nav a:hover::after {
            left: 0;
            width: 100%;
        }
        section {
            padding: 2em 1em;
            margin-top: 80px;
        }
        .dropdown {
            position: absolute;
            display: none;
            background-color: rgba(255, 255, 255, 0.9);
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            top: 100%;
            left: 0;
            width: 200px;
            z-index: 1000;
        }
        .dropdown a {
            display: block;
            padding: 1em;
            text-decoration: none;
            color: #333;
        }
        nav a:hover .dropdown {
            display: block;
        }
        .overlay-text {
            background: rgba(255, 255, 255, 0.8);
            padding: 1em;
            margin-bottom: 1em;
            border-radius: 5px;
        }
        .transparent-yellow {
            background: rgba(255, 255, 0, 0.2);
        }
        .transparent-blue {
            background: rgba(0, 0, 255, 0.2);
        }
        .images {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .images img {
            max-width: 100%;
            height: auto;
            margin: 1em;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<header>
    <nav>
        <a href="#programs">Programs
            <div class="dropdown">
                <a href="#asylum">Asylum Seeking</a>
                <a href="#immigration">Immigration Counseling</a>
                <a href="#job">Job Training & Placement</a>
                <a href="#housing">Housing Assistance</a>
            </div>
        </a>
        <a href="#get-involved">Get Involved
            <div class="dropdown">
                <a href="#volunteer-legal">Volunteer: Legal Help</a>
                <a href="#volunteer-social">Volunteer: Social Work</a>
                <a href="#volunteer-outreach">Volunteer: Outreach</a>
            </div>
        </a>
        <a href="#about">About</a>
        <a href="#news">News</a>
        <a href="#donate">Donate</a>
    </nav>
</header>

<section id="programs">
    <h1>Programs</h1>
    <div class="overlay-text transparent-yellow">
        <h2 id="asylum">Asylum Seeking</h2>
        <p>We provide support and guidance for individuals seeking asylum, ensuring they have the resources and information needed to navigate the process.</p>
    </div>
    <div class="overlay-text transparent-blue">
        <h2 id="immigration">Immigration Counseling</h2>
        <p>Our immigration counseling services offer expert advice and support for those looking to settle and integrate into a new country.</p>
    </div>
    <div class="overlay-text transparent-yellow">
        <h2 id="job">Job Training & Placement</h2>
        <p>We offer job training programs to help individuals develop skills and find employment opportunities.</p>
    </div>
    <div class="overlay-text transparent-blue">
        <h2 id="housing">Housing Assistance</h2>
        <p>Our housing assistance program helps individuals and families find safe and affordable housing.</p>
    </div>
</section>

<section id="get-involved">
    <h1>Get Involved</h1>
    <div class="overlay-text transparent-yellow">
        <h2 id="volunteer-legal">Volunteer: Legal Help</h2>
        <p>Join our team of legal experts to provide assistance and support to those in need of legal aid.</p>
    </div>
    <div class="overlay-text transparent-blue">
        <h2 id="volunteer-social">Volunteer: Social Work</h2>
        <p>Help us support the community through social work, providing essential services and support.</p>
    </div>
    <div class="overlay-text transparent-yellow">
        <h2 id="volunteer-outreach">Volunteer: Outreach</h2>
        <p>Participate in outreach programs to connect with and support the community.</p>
    </div>
</section>

<section id="about">
    <h1>About Us</h1>
    <div class="images">
        <img src="/mnt/data/7cc86e0f-ce6a-4b6a-a1ec-446c7d23e196.JPG" alt="Martin Arzu, President">
        <img src="/mnt/data/dc5e391c-14cd-49ac-b9be-b103ab36fc7f.JPG" alt="Linell Lisa Alvarez, Vice President">
    </div>
    <div class="overlay-text transparent-blue">
        <h2>Mission Statement</h2>
        <p>Our mission is to support and uplift the community through dedicated services and programs aimed at improving quality of life.</p>
    </div>
    <div class="overlay-text transparent-yellow">
        <h2>Business Overview</h2>
        <p>Rio Esteban Professional Services offers a range of programs and services designed to assist individuals with asylum seeking, immigration counseling, job training and placement, and housing assistance.</p>
    </div>
</section>

<section id="news">
    <h1>News</h1>
    <div class="overlay-text transparent-blue">
        <h2>Recent Publications</h2>
        <p>Stay tuned for the latest news and updates from Rio Esteban Professional Services, including recent newspaper articles and announcements about upcoming events.</p>
    </div>
</section>

<section id="donate">
    <h1>Donate</h1>
    <div class="overlay-text transparent-yellow">
        <p>Your support is invaluable to us. Please consider making a donation to help us continue our work. You can donate using the following methods:</p>
        <ul>
            <li>Bitcoin Wallet Address: [Your Bitcoin Wallet Address]</li>
            <li>Venmo: [Your Venmo Link]</li>
        </ul>
    </div>
</section>

</body>
</html>
