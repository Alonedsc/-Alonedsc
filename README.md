<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kawaii Neko Girl Profile</title>
    <style>
        body {
            background-color: #fdf3f8;
            font-family: 'Arial', sans-serif;
            text-align: center;
            padding: 0;
            margin: 0;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        h1, h2 {
            color: #ff82a9;
        }

        .neko-girl {
            background: linear-gradient(135deg, #ffd1dc, #e0e0e0);
            border-radius: 10px;
            display: inline-block;
            padding: 20px;
            width: 300px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            position: relative;
        }

        .neko-girl img {
            width: 100%;
            border-radius: 10px;
        }

        .neko-ears {
            position: absolute;
            top: -25px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            justify-content: center;
        }

        .ear {
            width: 30px;
            height: 40px;
            background-color: #ff80a3;
            border-radius: 50%;
            margin: 0 5px;
        }

        .ear.left {
            transform: rotate(-30deg);
        }

        .ear.right {
            transform: rotate(30deg);
        }

        .heart {
            font-size: 20px;
            color: #ff82a9;
        }

        .neko-girl-name {
            font-size: 1.5em;
            color: #ff5080;
            margin-top: 10px;
        }

        .neko-girl-description {
            font-size: 1.1em;
            color: #b4a6a6;
            margin-top: 10px;
        }

        .buttons a {
            text-decoration: none;
            background-color: #ff82a9;
            padding: 10px 20px;
            border-radius: 20px;
            color: white;
            font-weight: bold;
            margin: 10px;
        }

        .buttons a:hover {
            background-color: #ff5080;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Meet the Kawaii Neko Girl!</h1>
    <div class="neko-girl">
        <div class="neko-ears">
            <div class="ear left"></div>
            <div class="ear right"></div>
        </div>
        <img src="https://www.example.com/cute-kawaii-image.jpg" alt="Kawaii Neko Girl">
        <div class="neko-girl-name">mIcHy AmRaNe</div>
        <div class="neko-girl-description">IT student based in Paris, Cat lover, and everything cute!</div>

        <div class="buttons">
            <a href="https://twitter.com/michyamrane" target="_blank">Follow on Twitter</a>
            <a href="https://www.youtube.com/channel/UCJ6BqQI-EEJUWEl7SdzeD_Q" target="_blank">Watch on YouTube</a>
        </div>
    </div>

    <h2>💖 Kawaii Stats 💖</h2>
    <p><span class="heart">💖</span> Neko Girl Stats Coming Soon!</p>
</div>

</body>
</html>
