# VideoText

# 🎙️ VideText Converter

## 📝 Descripción
AudioText Converter es una aplicación de escritorio potente y fácil de usar que convierte audio y video a texto. Diseñada para hacer la transcripción accesible para todos, permite procesar tanto archivos locales como contenido de YouTube y otras fuentes en línea.

![VideoText Converter Screenshot](screenshot.png)

## ✨ Características Principales

- 🎥 **Soporte Multi-Fuente**
  - Descarga y procesa videos de YouTube
  - Procesa URLs directas de video/audio
  - Maneja archivos locales en múltiples formatos

- 🌍 **Soporte Multi-Idioma**
  - Reconocimiento de voz en múltiples idiomas
  - Interfaz intuitiva para selección de idioma
  - Compatible con más de 50 idiomas

- 💾 **Gestión Automática**
  - Descarga automática a la carpeta de Descargas
  - Guardado automático de transcripciones
  - Limpieza automática de archivos temporales

- 📊 **Monitoreo en Tiempo Real**
  - Barra de estado actualizada
  - Log detallado del proceso
  - Mensajes de error descriptivos

## 🔧 Requisitos

- Python 3.8 o superior
- FFmpeg instalado en el sistema
- Conexión a Internet para descargas y reconocimiento de voz
- Bibliotecas Python requeridas:
  ```
  speech_recognition
  pytube
  requests
  tkinter
  ```

## 🚀 Instalación

1. Clone el repositorio:
   ```bash
   git clone https://github.com/Carloncho0528Videotext-converter.git
   cd audiotext-converter
   ```

2. Instale las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

3. Instale FFmpeg:
   - **Windows**: Descargue desde [FFmpeg Builds](https://github.com/BtbN/FFmpeg-Builds/releases)
   - **Linux**: `sudo apt-get install ffmpeg`
   - **macOS**: `brew install ffmpeg`

## 💻 Uso

1. Ejecute la aplicación:
   ```bash
   python audiotext_converter.py
   ```

2. Para procesar un video de YouTube:
   - Pegue la URL en el campo correspondiente
   - Haga clic en "Descargar"
   - Espere a que se complete la descarga
   - Presione "Procesar Audio"

3. Para archivos locales:
   - Use el botón "Buscar" para seleccionar el archivo
   - Presione "Procesar Audio"

4. La transcripción se guardará automáticamente en su carpeta de Descargas

## 🎯 Ejemplos de Uso

### Transcripción de Video de YouTube
```python
1. Pegue la URL: https://www.youtube.com/watch?v=ejemplo
2. Seleccione el idioma (ej: es-ES para español)
3. Haga clic en Descargar
4. Presione Procesar Audio
```

### Procesamiento de Archivo Local
```python
1. Haga clic en Buscar
2. Seleccione su archivo de audio/video
3. Elija el idioma
4. Presione Procesar Audio
```

## ⚙️ Configuración Avanzada

- Modifique `config.py` para cambiar:
  - Directorio de descarga predeterminado
  - Formato de salida de audio
  - Parámetros de FFmpeg
  - Configuración de reconocimiento de voz

## 🤝 Contribuciones

Las contribuciones son bienvenidas! Por favor:
1. Haga Fork del proyecto
2. Cree una rama para su característica (`git checkout -b feature/AmazingFeature`)
3. Commit sus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abra un Pull Request

## 📄 Licencia

Este proyecto está licenciado bajo la Licencia MIT - vea el archivo [LICENSE.md](LICENSE.md) para detalles.

## 🙏 Agradecimientos

- [FFmpeg](https://ffmpeg.org/) por el procesamiento de audio/video
- [Google Speech Recognition](https://cloud.google.com/speech-to-text) por el servicio de reconocimiento de voz
- [pytube](https://github.com/pytube/pytube) por la integración con YouTube

---
Made with ❤️ by [Sedsist]
