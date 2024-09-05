<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hi, All. ✏️Welcome to my 🌱portfolio!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em;
            text-align: center;
        }
        h1 {
            margin: 0;
            font-size: 2em;
        }
        h2 {
            margin: 0.5em 0;
            font-size: 1.5em;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .columns {
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            gap: 10px;
            background: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .column {
            padding: 10px;
        }
        .column h3 {
            margin-top: 0;
            font-size: 1.2em;
            border-bottom: 1px solid #ddd;
            padding-bottom: 10px;
        }
        .column p {
            margin: 10px 0;
        }
        footer {
            text-align: center;
            padding: 1em;
            background-color: #333;
            color: #fff;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Hi, All. ✏️Welcome to my 🌱portfolio!</h1>
    </header>
    
    <div class="container">
        <h2>Data Analytics</h2>
        
        <div class="columns">
            <div class="column">
                <h3>Project Name</h3>
                <p>Project 1</p>
                <p>Project 2</p>
                <p>Project 3</p>
            </div>
            <div class="column">
                <h3>Skills & Tools</h3>
                <p>Python, SQL</p>
                <p>Excel, Tableau</p>
                <p>BigQuery, R</p>
            </div>
            <div class="column">
                <h3>Description</h3>
                <p>Brief description of Project 1</p>
                <p>Brief description of Project 2</p>
                <p>Brief description of Project 3</p>
            </div>
        </div>
    </div>
    
    <footer>
        <p>&copy; 2024 Tu Nombre</p>
    </footer>
</body>
</html>
