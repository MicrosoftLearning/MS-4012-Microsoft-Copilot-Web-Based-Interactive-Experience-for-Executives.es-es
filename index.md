---
title: Instrucciones hospedadas en línea
permalink: index.html
layout: home
---

# Directorio de contenido

Las demostraciones de este curso se basan en las demostraciones de la guía de demostración del kit [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

Es importante que te familiarices con las demostraciones antes de presentar este entrenamiento. Para varios laboratorios, usarás documentos de ejemplo y reuniones y correos electrónicos de Teams creados previamente.

- Descarga previamente todos los documentos de ejemplo [aquí](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Resourcefiles).
- Configura las reuniones de Teams y los hilos de correo siguiendo las instrucciones que se indican [aquí](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- Familiarízate con la experiencia interactiva que se encuentra [aquí](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012_interactive_experience.pdf).

    > **NOTA:** el archivo PDF de la experiencia interactiva se descargará directamente en el dispositivo (carpeta de descargas).

- Revisa la presentación más reciente [aquí](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012-ENU-PowerPoint.pptx).

## Descripción del curso

Explora el potencial transformador de Microsoft Copilot y su impacto en la eficiencia de la organización. Diseñado para ejecutivos y líderes empresariales sin una licencia de Copilot, esta experiencia profundiza en el arte de elaborar solicitudes eficaces, ofrece una experiencia interactiva y muestra cómo Microsoft Copilot para Microsoft 365 puede integrarse perfectamente en los flujos de trabajo empresariales diarios para aumentar la productividad y la innovación.

Los objetivos principales de esta entrega son:

- Enseñar a crear solicitudes eficaces
- Demostrar Microsoft Copilot (ámbito web) y guiar a los participantes a través de una experiencia interactiva
- Demostrar Microsoft Copilot para Microsoft 365: Microsoft Copilot (ámbito de trabajo), word, Outlook y equipos
- Invita a los participantes a descargar y probar Microsoft Copilot for Mobile

## Tiempo del curso (no finalizado) 

| # | Tema                                 | Detalles                                                                                          | Tiempo total      |
|---|---------------------------------------|--------------------------------------------------------------------------------------------------|-----------------|
| 1 | Creación de solicitudes efectivas para Copilot para Microsoft 365 | - Diapositiva del arte de la pregunta <br> - Diapositiva de creación de solicitud <br> - Diapositiva del laboratorio de Copilot | 5-10 minutos    |
| 2 | Microsoft Copilot en la web          | - Demostración de Microsoft Copilot (modo web) <br> - Experiencia interactiva  <br> - Diapositiva para compartir tus experiencias | 35 minutos      |
| 3 | Copilot para Microsoft 365 en acción     | - Diapositiva de Microsoft Graph <br> - Demostración de Copilot en Word, Microsoft Copilot (modo de trabajo), Copilot en Outlook y Copilot en Teams <br> - Diapositiva de testimonios <br> - Diapositiva de Microsoft Copilot on Mobile | 25 minutos      |
|   |                                       |                                                                                                  | **El tiempo total podría ser 70 minutos** |


A continuación, se enumeran los hipervínculos a cada una de las demostraciones.

## Demostraciones

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demostración |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
