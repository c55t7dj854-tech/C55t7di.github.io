<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>my cozy autumn corner 🍂</title>
    <style>
        /* Autumn aesthetic colors and styling */
        body {
            background-color: #f5ebe0; /* Cozy cappuccino beige */
            color: #4a2810; /* Dark chocolate brown text */
            font-family: 'Courier New', Courier, monospace; /* Classic typewriter girlblog font */
            text-align: center;
            padding: 20px 15px;
            margin: 0;
            overflow-x: hidden;
        }

        /* Main website container */
        .container {
            background: #ffffff;
            padding: 25px 20px;
            border-radius: 20px;
            box-shadow: 0px 8px 25px rgba(92, 64, 50, 0.12);
            max-width: 100%;
            box-sizing: border-box;
            border: 2px dashed #b5651d; /* Dashed autumn border */
            position: relative;
            z-index: 10;
        }

        h1 { 
            color: #bc6c25; /* Soft autumn orange */
            font-size: 24px;
            margin-top: 10px;
        }

        .emoji-line {
            font-size: 22px;
            margin-bottom: 20px;
            letter-spacing: 5px;
        }

        /* Blog posts styling */
        .post {
            background: #fdf8f5;
            padding: 18px;
            margin-top: 20px;
            border-radius: 12px;
            text-align: left; /* Aligned to the left for English */
            border-left: 5px solid #dda15e; /* Warm side border */
            box-shadow: 0px 3px 10px rgba(0,0,0,0.02);
        }

        .post h3 {
            margin: 0 0 8px 0;
            color: #87431d;
            font-size: 19px;
        }

        .post p {
            font-size: 15px;
            line-height: 1.6;
            margin: 0;
        }

        .post small {
            color: #a0816c;
            display: block;
            margin-top: 10px;
            font-size: 12px;
        }

        .footer {
            margin-top: 35px;
            font-size: 13px;
            color: #a0816c;
        }

        /* Magical falling autumn leaves effect */
        .leaf {
            position: fixed;
            top: -20px;
            font-size: 24px;
            animation: fall linear infinite;
            z-index: 1;
            pointer-events: none;
        }

        @keyframes fall {
            0% { transform: translateY(0) rotate(0deg); opacity: 1; }
            100% { transform: translateY(100vh) rotate(360deg); opacity: 0; }
        }
    </style>
</head>
<body>

    <!-- Falling leaves in the background -->
    <div class="leaf" style="left: 8%; animation-duration: 6s;">🍂</div>
    <div class="leaf" style="left: 28%; animation-duration: 8s;">🍁</div>
    <div class="leaf" style="left: 48%; animation-duration: 5s;">🍂</div>
    <div class="leaf" style="left: 68%; animation-duration: 7s;">🍁</div>
    <div class="leaf" style="left: 88%; animation-duration: 6s;">🍂</div>

    <!-- Main blog content -->
    <div class="container">
        <h1>welcome to my autumn corner 🤎 ✨</h1>
        <div class="emoji-line">☕ 🥧 🧸 🕯️ 🧦</div>
        
        <p>welcome to my safe space programmed fully from my phone. here i share my daily thoughts, reading lists, and cozy autumn vibes.</p>
        
        <!-- First Blog Post -->
        <div class="post">
            <h3>🍂 entry #01: hello world!</h3>
            <p>welcome to my new autumn girlblog! i created and designed this entire website from scratch using my phone on github pages. it feels so warm and cozy here!</p>
            <small>📅 published: august 29, 2026</small>
        </div>

        <!-- Second Blog Post -->
        <div class="post">
            <h3>📖 autumn reading rituals</h3>
            <p>the best feeling in this season is lighting a warm vanilla candle, making a hot cup of cocoa, and reading a classic book while listening to the rain outside.</p>
            <small>📅 published: august 29, 2026</small>
        </div>
    </div>

    <div class="footer">
        made with love by a girlblogger 📱 🍁
    </div>

</body>
</html>
