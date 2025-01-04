<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> About Me </title>
    <style>
        body {
            margin: 0;
            font-family: 'Cairo', sans-serif;
            background: linear-gradient(to bottom right, #fdf7f0, #8e7d63);
            color: #4b3832;
            display: flex;
            flex-direction: column;
            align-items: center;
            height: 100vh;
            overflow: hidden;
            position: relative;
        }
        .card {
            width: 90%;
            max-width: 900px;
            margin: 50px auto;
            background: #ffffff;
            border-radius: 15px;
            box-shadow: 0 20px 30px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            display: flex;
            flex-direction: column;
            align-items: center;
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: translateY(-15px);
            box-shadow: 0 25px 35px rgba(0, 0, 0, 0.25);
        }
        .card-header {
            width: 100%;
            background: linear-gradient(135deg, #d8c3a5, #8e7d63);
            padding: 30px 0;
            text-align: center;
            color: #ffffff;
        }
        .card-header h1 {
            font-size: 2.5em;
            font-weight: bold;
        }
        .profile-section {
            text-align: center;
            margin-top: -80px;
            animation: fadeIn 1s ease-in-out;
        }
        .profile-section img {
            border-radius: 50%;
            border: 8px solid #ffffff;
            width: 160px;
            height: 160px;
            transition: transform 0.3s ease;
        }
        .profile-section img:hover {
            transform: scale(1.15);
        }
        .profile-section h2 {
            margin-top: 15px;
            font-size: 1.8em;
            color: #4b3832;
            font-weight: bold;
        }
        .profile-section p {
            max-width: 600px;
            margin: 10px auto;
            font-size: 1em;
            color: #6d4c41;
            line-height: 1.8;
        }
        .skills-section {
            width: 100%;
            background: #f5ebe0;
            padding: 30px 20px;
            text-align: center;
            animation: slideUp 1s ease-in-out;
        }
        .skills-section h3 {
            color: #4b3832;
            font-size: 1.8em;
            margin-bottom: 20px;
            font-weight: bold;
        }
        .skills-list {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
        }
        .skills-list span {
            display: inline-block;
            padding: 10px 20px;
            background: #d8c3a5;
            border-radius: 20px;
            font-size: 1em;
            color: #4b3832;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            font-weight: bold;
            transition: transform 0.2s ease;
        }
        .skills-list span:hover {
            transform: scale(1.1);
        }
        .contact-section {
            width: 100%;
            padding: 30px 20px;
            background: #8e7d63;
            color: #ffffff;
            text-align: center;
            animation: fadeIn 1s ease-in-out;
        }
        .contact-section h3 {
            font-size: 1.8em;
            margin-bottom: 20px;
            font-weight: bold;
        }
        .contact-links a {
            display: inline-block;
            margin: 0 10px;
            padding: 10px 20px;
            background: #4b3832;
            color: #ffffff;
            border-radius: 20px;
            text-decoration: none;
            font-size: 1em;
            transition: background 0.3s, transform 0.2s;
            font-weight: bold;
        }
        .contact-links a:hover {
            background: #6d4c41;
            transform: scale(1.1);
        }
        .contact-links a:active {
            transform: scale(0.9);
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        @keyframes slideUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="card-header">
            <h1></h1>
        </div>
        <div class="profile-section">
            <img src="https://i.ibb.co/jWWB6ZN/photo-2024-08-27-04-40-14.jpg" alt="">
            <h2> </h2>
            <p>Hi, My name is omgsmok , i’m a penetration tester with strong background on Web,Mobile,Network,Source Code Review,Thick Client,Red Teaming. Throughtout the past 3 year i have found security issues on various companies at work and as well on bug bounties.</p>
        </div>
        <div class="skills-section">
            <h3> skills </h3>
            <div class="skills-list">
                <span>HTML & CSS</span>
                <span>JavaScript</span>
                <span>React.js</span>
                <span>Node.js</span>
                <span>Python</span>
                <span>SQL</span>
                <span>TypeScript</span>
                <span>UI/UX Design</span>
                <span>Agile Development</span>
            </div>
        </div>
        <div class="contact-section">
            <h3>تواصل</h3>
            <div class="contact-links">
                <a href="https://www.instagram.com/omgsmok"> instagram </a>
                <a href="https://t.me/omgsmok"> Telegram </a>
                <a href="https://twitter.com/omgsmok"> Twitter </a>
            </div>
        </div>
    </div>
</body>
</html>
