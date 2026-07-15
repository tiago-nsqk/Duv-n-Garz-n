# Hola, soy Duván - Tiago 👋

Soy estudiante, enfocado en aprender de la programacion y reforzas los temas de los cuales tengo conocimientos basicos.

## Sobre mí
- soy estudiante del colegio union colombia, del grado 10°.
- Intereses: matematicas, programacion y diseño mecanico.
- Objetivo profesional: mi objetivo es estudiar en el Sena y despues ir a alguna universidad.

## Habilidades
- Lenguajes: HTML, CSS, JavaScript, Python (conocimientos basicos)
- Herramientas: VS Code.

## Proyectos destacados
- Proyecto 1: Soy constructor del equipo Uctikray, competidor de la FLL.

## Contacto
- Email: Nesquik3883m@gmail.com
- telefono: 3165164598


<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mini juego</title>
  <style>
    body { font-family: Arial; text-align: center; padding: 40px; }
    button { padding: 10px 20px; font-size: 18px; cursor: pointer; }
  </style>
</head>
<body>
  <h1>Adivina el número</h1>
  <p>Elige un número del 1 al 5</p>
  <button onclick="jugar(1)">1</button>
  <button onclick="jugar(2)">2</button>
  <button onclick="jugar(3)">3</button>
  <button onclick="jugar(4)">4</button>
  <button onclick="jugar(5)">5</button>
  <p id="resultado"></p>

  <script>
    const secreto = 3;
    function jugar(num) {
      document.getElementById("resultado").textContent =
        num === secreto ? "¡Ganaste!" : "Intenta otra vez";
    }
  </script>
</body>
</html>
