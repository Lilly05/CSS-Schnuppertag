<h1>Schnuppertag Javascript Aufgaben Theorie</h1>

<h2>Was ist Javascript überhaupt?</h2>
Javascript ist wie HTML und CSS eine Sprache für die Web Entwicklung. Diese drei Sprachen sind die Kernsprachen für das Web.<br>
Sie werden aber nicht für das gleiche verwendet.<br><br>
<b>HTML</b> wird für die Struktur einer Webseite verwendet (Text, Bilder u.s.w) und ist KEINE Programmiersprache, sondern eine Auszeichnungssprache <br><br>
<b>CSS</b> wird für das Styling einer Webseite verwendet (Farbe von Text, Hintergrundfarbe u.s.w) und ist ebenfalls KEINE Programmiersprache, sondern eine Stylesheet Sprache <br><br>
<b>Javascript</b> hingegen ist eine Programmiersprache. Ganz genau ist Javascript eine Skriptsprache, aber Skriptsprachen gehören ebenfalls zu den Programmiersprachen.
Mit Javascript kann man Inhalte von einer Webseite bearbeiten, Interaktionen hinzufügen u.s.w
<br><br>
<h2>Wie kann man Javascript verwenden?</h2>
Man kann Javascript Code direkt in einem HTML File schreiben.
Dies sieht dann so aus:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Javascript Aufgaben</title>
</head>
<body>

    <script>
    // Hier kannst du deinen Javascript Code direkt im HTML File zwischen <script>
    Tags schreiben
        console.log("Hello World");
    </script>

</body>
</html>
````

Ebenfalls kann man Javascript File in einem externen File schreiben. Dies verlinkt man dann im HTML Code. <br>Dies sieht dann so aus:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Javascript Aufgaben</title>
</head>
<body>
    <!--Das Javascript File wird eingebunden. Der Javascript Code wird dann im 
    externen .js File geschrieben-->
    <script src="main.js"></script>

</body>
</html>
```

Text im HTML File ausgeben: 
```
document.write("Hello World");
```
Text in der Konsole ausgeben:
```
console.log("Hello World");
```
Weitere Links für Theorie und Hilfe:<br>
<a href="https://www.w3schools.com/js/default.asp">W3schools Javascript</a><br>
<a href="https://www.w3schools.com/js/js_loop_for.asp">For Schleife</a><br>
<a href="https://www.w3schools.com/js/js_functions.asp">Funktionen</a><br>
<a href="https://www.w3schools.com/js/js_intro.asp">HTML Content verändern</a><br>
<a href="https://www.w3schools.com/jsref/met_document_queryselector.asp">HTML Content verändern</a><br>
<a href="https://www.w3schools.com/jsref/prop_html_style.asp">HTML Elemente stylen</a><br>
<a href="https://www.w3schools.com/jsref/met_document_createelement.asp">HTML Element in Javascript erstellen</a><br>
<a href="https://www.w3schools.com/jsref/met_node_appendchild.asp">HTML Element mit Javascript ins HTML File einfügen</a><br>
<a href="https://www.w3schools.com/html/html_forms.asp">HTML Formulare</a><br>
<a href="https://www.w3schools.com/html/html_form_input_types.asp">HTML Formulare Input Typen</a>