      
# Exámenes Interactivos para el Curso DesarrolloCognitivo y Motor

Este repositorio contiene un sistema de exámenes interactivos desarrollado con HTML, CSS y JavaScript. Los exámenes están definidos en formato JSON y se cargan dinámicamente en la página web.

## Descripción

El proyecto permite a los estudiantes realizar exámenes interactivos directamente en su navegador. Las principales características incluyen:

*   **Interfaz sencilla e intuitiva:** Diseño limpio y fácil de usar para una experiencia de usuario óptima.
*   **Carga dinámica de exámenes:** Los exámenes se cargan desde archivos JSON, lo que facilita la creación y actualización de contenido.
*   **Corrección automática:** Los resultados se muestran al finalizar el examen, indicando las respuestas correctas e incorrectas.
*   **Explicaciones detalladas:** Cada pregunta incluye una explicación de la respuesta correcta para reforzar el aprendizaje.

## Estructura del Repositorio

El repositorio tiene la siguiente estructura:

    

IGNORE_WHEN_COPYING_START
Use code with caution.Markdown
IGNORE_WHEN_COPYING_END

.
├── index.html # Archivo HTML principal que contiene la estructura de la página y el JavaScript
├── examenes.json # Archivo JSON que contiene la definición de los exámenes (preguntas, respuestas, explicaciones)
├── README.md # Este archivo, que proporciona información sobre el proyecto
└──

      
## Cómo Usar

1.  **Clonar el repositorio:**

    ```bash
    git clone [URL del repositorio]
    ```

2.  **Abrir el archivo `index.html` en tu navegador web:**

    Simplemente abre el archivo `index.html` con tu navegador web preferido. No se requiere un servidor web para ejecutarlo localmente, ya que el código JavaScript se ejecuta directamente en el navegador.

3.  **Seleccionar un examen:**

    En la página web, selecciona el examen que deseas realizar de la lista disponible.

4.  **Responder las preguntas:**

    Lee cada pregunta y selecciona la respuesta que consideres correcta.

5.  **Enviar el examen:**

    Haz clic en el botón "Enviar Examen" para ver los resultados.

6.  **Revisar los resultados:**

    La página mostrará tu puntuación, las respuestas correctas e incorrectas, y las explicaciones detalladas de cada pregunta.

## Formato del Archivo `examenes.json`

El archivo `examenes.json` contiene la definición de todos los exámenes. La estructura general es la siguiente:

```json
{
  "examenes": [
    {
      "titulo": "Título del Examen",
      "preguntas": [
        {
          "numero": 1,
          "pregunta": "Texto de la pregunta",
          "opciones": {
            "a": "Opción A",
            "b": "Opción B",
            "c": "Opción C",
            "d": "Opción D"
          }
        },
        // ... más preguntas
      ],
      "respuestas_correctas": {
        "1": "a",  // El número de la pregunta y la letra de la respuesta correcta
        "2": "c",
        // ... más respuestas
      },
      "banco_explicaciones": {
        "1": "Explicación de la respuesta correcta a la pregunta 1.",
        "2": "Explicación de la respuesta correcta a la pregunta 2.",
        // ... más explicaciones
      }
    },
    // ... más exámenes
  ]
}

    

IGNORE_WHEN_COPYING_START
Use code with caution.
IGNORE_WHEN_COPYING_END
Personalización

    Añadir nuevos exámenes: Edita el archivo examenes.json y agrega nuevos objetos JSON al array "examenes". Asegúrate de seguir la estructura definida.

    Modificar el contenido de los exámenes: Edita los campos "titulo", "pregunta", "opciones", "respuestas_correctas" y "banco_explicaciones" para adaptar el contenido a tus necesidades.

    Modificar el estilo: Edita el CSS dentro de la etiqueta <style> en el archivo index.html para personalizar la apariencia de la página.

Dependencias

Este proyecto no tiene dependencias externas. Solo requiere un navegador web moderno para funcionar correctamente.
Notas Adicionales

    Este proyecto está diseñado para ser sencillo y fácil de usar. Si deseas agregar funcionalidades más avanzadas (por ejemplo, temporizador, sistema de puntuación más sofisticado), puedes modificar el código JavaScript según tus necesidades.

    Asegúrate de que el archivo examenes.json esté bien formado (válido según la sintaxis JSON) para evitar errores de carga.

Licencia

[ANa Maria da Cunha Goncalves Licencia]
