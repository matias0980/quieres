<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>quieres </title>
        <style>
            body{
                background-color: pink;
            }
        </style>
    <script>
        function accioncuandoelladiagaqueSi(){
            alert("ahora ya somos nobios <3")
        }
        function mueveElboton(){
            Width = window.innerWidth;
            heigth = window.innerHeight;

            newWidth=(Math.random() * Width);
            newHeigth =(Math.random() * heigth);

            document.getElementById('btnNo').style.position = "absolute";
            document.getElementById('btnNo').style.left = newWidth + "px";
            document.getElementById('btnNo').style.top = newHeigth + "px";
        }

    </script>
</head>
<body>
    <h3>Quieres ser mi nobia <3?</h3>

    <input type="button" onclick="accioncuandoelladiagaqueSi()" Id="btnSI" value="Si"/>
    <input type="button" id="btnNo" onmouseover="mueveElboton()" value="No"/>
</body>
</html>
              
