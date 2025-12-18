# 🚀 Guía Rápida: HTML5 & CSS3 (Examen)

Este repositorio contiene los snippets y conceptos clave para resolver ejercicios de maquetación de forma ágil. ¡Éxito en el examen!

---

## 🏗️ 1. Estructura HTML Semántica
Usa etiquetas que describan el contenido para obtener el puntaje completo.

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Examen</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header> </header>
    <nav> </nav>
    <main>
        <section> </section>
        <article> </article>
    </main>
    <footer> </footer>
</body>
</html>
🎨 2. CSS: El Modelo de Caja (Box Model)Margin: Espacio fuera del borde (externo).Border: La línea que rodea el relleno.Padding: Espacio entre el contenido y el borde (interno).Box-sizing: Clave para que el tamaño sea exacto.CSS* {
    box-sizing: border-box; /* El padding no suma al ancho total */
    margin: 0;
    padding: 0;
}
📐 3. Layouts (Alineación)Flexbox (Filas o Columnas)CSS.container {
    display: flex;
    flex-direction: row;     /* O 'column' para vertical */
    justify-content: center; /* Alineación horizontal (eje principal) */
    align-items: center;     /* Alineación vertical (eje secundario) */
    gap: 20px;               /* Espacio entre elementos */
}
CSS Grid (Tablas complejas)CSS.grid-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* 3 columnas iguales */
    gap: 15px;
}
📝 4. Selectores y Propiedades ComunesTipoEjemploNotaElementop { }Afecta a todos los párrafosClase.card { }Se usa con class="card"ID#header { }Único, se usa con id="header"Hoverbutton:hover { }Estilo al pasar el ratón📱

5. Responsividad (Media Queries)Ajusta el diseño según el tamaño de la pantalla.CSS/* Para pantallas móviles (menores a 768px) */
@media (max-width: 768px) {
    .container {
        flex-direction: column;
    }
}
💡 Tips de Último MinutoImágenes: Revisa la ruta, usualmente es src="img/foto.jpg".Fuentes: Si usas Google Fonts, pega el <link> dentro del <head>.F12: Usa el "Inspector de elementos" para ver por qué algo no se alinea.





