<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unstoppable Motivation</title>

    <!-- Google Fonts for Premium Typography -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
    
    <!-- High-quality External CSS Frameworks (Optional) -->
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body, html {
            height: 100%;
            width: 100%;
            font-family: 'Roboto', sans-serif;
            overflow: hidden;
        }

        /* Full Screen Background Image */
        .bg-image {
            background-image: url('https://www.example.com/high-quality-background.jpg'); /* Replace with your high-quality background image URL */
            background-size: cover;
            background-position: center;
            position: absolute;
            top: 0;
            left: 0;
            height: 100%;
            width: 100%;
            filter: brightness(0.5); /* Darken the background image */
        }

        .content {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100%;
            text-align: center;
            color: #fff;
            z-index: 1;
            position: relative;
            padding: 0 20px;
        }

        h1 {
            font-size: 70px;
            color: white;
            font-family: 'Open Sans', sans-serif;
            font-weight: 700;
            letter-spacing: 2px;
            text-shadow: 4px 4px 10px rgba(0, 0, 0, 0.6);
            margin-bottom: 30px;
            animation: fadeInUp 2s ease-out;
        }

        p {
            font-size: 24px;
            margin-top: 10px;
            line-height: 1.6;
            font-weight: 300;
            color: #fff;
            text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.5);
            max-width: 650px;
            animation: fadeInUp 3s ease-out;
        }

        .quote {
            font-style: italic;
            font-size: 30px;
            margin-top: 40px;
            color: #fff;
            letter-spacing: 1px;
            text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.7);
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            background: rgba(0, 0, 0, 0.5);
            border-radius: 12px;
            animation: fadeInUp 4s ease-out;
        }

        .cta-button {
            display: inline-block;
            padding: 18px 50px;
            background-color: #ff6347;
            color: #fff;
            font-size: 26px;
            font-weight: bold;
            text-decoration: none;
            margin-top: 50px;
            border-radius: 12px;
            box-shadow: 0 12px 25px rgba(0, 0, 0, 0.5);
            transition: background-color 0.3s, transform 0.3s;
            animation: fadeInUp 5s ease-out;
        }

        .cta-button:hover {
            background-color: #ff4500;
            transform: translateY(-5px);
        }

        /* Fade-In Animation */
        @keyframes fadeInUp {
            0% {
                opacity: 0;
                transform: translateY(50px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Responsive Design */
        @media only screen and (max-width: 768px) {
            h1 {
                font-size: 50px;
            }
            p {
                font-size: 18px;
            }
            .quote {
                font-size: 22px;
            }
            .cta-button {
                font-size: 22px;
                padding: 15px 40px;
            }
        }
    </style>
</head>
<body>
    <!-- Full-Screen High-Quality Background Image -->
    <div class="bg-image"></div>

    <!-- Content Section -->
    <div class="content">
        <h1>Unlock Your True Potential</h1>
        <p>Push through the challenges and discover the strength within you. Your success story begins now.</p>

        <!-- Motivational Quote Section -->
        <div class="quote">
            <p>"Success is the sum of small efforts, repeated day in and day out." – Robert Collier</p>
        </div>

        <!-- CTA Button: Link to Facebook Share or Any Other Link -->
        <a href="https://www.facebook.com/share/1CbD17ZpPL/" class="cta-button" target="_blank">Share Your Motivation</a>
    </div>
</body>
</html>
