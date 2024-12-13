# 🗣️ **Proyecto de Reconocimiento de Voz con Google Cloud Speech-to-Text**

Este proyecto emplea la API de Google Cloud Speech-to-Text para convertir grabaciones de voz en texto escrito. Ideal para aplicaciones de transcripción, accesibilidad y procesamiento de lenguaje natural.


## 🎥 **Demostración en YouTube**
[Haz clic aquí para ver el video](https://youtu.be/)

---

## 🎯 **Objetivo**
Integrar la tecnología de Google Cloud Speech-to-Text para transformar grabaciones de voz en texto, facilitando aplicaciones en accesibilidad, transcripción de contenido, y procesamiento de lenguaje natural.

---

## 🔧 **Requisitos**

- `google-cloud-speech`: Interactuar con la API.
- Software para grabar o almacenar archivos de audio en formato compatible (como `.wav` o `.flac`).

Instala la dependencia principal:

```
pip install google-cloud-speech
```

## ⚙️ Configuración
Para utilizar la API de Google Cloud Speech-to-Text, sigue estos pasos:

Crea un proyecto en Google Cloud Console.
Habilita la API de Speech-to-Text.
Genera una clave de servicio en formato JSON y descárgala.
Configura la variable de entorno GOOGLE_APPLICATION_CREDENTIALS con la ruta del archivo de credencial:

```
import os
os.environ["GOOGLE_APPLICATION_CREDENTIALS"] = "ruta/a/tu/credencial.json"
```

## 🎙️ Grabar y Transcribir
Grabar Audio: Utiliza una herramienta de grabación para obtener un archivo de audio en formato .wav o .flac.
Subir y Procesar: Carga el archivo en el proyecto y utiliza la API para obtener la transcripción en texto.
Ajustar Configuración: Configura opciones como idioma, formato de audio, y puntuación automática según las necesidades del proyecto.

