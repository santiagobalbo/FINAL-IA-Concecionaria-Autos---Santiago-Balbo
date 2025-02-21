# Concecionaria de Autos con Inteligencia Artificial.
Bienvenido al proyecto Generador de Contenido para Concesionarias, una herramienta diseñada para crear descripciones publicitarias y generar imágenes personalizadas de automóviles utilizando modelos de inteligencia artificial. Este proyecto aprovecha la generación de texto de OpenAI junto con la creación de imágenes relevantes, brindando una solución eficiente para el marketing automotriz.

Funcionalidades:
•	Generación de descripciones publicitarias: Escribe un prompt con las características del auto y la IA generará un texto persuasivo adaptado a tus necesidades.
•	Imágenes personalizadas de los vehículos: Crea representaciones visuales de los automóviles en diferentes escenarios, con colores y detalles personalizados.

Tecnologías Utilizadas:
•	Python para la implementación del código.
•	OpenAI GPT para la generación de textos publicitarios.
•	DALL·E para la creación de imágenes de los autos.
•	Google Colab como entorno de ejecución.

Uso del Proyecto:
1.	Clona el repositorio:
git clone https://github.com/TU_USUARIO/contenido_concesionarias.git
cd contenido_concesionarias
2.	Abre notebook:
o	Carga el archivo generador_contenido.ipynb en Google Colab.
3.	Configura tu API Key:
o	Asegúrate de configurar tu clave de OpenAI como una variable de entorno para mayor seguridad:
import os
os.environ["OPENAI_API_KEY"] = "PONE_TU_API_KEY"
openai.api_key = os.getenv("OPENAI_API_KEY")
4.	Ejecuta las celdas:
o	Sigue las instrucciones dentro del notebook para generar descripciones publicitarias e imágenes de los automóviles.

Ejemplo de Uso:
Prompt:
"Genera una descripción publicitaria para un auto eléctrico deportivo dirigido a jóvenes emprendedores."
Resultado: Un texto publicitario atractivo y una imagen personalizada del auto generada automáticamente.
Análisis de Costos:
Para optimizar costos y minimizar el uso de la API:
•	Se utilizan prompts compactos que reducen la cantidad de tokens procesados.
•	Se emplea batch processing para evitar consultas innecesarias.
•	Se optimiza la generación de imágenes utilizando prompts estructurados.

Contacto:
Si tienes preguntas o sugerencias, no dudes en contactarme:
•	Autor: Santiago Balbo
•	Email: [balbosantiago@gmail.com]
¡Disfruta creando contenido automotriz con IA! 🚀
