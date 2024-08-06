<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Externí CSS Příklad</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>


<h1>KRIMI</h1>
<em>Výtejte na strance KRIMI  tato stranka je dovážejicí služba.</em>
<br>
<button id="myButton">Objednat</button>
</br>

<script>
    document.getElementById('myButton').addEventListener('click', function() {
        window.open('file:///C:/Users/Michal/Documents/Moje%20S.A.V%20Antivirusy/kontakt.html', '_blank');
    });
</script>

</body>
</html>
