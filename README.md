<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ReFlexz</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Raleway:wght@300&display=swap');

        body {
            font-family: 'Raleway', sans-serif;
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(45deg, #0f0c29, #302b63, #24243e, #4a00e0, #8e2de2, #000428, #004e92);
            background-size: 400% 400%;
            animation: gradientBackground 20s ease infinite;
            border: none;
            box-sizing: border-box;
        }

        @keyframes gradientBackground {
            0% { background-position: 0% 50%; background-color: rgba(255, 0, 0, 0.8); }
            25% { background-position: 25% 50%; background-color: rgba(255, 128, 128, 0.8); }
            50% { background-position: 50% 50%; background-color: rgba(128, 0, 128, 0.8); }
            75% { background-position: 75% 50%; background-color: rgba(75, 0, 130, 0.8); }
            100% { background-position: 100% 50%; background-color: rgba(255, 0, 0, 0.8); }
        }

        .container {
            text-align: center;
            background: rgba(0, 0, 0, 0.7);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
        }

        .container img {
            border-radius: 50%;
            width: 100px;
            height: 100px;
        }

        .container h1, .container p {
            color: #fff;
            text-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        .link {
            display: block;
            background: linear-gradient(45deg, #ff0099, #493240, #1f4037, #00c6ff, #0072ff, #4a00e0, #8e2de2);
            background-size: 400% 400%;
            animation: gradientButton 10s ease infinite;
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            margin: 10px 0;
            border-radius: 5px;
            transition: transform 0.3s, box-shadow 0.3s;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
        }

        @keyframes gradientButton {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .link:hover {
            transform: scale(1.05);
            box-shadow: 0 0 20px rgba(255, 0, 128, 0.7);
        }

        .link img {
            width: 20px;
            height: 20px;
            vertical-align: middle;
            margin-right: 8px;
        }

        .youtube-stats {
            color: #fff;
            text-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src='https://i.postimg.cc/HLWLxy6R/Screenshot-2024-0616-191819.jpg' border='0' alt=''/>
        <h1>ReFlexz</h1>
        <p>ช่องทางทั้งหมด😘 อย่าลืมชื้อเสื้อไม่งั้นจะตามไปบ้าน😡</p>
        <a class="link" href="https://youtube.com/@reflexzsama?si=lCTcXWeGi0Qk2ZKq"><img src="https://img.icons8.com/ios-filled/50/ffffff/youtube-play.png" alt="YouTube">ช่องยูทูป</a>
        <a class="link" href="https://www.roblox.com/th/groups/34202684/KaKGrean-Group#!/about"><img src="https://img.icons8.com/ios-filled/50/ffffff/roblox.png" alt="Roblox Group">กลุ่มขายเสื้อ</a>
        <a class="link" href="https://www.roblox.com/th/users/3616268238/profile"><img src="https://img.icons8.com/ios-filled/50/ffffff/roblox.png" alt="Roblox Profile">user หลัก</a>
        <a class="link" href="https://discord.com/invite/mdWqDcJVn5"><img src="https://img.icons8.com/ios-filled/50/ffffff/discord-logo.png" alt="Discord">discord</a>
        <a class="link" href="https://easydonate.app/ReFx505"><img src="https://img.icons8.com/ios-filled/50/ffffff/money.png" alt="Donate">donate 2 บาท ขึ้นจอ</a>
        <a class="link" href="https://www.roblox.com/th/games/17252994471/ReFlexz-Commission-Robux"><img src="https://img.icons8.com/ios-filled/50/ffffff/game-controller.png" alt="Game">แมพที่สร้าง😘</a>        
        <div class="youtube-stats" id="youtube-stats">            
        </div>
    </div>
</body>
</html>
