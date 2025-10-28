# LLM_PrimerAvance

Este repositorio contiene ejemplos básicos y progresivos para aprender a usar la API de OpenAI (y su integración con LangChain) desde Python.
Cada guía muestra cómo interactuar con modelos como gpt-4o-mini para generar texto, estructurar respuestas o construir cadenas conversacionales.

**Guía 1 – Primer contacto con OpenAI**

Archivo: guia1.py
Descripción:
Ejemplo mínimo para conectarse a la API, enviar un prompt simple y mostrar la respuesta del modelo.

**Guía 2 – Explorando la temperatura**

Archivo: guia2.py
Descripción:
Muestra cómo la temperatura afecta la creatividad del modelo generando respuestas distintas a un mismo prompt.

**Guía 3 – Respuestas estructuradas y funciones reutilizables**

Archivo: guia3.py
Descripción:
Demuestra cómo obtener respuestas estructuradas en JSON, validar la salida y crear una función de consulta reutilizable.

**Guía 4 – Integración con LangChain**

Archivo: guia4.py
Descripción:
Introduce el uso de LangChain para construir flujos conversacionales más avanzados, como cadenas de prompts y memoria de chat.

**Requisitos**

Instalamos las dependencias necesarias con:

`pip install openai python-dotenv langchain langchain-openai`

Y creamos un archivo .env con tu clave de API:

`OPENAI_API_KEY=clave`

**Ejecución**

Ejecutamos cualquier guía con:

`python guia1.py`

