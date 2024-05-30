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

Descarga el proyecto en este link: [ ]

### 2. Crear un entorno virtual

Crea y activa un entorno virtual:

#### En Windows (PowerShell):

sh
python -m venv venv
.\venv\Scripts\Activate.ps1

### En macOS y Linux:
sh
Copiar código
python3 -m venv venv
source venv/bin/activate

#### 3. Instalar dependencias
#### Instala las dependencias necesarias:

sh
Copiar código
pip install Flask torch torchvision nltk

### 4. Descargar el paquete 'punkt' de nltk
### Abre una consola interactiva de Python y ejecuta los siguientes comandos:

sh
Copiar código
python
python
Copiar código
import nltk
nltk.download('punkt')
exit()

### 5. Modificar intents.json
### Abre el archivo intents.json en tu editor de texto y modifica las intenciones y respuestas según tus necesidades.

#### 6. Entrenar el chatbot
#### Ejecuta el script train.py para entrenar el modelo del chatbot:

sh
Copiar código
python train.py

### 7. Probar el chatbot en la consola
### Una vez que el modelo esté entrenado, prueba el chatbot ejecutando el script chat.py:

sh
Copiar código
python chat.py

### 8. Implementación (opcional)
### Para la implementación en una aplicación web, sigue el tutorial del autor para configurar app.py y app.js.

#### Licencia
MIT License

Copyright (c) 2024 Samuel García Ramírez, José Andrés Herrera Rincón

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
