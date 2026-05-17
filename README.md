<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Basic Settings -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Title -->
    <title>Quiz App</title>

    <!-- Font Awesome -->
    <link rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Internal CSS -->
    <style>

        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, sans-serif;
        }

        body{
            background:#f4f4f4;
            color:#333;
        }

        /* Navigation Bar */
        .navbar{
            background:#007bff;
            color:white;
            display:flex;
            justify-content:space-between;
            align-items:center;
            padding:15px 40px;
        }

        .logo{
            font-size:24px;
            font-weight:bold;
        }

        .nav-links{
            list-style:none;
            display:flex;
            gap:20px;
        }

        .nav-links a{
            text-decoration:none;
            color:white;
            font-weight:bold;
        }

        .nav-links a:hover{
            color:yellow;
        }

        /* Hero Section */
        .hero{
            height:90vh;
            display:flex;
            flex-direction:column;
            justify-content:center;
            align-items:center;
            text-align:center;
            background:linear-gradient(rgba(0,0,0,0.5),
            rgba(0,0,0,0.5)),
            url('https://images.unsplash.com/photo-1522202176988-66273c2fd55f')
            center/cover no-repeat;

            color:white;
        }

        .hero h1{
            font-size:50px;
            margin-bottom:20px;
        }

        .hero p{
            font-size:20px;
            margin-bottom:20px;
        }

        .btn{
            background:yellow;
            color:black;
            padding:12px 25px;
            border:none;
            border-radius:5px;
            cursor:pointer;
            font-size:18px;
            text-decoration:none;
            font-weight:bold;
        }

        .btn:hover{
            background:orange;
        }

        /* Sections */
        section{
            padding:60px 20px;
            text-align:center;
        }

        .section-title{
            font-size:35px;
            margin-bottom:20px;
            color:#007bff;
        }

        /* Quiz Cards */
        .quiz-container{
            display:flex;
            justify-content:center;
            gap:20px;
            flex-wrap:wrap;
        }

        .quiz-card{
            background:white;
            width:250px;
            padding:20px;
            border-radius:10px;
            box-shadow:0 0 10px rgba(0,0,0,0.1);
        }

        .quiz-card i{
            font-size:40px;
            color:#007bff;
            margin-bottom:15px;
        }

        .quiz-card h3{
            margin-bottom:10px;
        }

        /* About Section */
        .about{
            background:white;
        }

        /* Contact Section */
        .contact-form{
            max-width:500px;
            margin:auto;
        }

        .contact-form input,
        .contact-form textarea{
            width:100%;
            padding:12px;
            margin:10px 0;
            border:1px solid #ccc;
            border-radius:5px;
        }

        /* Footer */
        footer{
            background:#007bff;
            color:white;
            text-align:center;
            padding:20px;
        }

    </style>
</head>

<body>

    <!-- Navigation -->
    <nav class="navbar">

        <div class="logo">
            Quiz App
        </div>

        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#quiz">Quiz</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>

    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">

        <h1>Welcome to Quiz App</h1>

        <p>
            Improve your knowledge with fun and interactive quizzes.
        </p>

        <a href="#quiz" class="btn">
            Start Quiz
        </a>

    </section>

    <!-- Quiz Section -->
    <section id="quiz">

        <h2 class="section-title">Quiz Categories</h2>

        <div class="quiz-container">

            <div class="quiz-card">
                <i class="fa-solid fa-flask"></i>
                <h3>Chemistry Quiz</h3>
                <p>Test your science knowledge.</p>
            </div>

            <div class="quiz-card">
                <i class="fa-solid fa-calculator"></i>
                <h3>Math Quiz</h3>
                <p>Solve interesting math questions.</p>
            </div>
            
           <div class="quiz-card">
            <i class="fa-solid fa-book"></i>
            <h3>Physics Quiz</h3>
            <!-- Physics Quiz Questions -->

<div class="quiz-box">

    <!-- Question 1 -->
    <h2>1. What is the SI unit of force?</h2>

    <input type="radio" name="q1"> Joule <br>
    <input type="radio" name="q1"> Newton <br>
    <input type="radio" name="q1"> Watt <br>
    <input type="radio" name="q1"> Pascal <br><br>


    <!-- Question 2 -->
    <h2>2. What is the speed of light in vacuum?</h2>

    <input type="radio" name="q2"> 3 × 10⁸ m/s <br>
    <input type="radio" name="q2"> 3 × 10⁶ m/s <br>
    <input type="radio" name="q2"> 300 m/s <br>
    <input type="radio" name="q2"> 1500 m/s <br><br>


    <!-- Question 3 -->
    <h2>3. Which device is used to measure electric current?</h2>

    <input type="radio" name="q3"> Voltmeter <br>
    <input type="radio" name="q3"> Thermometer <br>
    <input type="radio" name="q3"> Ammeter <br>
    <input type="radio" name="q3"> Barometer <br><br>


    <!-- Question 4 -->
    <h2>4. What is the formula of force?</h2>

    :contentReference[oaicite:0]{index=0}

    <input type="radio" name="q4"> F = mv <br>
    <input type="radio" name="q4"> F = ma <br>
    <input type="radio" name="q4"> F = m/a <br>
    <input type="radio" name="q4"> F = v/a <br><br>


    <!-- Question 5 -->
    <h2>5. Which energy is stored in a stretched spring?</h2>

    <input type="radio" name="q5"> Heat Energy <br>
    <input type="radio" name="q5"> Kinetic Energy <br>
    <input type="radio" name="q5"> Potential Energy <br>
    <input type="radio" name="q5"> Sound Energy <br><br>


    <!-- Question 6 -->
    <h2>6. What is the acceleration due to gravity on Earth?</h2>

    <input type="radio" name="q6"> 5 m/s² <br>
    <input type="radio" name="q6"> 9.8 m/s² <br>
    <input type="radio" name="q6"> 15 m/s² <br>
    <input type="radio" name="q6"> 20 m/s² <br><br>


    <!-- Question 7 -->
    <h2>7. Which wave can travel in vacuum?</h2>

    <input type="radio" name="q7"> Sound Wave <br>
    <input type="radio" name="q7"> Water Wave <br>
    <input type="radio" name="q7"> Electromagnetic Wave <br>
    <input type="radio" name="q7"> Seismic Wave <br><br>


    <!-- Submit Button -->
    <button>Submit Quiz</button>

    </div>
            <p>Solve challenging questions in Physics</p>
           </div>
            <div class="quiz-card">
                <i class="fa-solid fa-earth-africa"></i>
                <h3>Geography Quiz</h3>
                <p>Explore the world through quizzes.</p>
            </div>

        </div>

    </section>

    <!-- About Section -->
    <section class="about" id="about">

        <h2 class="section-title">About Us</h2>

        <p>
            We developed this quiz app to help students learn in a fun and easy way.
            Our goal is to improve education using technology.
        </p>

    </section>

    <!-- Contact Section -->
    <section id="contact">

        <h2 class="section-title">Contact Us</h2>

        <div class="contact-form">

            <input type="text" placeholder="Enter your name">

            <input type="email" placeholder="Enter your email">

            <textarea rows="5" placeholder="Write your message"></textarea>

            <button class="btn">
                Send Message
            </button>

        </div>

    </section>

    <!-- Footer -->
    <footer>

        <p>
            © 2026 Quiz App | All Rights Reserved
        </p>

    </footer>

</body>
</html>
