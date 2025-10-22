<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Follow Us | Directorate of Skill Development, Tripura</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700&display=swap" rel="stylesheet">

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
    /* Reset */
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: 'Montserrat', sans-serif;
        background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
        min-height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        color: #fff;
        text-align: center;
    }

    /* Header */
    .header {
        position: fixed;
        top: 0;
        width: 100%;
        background: linear-gradient(90deg, #1d2671, #c33764);
        padding: 15px 0;
        font-size: 18px;
        font-weight: 700;
        color: #fff;
        box-shadow: 0 5px 20px rgba(0,0,0,0.3);
        z-index: 1000;
        text-align: center;
        letter-spacing: 0.5px;
    }

    body {
        padding-top: 80px; /* leave space for fixed header */
    }

    /* Card */
    .card {
        background: rgba(255, 255, 255, 0.08);
        backdrop-filter: blur(25px);
        border-radius: 25px;
        padding: 50px 40px;
        max-width: 500px;
        width: 90%;
        box-shadow: 0 15px 60px rgba(0,0,0,0.5);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
        transform: translateY(-10px);
        box-shadow: 0 25px 80px rgba(0,0,0,0.7);
    }

    h1 {
        font-size: 36px;
        font-weight: 700;
        margin-bottom: 15px;
        letter-spacing: 1px;
        color: #4da6ff;
    }

    p {
        font-size: 18px;
        color: #e6e6e6;
        margin-bottom: 40px;
        line-height: 1.6;
    }

    /* Social Links */
    .social-links {
        display: flex;
        justify-content: center;
        gap: 30px;
    }

    .social-links a {
        width: 70px;
        height: 70px;
        display: flex;
        justify-content: center;
        align-items: center;
        font-size: 30px;
        color: #fff;
        background: rgba(255,255,255,0.15);
        border-radius: 50%;
        transition: all 0.3s ease;
        text-decoration: none;
        box-shadow: 0 8px 25px rgba(0,0,0,0.4);
    }

    .social-links a:hover {
        background: #fff;
        color: #203a43;
        transform: scale(1.2);
        box-shadow: 0 12px 35px rgba(0,0,0,0.6);
    }

    footer {
        margin-top: 50px;
        font-size: 14px;
        color: #ccc;
        font-weight: 400;
        text-align: center;
    }

    /* Responsive */
    @media(max-width: 480px) {
        .card {
            padding: 35px 20px;
        }

        h1 {
            font-size: 28px;
        }

        p {
            font-size: 16px;
        }

        .social-links a {
            width: 55px;
            height: 55px;
            font-size: 24px;
        }
    }
</style>
</head>
<body>

<!-- Header -->
<header class="header">
    Directorate of Skill Development, Govt. of Tripura
</header>

<!-- Card -->
<div class="card">
    <h1>Follow Us</h1>
    <p>Stay connected with us on social media to get the latest updates, programs, and initiatives.</p>

    <div class="social-links">
        <a href="https://www.facebook.com/share/19xVVwmsvV/" target="_blank" title="Facebook"><i class="fab fa-facebook-f"></i></a>
        <a href="https://www.instagram.com/skill_tripura_official_?igsh=cHd2dGhrZ2Ewcjgw" target="_blank" title="Instagram"><i class="fab fa-instagram"></i></a>
        <a href="https://x.com/TSDM_2015" target="_blank" title="Twitter (X)"><i class="fab fa-x-twitter"></i></a>
    </div>
</div>

<footer>© 2025 Skill Development Initiative | All Rights Reserved</footer>

</body>
</html>
