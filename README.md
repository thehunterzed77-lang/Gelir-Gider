<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Benim Uygulamam</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f5f5;
            color: #222;
        }

        .header {
            background: #111;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .container {
            max-width: 900px;
            margin: 30px auto;
            padding: 20px;
        }

        .card {
            background: white;
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 20px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
        }

        button {
            border: none;
            background: #111;
            color: white;
            padding: 12px 20px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background: #333;
        }
    </style>
</head>

<body>

    <div class="header">
        <h1>Benim Uygulamam</h1>
    </div>

    <div class="container">

        <div class="card">
            <h2>Hoş Geldin 👋</h2>
            <p>Uygulamamızın ana ekranı.</p>

            <button onclick="mesajGoster()">
                Test Et
            </button>
        </div>

    </div>

    <script>
        function mesajGoster() {
            alert("Çalışıyor! 🚀");
        }
    </script>

</body>
</html>
