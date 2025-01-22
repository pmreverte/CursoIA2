# 📘 Proyecto: Azure OpenAI & LlamaIndex RAG

## 📌 Descripción

Este repositorio contiene código en **Python** desarrollado en **Jupyter Notebooks** para la integración de **Azure OpenAI** con **LlamaIndex**, utilizando técnicas de recuperación aumentada de generación (**RAG**) para mejorar la búsqueda de información en documentos PDF y la web.

## 🚀 Características

- Carga y procesamiento de documentos **PDF** para extracción de texto y embeddings.
- Integración con **Azure OpenAI** para generación y consulta de embeddings.
- Implementación de un **sistema de búsqueda híbrido** combinando embeddings y consultas a **Bing Search API**.
- Funcionalidad para dividir, superponer y agrupar textos para mejorar la recuperación de información.
- Uso de **cosine similarity** para encontrar documentos más relevantes en el índice.
- Agente de IA con herramientas personalizadas para búsqueda de información.
- Posibilidad de definir un **prompt inicial** para el sistema y personalizar su comportamiento.
- Capacidad de obtener **archivos PDF desde la web o desde una carpeta local** para su procesamiento.

## 🛠️ Requisitos

Antes de ejecutar el código, asegúrate de crear un archivo `.env` con la siguiente configuración:

```ini
AZURE_OPENAI_ENDPOINT=
AZURE_OPENNAI_DEPLOYMENT_NAME=
AZURE_OPENAI_EMBEDINGS_DEPLOYMENT_NAME=
AZURE_OPENAI_API_KEY=
BING_ENDPOINT=
BING_SEARCH_API_KEY=
AZURE_OPENAI_EMBEDINGS_API_KEY=
AZURE_OPENAI_ENDPOINT_EMBEDINGS=
```
Estos valores deben configurarse con credenciales válidas para que el sistema funcione correctamente.


Antes de ejecutar el código, asegúrate de tener instalados los siguientes requisitos:

- **Python 3.8+**
- **Jupyter Notebook**
- Bibliotecas necesarias (pueden instalarse ejecutando el siguiente comando):
  ```bash
  pip install -r requirements.txt
  ```

## 🏃‍♂️ Ejecución

Para ejecutar el proyecto:

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   ```
2. Accede al directorio del proyecto:
   ```bash
   cd tu-repositorio
   ```
3. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
4. Inicia Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Abre el notebook deseado y ejecuta las celdas según las instrucciones proporcionadas.
