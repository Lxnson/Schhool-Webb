<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Lenson Gitachu">
    <title>Nakuru Whizzkids Academy</title>
    
    <!-- Google Font for Fancy Heading -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet">
    
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        /* Color scheme */
        :root {
            --primary-color: #992a2a; /* Soft maroon */
            --secondary-color: #b3b3b3; /* Soft gray */
            --text-color: #333;
        }

        /* Header Styling */
        header {
            background: url('header-bg.jpg') no-repeat center center/cover;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 15px 50px;
            color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .logo img {
            height: 60px;
        }

        .school-name {
            text-align: center;
            animation: fadeIn 2s ease-in-out;
        }

        .school-name h1 {
            font-family: 'Poppins', sans-serif;
            font-size: 2rem;
            font-weight: 600;
        }

        .school-name p {
            font-style: italic;
            font-size: 1rem;
        }

        nav ul {
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: var(--secondary-color);
        }

        /* Hero Section */
        .hero {
            background: url('images/campus-banner.jpg') no-repeat center center/cover;
            height: 60vh;
            color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            animation: fadeIn 2s ease-in-out;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }

        .cta-button {
            padding: 10px 20px;
            background: var(--secondary-color);
            color: var(--primary-color);
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: background 0.3s;
        }

        .cta-button:hover {
            background: white;
        }

        /* Overview Section */
        .overview {
            text-align: center;
            padding: 40px 20px;
        }

        .stages {
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .stage {
            background: var(--secondary-color);
            padding: 20px;
            border-radius: 5px;
            width: 30%;
            box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        .stage:hover {
            transform: scale(1.05);
        }

        /* Testimonials */
        .testimonials {
            text-align: center;
            padding: 40px 20px;
            background: var(--secondary-color);
        }

        .testimonial {
            margin: 20px auto;
            width: 60%;
            font-style: italic;
        }

        /* Events */
        .events {
            padding: 40px;
            text-align: center;
        }

        .event {
            background: var(--primary-color);
            color: white;
            padding: 20px;
            margin: 10px;
            border-radius: 8px;
        }

        /* Footer */
        footer {
            background: var(--primary-color);
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }

        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>

    <script>
        document.addEventListener("DOMContentLoaded", function () {
            console.log("Nakuru Whizzkids Academy Website Loaded Successfully!");
        });
    </script>
</head>
<body>

    <!-- Header with logo, school name, and navigation -->
    <header>
        <div class="logo">
            <img src="logo.png" alt="Nakuru Whizzkids Academy Logo">
        </div>
        <div class="school-name">
            <h1>Nakuru Whizzkids Academy</h1>
            <p>Peak Discipline, Peak Performance</p>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="admissions.html">Admissions</a></li>
                <li><a href="learning.html">Learning</a></li>
                <li><a href="school-life.html">School Life</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section with a full-width banner -->
    <section class="hero">
        <h1>Welcome to Nakuru Whizzkids Academy</h1>
        <p>Inspiring young minds through quality education.</p>
        <a href="admissions.html" class="cta-button">Enroll Now</a>
    </section>

    <!-- Overview Sections -->
    <section class="overview">
        <h2>Our Educational Stages</h2>
        <div class="stages">
            <div class="stage">
                <h3>Early Years</h3>
                <p>Building a strong foundation for young learners.</p>
            </div>
            <div class="stage">
                <h3>Lower School</h3>
                <p>Encouraging curiosity and creativity.</p>
            </div>
            <div class="stage">
                <h3>Upper School</h3>
                <p>Preparing students for future success.</p>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials">
        <h2>What Parents & Students Say</h2>
        <div class="testimonial">
            <p>"This school has transformed my child's learning experience!" – Parent</p>
        </div>
    </section>

    <!-- Events Section -->
    <section class="events">
        <h2>Upcoming Events</h2>
        <div class="event">
            <h3>Sports Day - August 12, 2025</h3>
            <p>Join us for an exciting day of sports and team spirit.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Nakuru Whizzkids Academy. All Rights Reserved.</p>
    </footer>

</body>
</html>

