<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Click Reveal</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 100px;
            background-color: #f2f2f2;
        }

        #content {
            display: none;
            font-size: 40px; /* font besar */
            font-weight: bold;
            color: #222;
            margin-top: 50px;
        }

        button {
            padding: 15px 30px;
            font-size: 20px;
            cursor: pointer;
            border: none;
            background-color: #333;
            color: white;
            border-radius: 10px;
        }

        button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

    <button onclick="showContent()">Klik di sini</button>

    <div id="content">
        TENGOK PA TOH ANG
    </div>

    <script>
        function showContent() {
            document.getElementById("content").style.display = "block";
        }
    </script>

</body>
</html>
