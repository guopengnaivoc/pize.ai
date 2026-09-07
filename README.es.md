<p align="center">
  <a href="https://pize.ai/es">
    <img src="assets/pize-logo.svg" width="96" height="96" alt="Pize logo" />
  </a>
</p>

<h1 align="center">pize.ai</h1>

<p align="center"><strong>Programación con IA para el cálculo científico y el análisis estadístico.</strong></p>
<p align="center">Comprende los datos. Construye el análisis. Revisa los resultados.</p>

<p align="center">
  <a href="https://pize.ai/es">Sitio web</a> &middot;
  <a href="https://pize.ai/docs">Documentación</a> &middot;
  <a href="https://pize.ai/download">Descargar</a>
</p>

<p align="center" dir="ltr">
  <a href="README.md">简体中文</a> &middot;
  <a href="README.en.md">English</a> &middot;
  <a href="README.de.md">Deutsch</a> &middot;
  <a href="README.ja.md">日本語</a> &middot;
  <a href="README.fr.md">Français</a><br />
  <a href="README.ar.md">العربية</a> &middot;
  <a href="README.es.md">Español</a> &middot;
  <a href="README.hi.md">हिन्दी</a> &middot;
  <a href="README.id.md">Bahasa Indonesia</a> &middot;
  <a href="README.ru.md">Русский</a>
</p>

---

## Ecosistema de cálculo científico

<p align="center">
  <a href="https://pize.ai/zh-Hans/share">
    <img src="assets/scientific-ecosystem.png" width="960" alt="24 lenguajes y herramientas de investigación del sitio web de Pize" />
  </a>
</p>

