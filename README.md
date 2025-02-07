<!DOCTYPE html>
<html>
<head>
    <title>Yo Mr. White! | Jesse's Crazy Page</title>
    <style>
        body {
            background: linear-gradient(45deg, #ff69b4, #ffd700);
            font-family: 'Comic Sans MS', cursive;
            text-align: center;
            margin: 0;
            padding: 20px;
            overflow-x: hidden;
        }
        
        .title {
            font-family: 'Bangers', cursive;
            font-size: 4em;
            text-shadow: 3px 3px 0 #ffd700, -3px -3px 0 #ff0000;
            animation: shake 0.5s infinite;
            color: #333;
            margin: 20px 0;
            border: 5px dashed #000;
            padding: 15px;
        }

        .jesse-img {
            border: 10px solid #fff;
            border-radius: 50%;
            box-shadow: 0 0 30px #ff0000;
            transform: rotate(5deg);
            margin: 20px;
            transition: transform 0.3s;
        }

        .jesse-img:hover {
            transform: rotate(-5deg) scale(1.1);
        }

        .marquee {
            background: #000;
            color: #fff;
            padding: 10px;
            font-size: 1.5em;
            margin: 20px 0;
            border: 3px solid #ffd700;
        }

        .insta-link {
            font-size: 2em;
            text-decoration: none;
            color: #ff0000;
            animation: glow 1s infinite alternate;
            display: block;
            margin: 20px;
            font-weight: bold;
        }

        .insta-link:hover {
            color: #ff69b4;
        }

        @keyframes shake {
            0% { transform: translateX(0); }
            25% { transform: translateX(-5px); }
            75% { transform: translateX(5px); }
            100% { transform: translateX(0); }
        }

        @keyframes glow {
            from { text-shadow: 0 0 10px #ff0000; }
            to { text-shadow: 0 0 20px #ffd700, 0 0 30px #ff0000; }
        }

        .crazy-text {
            font-size: 1.2em;
            transform: rotate(-3deg);
            background: #fff;
            display: inline-block;
            padding: 10px 20px;
            margin: 10px;
            border: 3px solid #000;
        }

        .floating-emoji {
            position: absolute;
            font-size: 2em;
            animation: float 5s infinite linear;
        }

        @keyframes float {
            0% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-100px) rotate(180deg); }
            100% { transform: translateY(0) rotate(360deg); }
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Bangers&display=swap" rel="stylesheet">
</head>
<body>
    <h1 class="title">ITS, SCIENCE! 🧪🔥</h1>

    <marquee class="marquee" behavior="alternate" scrollamount="15">
        ⚗️❌ DON'T MESS WITH THE BEST! ❌⚗️
    </marquee>

    <img src="https://i.imgur.com/5yYVhXK.png" alt="Jesse Pinkman" class="jesse-img" width="300">

    <div class="crazy-text">WIRE-FREE SINCE '08!</div>
    <div class="crazy-text" style="transform: rotate(5deg);">CHEMISTRY ROCKS!</div>

    <a href="https://www.instagram.com/kunalverma_2?igsh=bDV6bjB3aTN6a2lv" class="insta-link" target="_blank">
        📸 FOLLOW MY INSTA!  @MY_INSTA
    </a>

    <div style="position: fixed; top: 50px; left: 0; transform: rotate(-15deg);">
        🧨
    </div>
    <div style="position: fixed; top: 100px; right: 0; transform: rotate(15deg);">
        💣
    </div>

    <marquee class="marquee" direction="up" height="100" scrollamount="5">
        ❗️WARNING: <br>MAD SCIENTIST <br>AT WORK❗️
    </marquee>

    <blockquote style="border-left: 5px solid #ff0000; padding: 10px; margin: 20px; background: #fff;">
        "Yo, you got a problem with authority, Mr. White?<br>
        You are the authority!"<br>
        - Jesse Pinkman
    </blockquote>

    <div class="floating-emoji" style="left: 10%">💥</div>
    <div class="floating-emoji" style="left: 30%">🔥</div>
    <div class="floating-emoji" style="left: 50%">☢️</div>
    <div class="floating-emoji" style="left: 70%">💉</div>
    <div class="floating-emoji" style="left: 90%">🧪</div>

</body>
</html>
