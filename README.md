<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" type="text/css" href="style2.css">
    <title>bton11</title>
</head>
<body>
    <button class="boton" style="--clr:#1e9bff"><span>boton</span><i></i></button>
<button class="boton" style="--clr:#1e9bff"><span>boton</span><i></i></button>
<button class="boton" style="--clr:#1e9bff"><span>boton</span><i></i></button>
</body>
<footer>
    <P>HECHO POR: ADRIAN 90% Y LUIS 10%(HIZO QUE FUERA BOTON XD) Y SUGERENCIA DE FONDO POR JOSUE</P>
</footer>
</html>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300,400,500,600,700,800,900&display=swap');
*
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
}
body
{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #000000;
    flex-direction: column;
    gap: 50px;
}
button
{
    position: relative;
    background: #fff;
    color: #fff;
    color: rgb(250, 249, 249);
    text-decoration: none;
    text-transform: uppercase;
    font-size: 1.5em;
    letter-spacing: 0.1em;
    font-weight: 400;
    padding: 10px 30px;
    transition: 0.5s;
}
button:hover
{
    background: var(--clr);
    color: var(--clr);
    letter-spacing: 0.25em;
    box-shadow: 0 0 35px;
}
button:before
{
    content: '';
    position: absolute;
    inset: 2px;
    background: #27282c;
}
button span
{
    position: relative;
    z-index: 1;
}
button i
{
    position: absolute;
    inset: 0;
    display: block;
}
button i::before
{
    content: '';
    position: absolute;
    top: 0;
    left: 80%;
    width: 10px;
    height: 4px;
    background: #27282c;
    transform: translate(-50%) skewX(325deg);
    transition: 0.5s;
}
button:hover i::before
{
    width: 20px;
    left: 20%;
}

button i::after
{
    content: '';
    position: absolute;
    bottom: 0;
    left: 20%;
    width: 10px;
    height: 4px;
    background: #27282c;
    transform: translate(-50%) skewX(325deg);
    transition: 0.5s;
}
button:hover i::after
{
    width: 20px;
    left: 80%;
}

p{
    color: rgb(241, 239, 239);
}
