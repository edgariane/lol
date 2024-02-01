<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Deine Website</title>
    <style>
        body {
            background-color: #000;
            color: #ddd;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            overflow: hidden; /* Verhindert das Scrollen, wenn das GIF größer als der Bildschirm ist */
        }
      #gifContainer {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1; /* Platziert das GIF hinter den Inhalt */
        }
      #content {
            position: relative;
            z-index: 1; /* Platziert den Inhalt über dem GIF */
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <div id="gifContainer">
        <img src="steamuserimages-a.akamaihd.gif" alt="LOL sheint so als hättest du scheiß Internet">
    </div>
  <div id="content">
        <!-- Inhalt deiner ersten Seite -->
        <h1>Willkommen auf deiner Website</h1>
        <p>Hier steht dein Text.</p>
    </div>
</body>
</html>
