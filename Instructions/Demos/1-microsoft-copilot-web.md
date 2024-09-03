---
Layout: default
demo:
  title: 'Demostración: Microsoft Copilot (ámbito web)'
---

[Volver al índice](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Microsoft Copilot (ámbito web)

## Copilot y los modelos de lenguaje grandes

### Puntos de conversación

Microsoft Copilot en la web te ofrece un asistente personal con tecnología de IA que puede responder a preguntas y ayudar con tareas generales. Puedo hacerle preguntas, y me dará respuestas similares a las que cualquier persona con educación superior podría dar.

Cuando tú o tu organización usan Copilot con protección de datos comerciales, el chat no se guarda. Todos los datos están cifrados y Microsoft no conserva ninguna de las solicitudes o respuestas. No se usan para entrenar el modelo, por lo que puedes estar seguro de que tu información personal y organizativa se mantiene confidencial.

Por ejemplo, puedo hacer una pregunta de conocimiento general como esta y obtener una gran cantidad de información muy buena. Puedes considerarlo como tener un modelo conceptual básico del mundo que puede usar para responder a preguntas.

**Ejemplo**:
- **Pregunta:** ¿Qué me puedes decir sobre los elefantes?
- **Respuesta:** (analiza la respuesta)

Copilot usa modelos de lenguaje grandes (LLM) entrenados en grandes cantidades de información, incluidas las búsquedas y los resultados de Bing. Pero Copilot no es solo un verificador de hechos. Podemos usar Copilot como un motor de razonamiento general que puede tomar tus preguntas y razonar sobre ellas estocásticamente. En el sector, lo denominamos inferencia.

**Ejemplo**:
- **Mensaje:** Estoy más interesado en la fuerza de un elefante. ¿Cuántos seres humanos se necesitarían para ganar un juego de tirar de la cuerda con un elefante? NOTA: ten en cuenta la región y el público, ya que no todos conocen el término "juego de tirar de la cuerda" por lo que es posible que lo tengas que modificar en consecuencia. 
- **Respuesta:** (analiza la respuesta)

Copilot pudo hacer suposiciones y establecer conexiones entre conocimientos fragmentados para darme una respuesta más matizada a mi pregunta. A medida que mejoramos Copilot, estamos aprendiendo mucho sobre para qué son útiles estos LLM y para lo que no son útiles, y estamos incorporando ese conocimiento en el producto a medida que lo creamos.

### Pasos de la demostración

> **NOTA:** si deseas usar tus propios mensajes, comienza con un tema de conocimientos generales interesante para ti o el cliente.

1. Cambia a la pestaña Edge con Copilot abierto y el ámbito web seleccionado.

    ![Captura de pantalla que muestra el modo web en Microsoft Copilot.](../Demos/Media/web_mode.png)

1. En el cuadro de texto **Pregúntame lo que quieras...**, copia y pega el mensaje de los documentos de la biblioteca de mensajes o escribe:

    ```text
    What can you tell me about elephants?
    ```
1. Selecciona el botón **Enviar**.
1. En el cuadro de texto **Pregúntame lo que quieras...**, copia y pega el mensaje:

    ```text
    I’m more interested in the power of an elephant. How many humans would it take to win a tug-of-war with an elephant?
    ```
1. Selecciona el botón **Enviar**.

## Contextualización

### Puntos de conversación

Sin embargo, lo que lleva este poder al siguiente nivel es la capacidad de fundamentar Copilot con datos y conocimientos externos. A veces, esto se denomina generación aumentada de recuperación (RAG). Este es el proceso de proporcionar información adicional al modelo de lenguaje que es relevante para la tarea en cuestión.

Podemos fundamentar nuestras preguntas en todo tipo de datos y documentos, por ejemplo, el informe de trabajo de la Oficina de Estadística Laboral. Este es un documento enorme, que se publica anualmente y está lleno de datos sobre los empleos y las tendencias de empleo en todo Estados Unidos. Copilot puede salir y encontrar esa información, entenderla y responder a mi pregunta en tiempo real. También me da referencias que me muestran dónde Copilot obtuvo esa información, por ejemplo, el sitio web de la Oficina de Estadística Laboral. Esto significa que puedo comprobar dónde Copilot obtuvo su información y obtener más contexto, porque es un copiloto, no un piloto automático.

### Pasos de la demostración

1. Para iniciar un nuevo tema, haz clic en **Nuevo tema**.

    ![Captura de pantalla que muestra nuevo tema en Microsoft Copilot.](../Demos/Media/new_topic.png)

1. En el cuadro de texto **Pregúntame lo que quieras...**, copia y pega el mensaje:

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years?
    ```
1. Selecciona el botón **Enviar**.
1. En la respuesta, junto a **Más información**, pasa el mouse sobre una o dos de las referencias.

## Aptitudes adicionales de Copilot

### Puntos de conversación

Esto es genial, pero realmente me gustaría ver un gráfico de estos datos. Lamentablemente, Copilot no puede dibujar un gráfico en este momento, pero eso no significa que no se pueda. A medida que creamos Copilot, vamos agregando diferentes aptitudes. Las aptitudes son formas en que Copilot puede aprovechar su poder de razonamiento para resolver problemas.

Otra capacidad que sé que Copilot tiene es la capacidad de codificar. Voy a recordar a Copilot que sabe cómo codificar para ver si puedo lograr que escriba el código de Python para el gráfico que quería.

**Ejemplo**:
- **Pregunta:** ¿Puedes darme una lista de las tasas de participación de la fuerza laboral de la Oficina de Estadística Laboral en los últimos 5 años? También oí que podías codificar. ¿Puedes obtener los datos de bls.gov y después escribir el código de Python que generaría el gráfico que quiero?
- **Respuesta:** (analiza la respuesta)

Con el tiempo, esperamos que estos tipos de procesos sean más fáciles y más automatizados.

### Pasos de la demostración

1. Para iniciar un nuevo tema, haz clic en **Nuevo tema**.

    ![Captura de pantalla que muestra nuevo tema en Microsoft Copilot.](../Demos/Media/new_topic.png)

1. En el cuadro de texto **Pregúntame lo que quieras...**, copia y pega el mensaje:

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years? I also heard that you could code. Can you grab the data from bls.gov and then write the Python code that would produce the graph I'm looking for?
    ```

1. Selecciona el botón **Enviar**.

## Pasos de la demostración opcionales

### Reconocimiento de imágenes

Primero, descarga lo siguiente: [**¿Qué es esta image.png**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/what_is_this_image.PNG)

1. Para iniciar un nuevo tema, haz clic en **Nuevo tema**.

    ![Captura de pantalla que muestra nuevo tema en Microsoft Copilot.](../Demos/Media/new_topic.png)

1. En la parte inferior de la página, selecciona el icono **Agregar una imagen**.

    ![Captura de pantalla que muestra cómo agregar una imagen en Microsoft Copilot.](../Demos/Media/add_an_image.png)

1. Selecciona **Cargar desde este dispositivo**.
1. Ve a la ubicación donde descargaste la imagen, selecciona **¿Qué es esta picture.png**? y después selecciona **Abrir**.
1. En el cuadro de texto **Pregúntame lo que quieras...** en el cuadro de texto, escribe el mensaje:

    ```text
    What is this picture?
    ```

1. Selecciona el botón **Enviar**.

### Mostrar cómo Copilot puede crear imágenes

1. En el cuadro de texto **Pregúntame lo que quieras...**, copia y pega el mensaje:

    ```text
    Copilot, make a banner for a hamburger stand. Make it friendly and show people enjoying a hamburger.
    ```

1. Selecciona el botón **Enviar**.

### Mostrar cómo Copilot puede escribir una canción

1. Cambia a una nueva sesión del explorador que haya iniciado sesión en una cuenta personal.

> **NOTA:** deberás usar una cuenta personal para este paso. Las cuentas profesionales no funcionarán.

1. En la esquina superior derecha, selecciona **Complementos**.

    ![Captura de pantalla que muestra cómo agregar una imagen en Microsoft Copilot.](../Demos/Media/copilot_plugins.png)

1. En la lista de complementos disponibles, habilita **Suno**.

    ![Captura de pantalla que muestra cómo agregar una imagen en Microsoft Copilot.](../Demos/Media/copilot_suno.png)

    > **NOTA:** para usar Suno, debes iniciar un nuevo tema en Copilot y después habilitar Suno.

1. En el cuadro de texto **Pregúntame lo que quieras...**, copia y pega el mensaje:

    ```text
    Write a country song about Microsoft Copilot, extolling its virtues as an AI companion. Make it catchy, upbeat, and a little quirky.
    ```

1. Selecciona el botón **Enviar**.

[Volver al índice](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)
