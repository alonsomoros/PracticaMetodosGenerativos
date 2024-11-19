[README: Proyecto Métodos Generativos - Texto a Audio]

    IMPORTANTE
    Descarga todos los archivos necesarios desde el repositorio para asegurar que no falten dependencias.
    Aquí se explica brevemente qué hace cada componente del proyecto.

🛠️ Componentes principales del Proyecto
IA Generativa (Texto a Audio)

    Modelo Base: Utiliza un modelo basado en redes neuronales tipo TTS (Text-To-Speech), optimizado para entradas en múltiples idiomas.
    Tokenizador: Procesa el texto para convertirlo en representaciones que el modelo pueda interpretar.
    Generador de Audio: Convierte las salidas del modelo en archivos de audio .wav.

Librerías esenciales

Estas librerías son imprescindibles para el funcionamiento del proyecto:

    Pytorch/TensorFlow: Backend para el entrenamiento y ejecución del modelo.
    Librosa: Procesamiento de audio.
    Hugging Face Transformers: Arquitecturas de modelos y utilidades.
    WaveGlow/Vocoder: Mejora en la síntesis del audio generado.

📚 Herramientas incluidas

    Preprocesador de Texto:
        Normaliza entradas (limpieza de caracteres especiales, conversión a minúsculas).
        Soporte para marcadores prosódicos.

    Entrenador de Modelo:
        Compatible con múltiples GPUs para optimización.
        Generación de checkpoints durante el entrenamiento.

    Postprocesador de Audio:
        Filtros y ajustes en las frecuencias para mejorar la calidad de salida.

🚀 Características y Funciones

    Entrada dinámica: Admite textos largos con pausas calculadas automáticamente.
    Soporte Multilingüe: Reconoce idiomas y ajusta la pronunciación en consecuencia.
    Configuración personalizable: Ajusta velocidad, tono, y emociones en la salida.

🆕 (NUEVAS FUNCIONES)

    Control de emociones en el audio (feliz, serio, interrogativo).
    Conversión a múltiples formatos de audio (WAV, MP3, FLAC).
    Interfaz gráfica básica (GUI) para usuarios no técnicos.

⚠️ Problemas conocidos (CRASHED)

    Latencia en generación con textos largos.
        Recomendación: Dividir el texto en fragmentos menores a 500 caracteres.
    Errores en idiomas de baja frecuencia.
        Plan: Añadir datos de entrenamiento adicionales.

🔍 Dependencias sugeridas (Debate)

    Soporte para síntesis de voz en tiempo real.
    Compatibilidad con modelos de voces customizadas.

📂 Herramientas de Cliente (Opcionales)

    Audacity: Edición avanzada del audio generado.
    Google Colab: Ejecución del modelo en entornos en la nube.
    Docker: Contenedor preconfigurado para facilitar la instalación.
