# RAG con LangChain y Ollama — Trabajo Práctico

## Resumen

Proyecto de ejemplo para implementar un sistema RAG (Retrieval-Augmented Generation) utilizando LangChain para orquestación y Ollama como modelo local/servicio de LLM. Incluye scripts de ejemplo, notas de instalación y guías básicas de uso.

## Características principales

- Indexado y recuperación de documentos para contexto.
- Integración con LangChain para cadenas de prompts y manejo de memoria.
- Uso de Ollama como modelo local/servicio para generación de texto.
- Ejemplos y notebooks para experimentación.

## Requisitos

- Python 3.10+ recomendado
- uv
- Entorno virtual: venv.
- Ollama instalado y corriendo si se usa como servicio local
- Dependencias listadas en requirements.txt

## Instalación rápida

1. Crear y activar un entorno virtual:

   - Windows (cmd/powershell):
     uv venv

     .venv\Scripts\activate

2. Instalar dependencias:
   uv pip install -r requirements.txt
3. Asegurarse de que Ollama está instalado y accesible.
4. Tener los modelos de Ollama nomic-embed-text, embeddinggemma, qwen2.5:0.5b.

## Uso básico

1. Abrir el archivo de configuración .env.example, cambiar el nombre a .env y modificar la variable API_KEY con tu clave de google ai studio.
2. Abrir el archivo langchain_tp.ipynb y ejecutar todo.
3. Revisar resultados.
