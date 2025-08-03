# Dog
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dog to Cute Human</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #fce4ec;
            margin: 0;
        }

        .container {
            position: relative;
            width: 300px;
            height: 300px;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }

        img {
            position: absolute;
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: opacity 2s ease-in-out;
        }

        #human {
            opacity: 0;
        }

        .container:hover #human {
            opacity: 1;
        }

        .container:hover #dog {
            opacity: 0;
        }

        h2 {
            position: absolute;
            bottom: 10px;
            width: 100%;
            text-align: center;
            color: white;
            text-shadow: 0 0 10px black;
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Replace these image URLs with your own -->
        <img id="dog" src="dog.jpg" alt="Dog">
        <img id="human" src="cute-human.jpg" alt="Cute Human">
        <h2>Dog → Cute Human</h2>
    </div>

</body>
</html>
