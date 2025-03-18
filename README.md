# CV
PDF embebido dentro de una página web (Estrucura basica de HTML)
**********************************
Opción 1
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi CV</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f4f4f4;
            font-family: Arial, sans-serif;
        }
        embed {
            width: 80%;
            height: 90vh;
            border: 1px solid #ccc;
        }
    </style>
</head>
<body>
    <h1>Nicolás García Peñaloza</h1>
    <embed src="Nicolás_García_Peñaloza_CV.pdf" type="application/pdf">
</body>
</html>

*********************************

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi CV</title>
    <style>
        body {
            background: linear-gradient(to right, #4facfe, #00f2fe);
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
        }
        embed {
            width: 80%;
            height: 90vh;
            border: 2px solid white;
            border-radius: 10px;
        }
        .download-btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: white;
            color: #4facfe;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
            font-weight: bold;
        }
        .download-btn:hover {
            background-color: #f1f1f1;
        }
    </style>
</head>
<body>
    <h1>Nicolás García Peñaloza</h1>
    <embed src="Nicolás_García_Peñaloza_CV.pdf" type="application/pdf">
    <br>
    <a class="download-btn" href="CV.pdf" download>Descargar CV</a>
</body>
</html>

************************************************************************
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi CV</title>
    <style>
        body {
            background-color: #eceff1;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .cv-container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
        }
        embed {
            width: 100%;
            height: 500px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="cv-container">
        <h1>Nicolás García Peñaloza</h1>
        <embed src="Nicolás_García_Peñaloza_CV.pdf" type="application/pdf">
    </div>
</body>
</html>

*******************************************************

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi CV</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
            background-color: #f4f4f4;
        }
        embed {
            width: 80%;
            height: 90vh;
            border: 2px solid #333;
        }
    </style>
</head>
<body>
    <h1>Nicolás García Peñaloza</h1>
    <embed src="Nicolás_García_Peñaloza_CV.pdf" type="application/pdf">
</body>
</html>

