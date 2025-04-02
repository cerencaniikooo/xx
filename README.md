<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sürpriz!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #fce4ec;
            text-align: center;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            margin-top: 20px;
            background-color: #d81b60;
            border: none;
            color: white;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #ad1457;
        }
        #content {
            display: none;
            margin-top: 20px;
        }
        #content img {
            width: 300px;
            border-radius: 10px;
            margin-top: 10px;
        }
        #message {
            font-size: 20px;
            color: #880e4f;
            margin-top: 10px;
        }
    </style>
</head>
<body>

    <h1>Merhaba Tatlım! ❤️</h1>
    <p>Butona basınca sana özel bir sürpriz var! 😊</p>

    <button onclick="showSurprise()">Sürprizi Gör!</button>

    <div id="content">
        <p id="message">Seni çok seviyorum! 💖</p>
        <img id="surpriseImage" src="(https://github.com/cerencaniikooo/xx/blob/main/C2ABE29B-B84B-4F20-B2E6-F233085E4413_Original.JPG?raw=true)"alt="Sürpriz Fotoğrafı">
    </div>

    <script>
        function showSurprise() {
            document.getElementById("content").style.display = "block";
        }
    </script>

</body>
</html>
