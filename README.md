# Fusion
Fusion est un réseau social innovant qui permet de partager des moments uniques avec des amis, en s'inspirant du design moderne de Snapchat. Découvrez une interface fluide, des stories captivantes et interagissez avec vos proches en un clic."
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Fusion - Share Your Moments</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: #000;
            color: #FFFC00;
            overflow: hidden;
        }
        header {
            background: linear-gradient(90deg, #FFFC00, #FFBF00);
            color: #000;
            padding: 20px;
            text-align: center;
            font-size: 2rem;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            height: calc(100vh - 70px);
            overflow-y: auto;
            scrollbar-width: none;
            -ms-overflow-style: none;
        }
        .container::-webkit-scrollbar {
            display: none;
        }
        .snap {
            background: rgba(255, 255, 255, 0.1);
            width: 90%;
            max-width: 400px;
            border-radius: 20px;
            box-shadow: 0 4px 15px rgba(255, 252, 0, 0.4);
            margin: 15px 0;
            padding: 20px;
            backdrop-filter: blur(10px);
            transition: transform 0.2s;
        }
        .snap:hover {
            transform: scale(1.05);
        }
        .snap img {
            width: 100%;
            border-radius: 15px;
            border: 2px solid #FFFC00;
        }
        .snap p {
            margin: 15px 0 10px;
            font-size: 1.2rem;
            text-align: center;
        }
        .snap button {
            background: #FFFC00;
            color: #000;
            border: none;
            padding: 10px 25px;
            border-radius: 25px;
            cursor: pointer;
            font-size: 1rem;
            display: block;
            margin: 10px auto 0;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
            transition: background 0.2s, transform 0.2s;
        }
        .snap button:hover {
            background: #FFBF00;
            transform: translateY(-3px);
        }
    </style>
</head>
<body>
    <header>Fusion - Share Your Moments</header>
    <div class="container">
        <div class="snap">
            <img src="https://via.placeholder.com/350x150" alt="Story">
            <p>John's Adventure in the Mountains</p>
            <button>Reply</button>
        </div>
        <div class="snap">
            <img src="https://via.placeholder.com/350x150" alt="Story">
            <p>Lisa's New Pet</p>
            <button>Reply</button>
        </div>
        <div class="snap">
            <img src="https://via.placeholder.com/350x150" alt="Story">
            <p>Mark's Cooking Skills</p>
            <button>Reply</button>
        </div>
    </div>
</body>
</html>
