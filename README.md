<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KRIMI</title>
    <style>
        body {
            background-color: lightblue;
            font-family: Arial, sans-serif;
        }

        h1 {
            color: navy;
            margin-left: 20px;
        }

        em {
            margin-left: 20px;
            color: darkred;
        }

        button {
            display: inline-block;
            margin-left: 20px;
            padding: 10px 20px;
            font-size: 16px;
            background-color: navy;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: darkblue;
        }
    </style>
</head>
<body>

<h1>KRIMI</h1>
<em>Výtejte na strance KRIMI, tato stranka je dovážejicí služba.</em>
<br>
<button id="myButton">Objednat</button>
</br>
<br>
<Strong>Otevírací doba</Strong>

<script>
    document.getElementById('myButton').addEventListener('click', function() {
        window.open('file:///C:/Users/Michal/Documents/Moje%20S.A.V%20Antivirusy/kontakt.html', '_blank');
    });
</script>

</body>
</html>
