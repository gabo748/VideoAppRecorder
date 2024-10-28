# Video Recorder App

Una aplicación sencilla de Android que permite **grabar videos**, almacenarlos en el almacenamiento específico de la aplicación, y reproducirlos desde una lista usando **Jetpack Compose** y **MediaRecorder**. Esta app está diseñada para mostrar los conceptos básicos de grabación, almacenamiento y reproducción de video en Android.

## Características
- **Grabar videos** usando la cámara y micrófono.
- **Almacenar videos** en el directorio específico de la aplicación.
- **Listar y reproducir videos** dentro de la app.
- Implementada con **Jetpack Compose** para la interfaz de usuario moderna.
- Soporte para **ViewModel** con un **ViewModelFactory** personalizado.

---
## Requisitos
- **Android Studio** 2022.2.1 o superior.
- SDK mínimo: 24 (Android 7.0 Nougat)
- **Permisos**: Cámara, Audio y Almacenamiento.

---

## Instalación

1. **Clonar el proyecto**:
   ```bash
   git clone https://github.com/tu-repositorio/video-recorder-app.git
   ```
2. **Abrir en Android Studio**:
   - Archivo > Abrir > Selecciona la carpeta del proyecto.
3. **Configurar el emulador** (o usar un dispositivo físico).
4. **Construir y ejecutar** la aplicación:
   - Haz clic en "Run" en Android Studio.
---

## Permisos Requeridos

Asegúrate de que los siguientes permisos estén configurados en el archivo `AndroidManifest.xml`:

```xml
<uses-permission android:name="android.permission.CAMERA" />
<uses-permission android:name="android.permission.RECORD_AUDIO" />
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" android:maxSdkVersion="28" />
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
```

Para dispositivos con Android 6.0 o superior, los permisos se solicitan en **tiempo de ejecución**.

---


## Tecnologías Usadas

- **Kotlin**: Lenguaje principal del proyecto.
- **Jetpack Compose**: Para la interfaz de usuario declarativa.
- **ViewModel**: Para la gestión del estado.
- **MediaRecorder**: Para la grabación de audio y video.
- **ExoPlayer** (opcional): Para la reproducción de video.

---

## Autor

**Gabriel Campos**  

---

## Pruebas

#
https://github.com/gabo748/VideoAppRecorder/blob/main/Screenshot_20241027_200847.png
https://github.com/gabo748/VideoAppRecorder/blob/main/Screenshot_20241027_200915.png
https://github.com/gabo748/VideoAppRecorder/blob/main/Screenshot_20241027_201022.png
https://github.com/gabo748/VideoAppRecorder/blob/main/Screenshot_20241027_201151.png
---

## Capturas de Pantalla

*(Agrega capturas de pantalla si lo deseas)*
