# ATATV44
TÜRKİYENİN EN İYİ SUNUCUSU
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ATATV44 | Katıl</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #0a0a0a;
            font-family: 'Inter', sans-serif;
            color: white;
            overflow: hidden;
        }

        .card {
            text-align: center;
            background: rgba(20, 20, 20, 0.8);
            padding: 60px;
            border-radius: 30px;
            border: 1px solid #222;
            box-shadow: 0 0 50px rgba(88, 101, 242, 0.1);
            backdrop-filter: blur(10px);
        }

        h1 {
            font-size: 3rem;
            font-weight: 900;
            margin-bottom: 40px;
            letter-spacing: -1px;
            background: linear-gradient(90deg, #fff, #5865F2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .join-button {
            display: inline-block;
            padding: 18px 50px;
            font-size: 1.3rem;
            font-weight: bold;
            color: white;
            background: #5865F2;
            text-decoration: none;
            border-radius: 15px;
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            box-shadow: 0 10px 20px rgba(88, 101, 242, 0.4);
            text-transform: uppercase;
        }

        .join-button:hover {
            transform: scale(1.05) translateY(-5px);
            box-shadow: 0 15px 30px rgba(88, 101, 242, 0.6);
            background: #4752c4;
        }

        /* Arka plan için hafif bir hareket */
        .bg-glow {
            position: absolute;
            width: 300px;
            height: 300px;
            background: #5865F2;
            filter: blur(150px);
            opacity: 0.15;
            z-index: -1;
            border-radius: 50%;
            animation: move 10s infinite alternate;
        }

        @keyframes move {
            from { transform: translate(-50%, -50%); }
            to { transform: translate(50%, 50%); }
        }
    </style>
</head>
<body>

    <div class="bg-glow"></div>
    
    <div class="card">
        <h1>ATATV44'E KATIL</h1>
        <a href="https://discord.gg/ZbJBqEDEj" class="join-button">Sunucuya Git</a>
    </div>

</body>
</html>
