<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maaf Sayang - Versi Romantis</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background: linear-gradient(to bottom, #ffe6e6, #ffb3ba);
            color: #333;
            padding: 50px;
            overflow: hidden;
            position: relative;
        }
        h1 {
            color: #ff4d4d;
            font-size: 3em;
            animation: fadeIn 2s ease-in;
        }
        p {
            font-size: 20px;
            margin: 20px 0;
            animation: slideUp 1.5s ease-out;
        }
        .hearts {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
        }
        .heart {
            position: absolute;
            color: #ff4d4d;
            font-size: 2em;
            animation: fall 5s linear infinite;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideUp {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        @keyframes fall {
            from { transform: translateY(-100vh); }
            to { transform: translateY(100vh); }
        }
        img {
            max-width: 300px;
            border-radius: 15px;
            margin: 20px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        button {
            background-color: #ff4d4d;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 18px;
            border-radius: 25px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #cc0000;
        }
        #message {
            margin-top: 20px;
            font-size: 18px;
            color: #ff4d4d;
        }
    </style>
</head>
<body>
    <div class="hearts">
        <!-- Hati jatuh animasi -->
        <div class="heart" style="left: 10%; animation-delay: 0s;">❤️</div>
        <div class="heart" style="left: 20%; animation-delay: 1s;">💖</div>
        <div class="heart" style="left: 30%; animation-delay: 2s;">❤️</div>
        <div class="heart" style="left: 40%; animation-delay: 3s;">💖</div>
        <div class="heart" style="left: 50%; animation-delay: 4s;">❤️</div>
        <div class="heart" style="left: 60%; animation-delay: 5s;">💖</div>
        <div class="heart" style="left: 70%; animation-delay: 6s;">❤️</div>
        <div class="heart" style="left: 80%; animation-delay: 7s;">💖</div>
        <div class="heart" style="left: 90%; animation-delay: 8s;">❤️</div>
    </div>

    <h1>sayangkuu semangat yaa ngejalanin hari harinya!!💖</h1>
    <p>maaf yaa kalau aku suka marah", suka ngediemin kamu atau ngga perduli sama kamuu, tapi sebenernya aku sayang kok sama kamu cantik💕</p>
    <img src="https://media.discordapp.net/attachments/841239420630728714/1462389346513453097/image.png?ex=696e03b6&is=696cb236&hm=560192c93fe7f8389c7371004ed8e50dee2f9697095b17b3a3e128c4125d6fdd&=&format=webp&quality=lossless" alt="Foto romantis kamu berdua"> <!-- Ganti dengan foto kamu sendiri -->
    <p>Klik tombol di bawah kalau sayang sama aku:</p>
    <button onclick="showMessage()">SAYANG NGGA?!</button>
    <p id="message"></p>

    <!-- Musik latar (autoplay, tapi bisa dimatikan di browser) -->
    <audio autoplay loop>
        <source src="https://soundcloud.com/fm_freemusic/playful-mood-bouncy-fun-happy-and-positive-track-by-oleg-mazur-free-download?si=da0323d629d34ca1a181b51d9ea5ba96&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" type="audio/wav"> <!-- Ganti dengan lagu romantis kamu, misal upload ke SoundCloud -->
    </audio>

    <script>
        function showMessage() {
            document.getElementById('message').innerHTML = "Aku sayang kamu I LOVE YOU! 😘💕";
        }
    </script>
</body>
</html>
