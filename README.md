# Laboratorio 1 – Desarrollo Web  

Este repositorio contiene las respuestas y ejercicios correspondientes al **Laboratorio 1 de la asignatura de Desarrollo Web**.  

---

## Preguntas de la guía  

### Pregunta 7  
**Enunciado:**  
> Actualice la página en su navegador y pregúntese:  
> ¿Hay cambios en la visualización del sitio web?  
> Si la respuesta es negativa, piense un momento: ¿Para qué sirven las etiquetas `<meta>`?

**Respuesta:**  
No, no se observan cambios en la visualización.  
Esto ocurre porque las etiquetas `<meta>` no modifican directamente el contenido visible de la página, sino que proporcionan **metadatos** sobre el sitio web.  

Estos metadatos son utilizados por:  
- **Navegadores:** para determinar cómo mostrar o renderizar la página.  
- **Motores de búsqueda (SEO):** para indexar y comprender mejor el contenido del sitio.  
- **Redes sociales:** para mostrar títulos, descripciones e imágenes al compartir la página.  

En resumen, las etiquetas `<meta>` son esenciales para la **compatibilidad, accesibilidad, posicionamiento y usabilidad**, aunque no produzcan cambios visuales inmediatos.  

---

### Pregunta 9  
**Enunciado:**  
> Asegúrese de entender el valor del atributo src de la etiqueta img.
> ¿Qué pasaría si la imagen esta guardada en la misma carpeta de la página web?
> ¿Y si está en una carpeta superior? 

**Respuesta:** 
Si la imagen esta en la misma carpeta de la imagen o una superior, la ruta `imagenes/imagen.jpg` no funcionaria, por lo que se haria uso del atributo `alt` y se mostrará en este caso *"Imagen"* con un pequeño icono de imagen rota, haciendo referencia a que la imagen o el vínculo esta **roto**. Una solución en estos dos caso es cambiar la ruta de `src` a una como `imagen.jpg` o como `../imagen.jpg` respectivamente.

---

### Pregunta 10 
**Enunciado:**  
> Pregúntese, ¿Cómo se consigue que el último enlace se abra en una nueva ventana?

**Respuesta:** 
Se consigue con el atributo `target="_ablank"` donde `target` controla donde se abre el enlace y el valor `_ablank` indica que se abra en una nueva ventana.

---