Este mural muestra los lenguajes y las herramientas de investigación enumerados en el sitio de Pize, que abarcan análisis de datos, cálculo numérico, aprendizaje automático y visualización. Pize aporta asistencia de programación con IA a estos flujos de investigación; consulta la [documentación oficial](https://pize.ai/docs) para conocer el alcance del soporte, y ten en cuenta que los logotipos no implican alianzas ni respaldo oficial de las marcas.

## Diseñado para investigar, no solo para completar código

**Pize es un asistente de programación con IA para investigadores que trabajan con código científico y datos estadísticos.** Ayuda a comprender proyectos, preparar análisis, escribir y ejecutar código, examinar salidas y gráficos, y ajustar el siguiente paso. Puedes usarlo en Pize Code, Positron, mediante la CLI o a través del SDK.

Los errores suelen empezar antes de ajustar un modelo: un delimitador incorrecto, un valor ausente interpretado como número o una observación confundida con una cabecera. Pize prioriza la comprensión de los datos para trabajar a partir de su estructura real, no de suposiciones sobre el archivo.

Este repositorio es el espacio público del producto y la comunidad de Pize, mantenido por su fundador, [@guopengnaivoc](https://github.com/guopengnaivoc).

## Qué ofrece Pize

| Capacidad | Aplicación en tu trabajo |
| --- | --- |
| **Lectura consciente de los datos** | Detectar delimitadores, cabeceras, valores ausentes y tipos de columna a partir del contenido; gestionar comentarios, metadatos y tablas comprimidas. |
| **Contexto para grandes conjuntos de datos** | Generar una ficha compacta cuando se supera el presupuesto de contexto, con esquema, una pequeña vista previa y un recuento de filas identificado como estimación. |
| **Sesión real de R / Python** | En Positron, inspeccionar la sesión activa y resumir dataframes. Ejecutar código y obtener gráficos con aprobación para iterar sobre resultados reales. |
| **Cambios de código revisables** | Coordinar modificaciones entre archivos, revisar diferencias, deshacer cambios y volver a un punto de control anterior de la tarea. |
| **Planificación y ejecución** | Explorar primero el proyecto en modo de planificación, acordar un enfoque y después escribir código y ejecutar comandos con aprobación. |
| **Contexto del proyecto y del navegador** | Referenciar archivos, carpetas, problemas y URL; usar el navegador, capturas de pantalla y registros al depurar. |
| **Convenciones reutilizables** | Aplicar reglas de proyecto y habilidades para definiciones estadísticas, convenciones de gráficos y organización de directorios. |

Para formatos de investigación como Parquet, Arrow, RDS, HDF5, h5ad, NumPy, SPSS y Stata, Pize identifica el formato y orienta la creación del código de carga adecuado. Esto no equivale a decodificar todos los formatos binarios directamente en la conversación. Consulta la [documentación de lectura y entorno de ejecución](https://pize.ai/docs) para conocer el comportamiento y sus límites.

## Trabaja en tu entorno habitual

| Interfaz | Uso |
| --- | --- |
| **Pize Code** | Asistencia en el editor, contexto del proyecto, revisión de cambios y trabajo en el terminal. |
| **Positron** | El mismo agente, con acceso a la sesión de R o Python que ya tienes activa. |
| **CLI** | Utilizar Pize desde la línea de comandos. |
| **SDK** | Integrar el agente y sus capacidades orientadas a datos en programas propios y herramientas internas. |

El puente con la sesión en ejecución es específico de Positron. No todas las interfaces ofrecen el mismo acceso al entorno de ejecución. La instalación y los detalles se describen en la [documentación oficial](https://pize.ai/docs).

## Modelos y herramientas conectadas

Pize admite conexiones a modelos en la nube y locales, entre ellos Anthropic, OpenAI, Google Gemini, DeepSeek, AWS Bedrock y OpenRouter, además de endpoints compatibles con OpenAI. Elige el proveedor y la configuración adecuados para tu entorno de investigación.

**El SDK integra Pize en tu programa; MCP conecta Pize con herramientas externas.** Como cliente MCP, puede conectarse a servidores compatibles de bases de datos, sistemas internos y herramientas de laboratorio. Las operaciones disponibles dependen del servidor conectado y de los permisos concedidos.

## Primeros pasos

1. **Elige una interfaz.** Empieza en la [página oficial de descargas](https://pize.ai/download) y sigue las instrucciones de tu entorno.
2. **Configura un modelo.** Conecta un proveedor compatible o un endpoint local según la documentación.
3. **Aporta el contexto de investigación.** Abre el proyecto y adjunta los scripts o datos pertinentes. En Positron, activa la sesión que contiene los datos que quieres analizar.
4. **Planifica, aprueba e itera.** Acuerda el enfoque, revisa las acciones propuestas y examina el código, las salidas y los gráficos antes de continuar.

<details>
<summary><strong>Ejemplos de solicitudes de investigación</strong></summary>

Estas solicitudes son puntos de partida, no resultados validados de forma independiente.

- «Examina las columnas, los tipos y los valores ausentes de este conjunto de datos antes de proponer un análisis».
- «Explica este flujo de R o Python e identifica los supuestos que debería revisar».
- «Ayúdame a modificar este script de análisis, ejecútalo tras mi aprobación e interpreta los gráficos de diagnóstico».

</details>

Pize ayuda con el trabajo, pero no sustituye el criterio científico. Revisa los supuestos metodológicos y las salidas antes de confiar en un resultado. El tratamiento de los datos depende de las herramientas y servicios de modelos configurados; consulta la [información de privacidad](https://pize.ai/privacy) y las políticas de tu proveedor.

## Qué se publica aquí

Este repositorio contiene información del producto, orientaciones para la comunidad y un [visor interactivo de proteínas](https://guopengnaivoc.github.io/pize.ai/) independiente. El visor es una demostración visual, no un servicio de predicción de proteínas ni evidencia de resultados científicos validados. Las fuentes se detallan en los [créditos de las proteínas](assets/protein-CREDITS.md).

**El código fuente de la aplicación principal de Pize no se publica en este repositorio.** La publicación del visor no convierte todo el producto en código abierto. En el futuro podrían publicarse herramientas, ejemplos y notas técnicas seleccionados, cada uno con su alcance y licencia. Consulta el sitio oficial para obtener el software y conocer su disponibilidad.

## Fundador, comentarios y colaboración

Pize fue fundado por [@guopengnaivoc](https://github.com/guopengnaivoc), que lo mantiene bajo el nombre **pize.ai**. El sitio web es la entrada al producto; este repositorio reúne información pública del proyecto y comentarios de la comunidad.

- **Preguntas sobre el producto y solicitudes de funciones:** abre una [incidencia en GitHub](https://github.com/guopengnaivoc/pize.ai/issues).
- **Informes de errores útiles:** describe el entorno, la tarea, el comportamiento esperado y el observado, junto con un ejemplo mínimo. Consulta la [guía de contribución](CONTRIBUTING.md).
- **Colaboración, uso en laboratorio o consultas privadas:** elige el correo adecuado más abajo.

No publiques claves API, credenciales, datos privados ni material de investigación confidencial en incidencias públicas. Consulta las capacidades actuales y la configuración en [pize.ai](https://pize.ai/es) y su [documentación](https://pize.ai/docs).

## Contactar con Pize

Haz clic en una dirección para abrir tu aplicación de correo con un asunto sugerido. Estas direcciones están publicadas en la [página oficial de contacto](https://pize.ai/contact).

| Contacto | Motivo | Correo electrónico |
| --- | --- | --- |
| **Consultas generales** | Preguntas sobre el producto, solicitudes de prensa e información de versiones. | [hello@pize.ai](mailto:hello@pize.ai?subject=Pize%20general%20inquiry) |
| **Contacto de producto** | Demostraciones, preguntas de implementación y colaboraciones. | [contact@pize.ai](mailto:contact@pize.ai?subject=Pize%20product%20inquiry) |
| **Soporte técnico** | Cuenta, documentación, privacidad y solicitudes de eliminación de datos. | [support@pize.ai](mailto:support@pize.ai?subject=Pize%20support%20request) |
| **Negocios y alianzas** | Compras, colaboraciones de investigación y consultas comerciales. | [business@pize.ai](mailto:business@pize.ai?subject=Pize%20business%20inquiry) |
