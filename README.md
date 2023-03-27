![enter image description here](https://raw.githubusercontent.com/sergiecode/css-marker-tutorial/master/css-marker-tutorial.jpg)


# Tutorial de uso del pseudoelemento `::marker` en CSS

Este tutorial te mostrará cómo usar el pseudoelemento `::marker` en CSS para personalizar el estilo de los marcadores de lista en tu sitio web.

## ¿Qué es el pseudoelemento `::marker`?

El pseudoelemento `::marker` es un selector CSS que te permite aplicar estilos personalizados a los marcadores de lista (`<li>`). Esto significa que puedes cambiar la apariencia de los marcadores de lista en tu sitio web, en lugar de tener que conformarte con los estilos predeterminados del navegador.

## Ejemplo de uso

Para usar el pseudoelemento `::marker`, debes seleccionar el elemento `<li>` y luego aplicar estilos a su pseudoelemento `::marker`. Por ejemplo, si quieres cambiar el color de los marcadores de lista a rojo, puedes hacer lo siguiente:

    li::marker {
      color: red;
    }

También puedes aplicar estilos adicionales al pseudoelemento `::marker`, como el tamaño de fuente, el peso de fuente y el contenido. Por ejemplo:

    li::marker {
      content: "🔥";
      font-size: 24px;
      font-weight: bold;
      color: orange;
    }

## Compatibilidad del navegador

El pseudoelemento `::marker` es compatible con la mayoría de los navegadores modernos, incluidos Chrome, Firefox, Safari y Edge. Sin embargo, algunos navegadores más antiguos no lo admiten, como Internet Explorer.

## Conclusión

Usar el pseudoelemento `::marker` en CSS te permite personalizar los marcadores de lista en tu sitio web. Es fácil de usar y es compatible con la mayoría de los navegadores modernos. ¡Prueba diferentes estilos para agregar un toque personal a tus listas!
