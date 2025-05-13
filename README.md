
# Auto Corregir Textos

**Auto Corregir Textos** es una herramienta creada para limpiar textos eliminando caracteres especiales invisibles que suelen quedar tras el uso de inteligencias artificiales o procesadores de texto. Su objetivo es entregar un contenido más limpio, compatible y natural para cualquier plataforma.

---

## ¿Cómo funciona la página?

1. **Pega** tu texto en el área principal.
2. **Corregir Texto**: Limpia automáticamente los caracteres invisibles y espacios anómalos.
3. **Visualizar Caracteres**: Resalta los caracteres invisibles para su identificación.
4. **Copiar Texto Limpio**: Copia al portapapeles el contenido ya corregido.
5. **Alternar Modo Claro/Oscuro**: Cambia la apariencia de la página para comodidad visual.

---

## ¿Qué son los caracteres especiales invisibles?

Son símbolos que, aunque no se ven a simple vista, están presentes en un texto y pueden influir en su comportamiento. Muchos de ellos son introducidos por herramientas de inteligencia artificial, editores de texto o sistemas de codificación.

### Importancia de eliminarlos

- Evitar delatar la generación artificial de textos.
- Asegurar compatibilidad entre distintas plataformas y programas.
- Mejorar la limpieza y profesionalismo del contenido.

La página resalta los caracteres invisibles de la siguiente forma:
- **Rojo:** Carácter potencialmente problemático (marcas típicas de IA).
- **Azul:** Carácter de formato normal, generalmente inofensivo.

---

## Simbología manejada en la página

| Código Unicode | Nombre                     | Descripción                                      |
| -------------- | --------------------------- | ------------------------------------------------ |
| U+2009         | Thin Space                  | Espacio delgado usado para ajuste estético.       |
| U+00A0         | No-Break Space              | Espacio que evita saltos de línea.                |
| U+200B         | Zero-Width Space            | Separador invisible que no ocupa espacio.         |
| U+200E         | Left-to-Right Mark           | Marca de dirección de texto de izquierda a derecha. |
| U+200F         | Right-to-Left Mark           | Marca de dirección de texto de derecha a izquierda. |
| U+202F         | Narrow No-Break Space       | Espacio angosto que evita salto de línea.         |
| U+FEFF         | Byte Order Mark (BOM)       | Marca de codificación al inicio de archivos.      |

### Ejemplos de Corrección

| Carácter Especial        | Texto con carácter especial | Texto corregido |
| ------------------------- | --------------------------- | --------------- |
| Thin Space (U+2009)        | Hola mundo                   | Hola mundo      |
| No-Break Space (U+00A0)     | Palabra1 Palabra2             | Palabra1 Palabra2 |
| Zero-Width Space (U+200B)   | Texto​Invisible               | TextoInvisible  |
| Narrow No-Break Space (U+202F) | Precio $100                   | Precio $100      |

---

## Agradecimientos

Este proyecto fue desarrollado con el apoyo y la colaboración de **ChatGPT** (OpenAI).  
La asistencia de ChatGPT fue fundamental para diseñar, depurar y perfeccionar tanto el código como la documentación de este proyecto.

¡Gracias por utilizar Auto Corregir Textos!  
Tu contenido se merece la mejor calidad.
