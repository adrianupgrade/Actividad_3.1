# Proyecto HTML y CSS

Este proyecto consiste en la creación de un archivo `index.html` y un archivo de estilos `estilos.css` para mostrar una tabla de precios.

## index.html

El archivo `index.html` contiene la estructura básica de un documento HTML. Incluye una tabla con los precios de diferentes temporadas y meses.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="estilos.css">
</head>
<body>
    <h1>PRECIOS</h1>
    <table>
        <tr>
            <th>TEMPORADA</th>
            <th>MES</th>
            <th>PRECIO</th>
        </tr>
        <tr>
            <td>MEDIA</td>
            <td>JUNIO</td>
            <td>60€</td>
        </tr>
        <tr>
            <td rowspan="2">ALTA</td>
            <td>JULIO</td>
            <td>70€</td>
        </tr>
        <tr>
            <td>AGOSTO</td>
            <td class="amarillo">80€</td>
        </tr>
        <tr>
            <td>MEDIA</td>
            <td colspan="2">70€</td>
        </tr>
    </table>
</body>
</html>
```

## estilos.css

El archivo `estilos.css` contiene los estilos para el documento HTML. Define la apariencia del texto, la tabla y sus celdas.

```css
body {
    text-align: center;
    font-family: Arial, sans-serif;
}

h1 {
    color: red;
    font-weight: bold;
}

table {
    width: 50%;
    margin: auto;
    border-collapse: collapse;
    border: 3px solid black;
}

th, td {
    border: 3px solid black;
    padding: 10px;
    text-align: center;
}

th {
    background-color: cyan;
}

.amarillo {
    background-color: yellow;
}
```

## Descripción

- **HTML**: Define la estructura del contenido, incluyendo una tabla con varias filas y columnas.
- **CSS**: Aplica estilos al contenido HTML, como la alineación del texto, colores de fondo y bordes de la tabla.

Este proyecto muestra cómo combinar HTML y CSS para crear una página web simple y estilizada.