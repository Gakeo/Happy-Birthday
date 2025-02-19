# Happy-Birthday
Plan Maria
<!DOCTYPE html><html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Cumpleaños María</title>
    <style>
        body {
            text-align: center;
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
        }
        img {
            max-width: 80%;
            height: auto;
            border-radius: 10px;
            margin-top: 20px;
        }
        button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 18px;
            border: none;
            background-color: #ff4081;
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #e60073;
        }
    </style>
</head>
<body>
    <h1>🎉 ¡Feliz Cumpleaños María! 🎂</h1>
    <img id="slideImage" src="https://drive.google.com/uc?export=view&id=1-SfGMX8wtYxzLyF6xS9sbNwvbz0dcgoi" alt="Imagen de cumpleaños">
    <br>
    <button onclick="nextImage()">Siguiente</button><script>
    const images = [
        "https://drive.google.com/uc?export=view&id=1-SfGMX8wtYxzLyF6xS9sbNwvbz0dcgoi",
        "https://drive.google.com/uc?export=view&id=1-IxIaOzhpVIHq5qDgQ6U4gwbgIdqc9Zc",
        "https://drive.google.com/uc?export=view&id=1-KUDJx8EpW-Q1frxJ2Kw0hcjnhwGiNMi"
    ];
    let index = 0;
    function nextImage() {
        index = (index + 1) % images.length;
        document.getElementById("slideImage").src = images[index];
    }
</script>

</body>
</html>
