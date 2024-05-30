# Chatbot Deployment

Este proyecto es un chatbot que utiliza Flask, PyTorch, torchvision y nltk. Sigue los pasos a continuación para configurarlo y ejecutarlo en tu entorno local.

## Autores

- Samuel García Ramírez
- José Andrés Herrera Rincón

## Requisitos

Asegúrate de tener instalado lo siguiente:

- Python 3.x
- Git

## Instrucciones

### 1. Descargar el proyecto

Descarga el proyecto en este link: [https://github.com/Jahrming/PROYECTO-HUMANO-COMPUTO/tree/main ]

### 2. Crear un entorno virtual

- Crea y activa un entorno virtual:

#### En Windows (PowerShell):

- sh
- python -m venv venv
- .\venv\Scripts\Activate.ps1

### En macOS y Linux:
- sh
- Copiar código
- python3 -m venv venv
- source venv/bin/activate

#### 3. Instalar dependencias
#### Instala las dependencias necesarias:

- sh
- pip install Flask torch torchvision nltk

### 4. Descargar el paquete 'punkt' de nltk
### Abre una consola interactiva de Python y ejecuta los siguientes comandos:

- sh
- python
- import nltk
- nltk.download('punkt')
- exit()

### 5. Modificar intents.json
### Abre el archivo intents.json en tu editor de texto y modifica las intenciones y respuestas según tus necesidades.

#### 6. Entrenar el chatbot
#### Ejecuta el script train.py para entrenar el modelo del chatbot:

- sh
- python train.py

### 7. Probar el chatbot en la consola
### Una vez que el modelo esté entrenado, prueba el chatbot ejecutando el script chat.py:

- sh
- python chat.py


