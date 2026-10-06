# Dorsiflexion-para-rehabilitar-marcha-Tom-s-Hasbun-y-Tom-s-Martinez
# KineVision Pro | Evaluación Biomecánica Bilateral del Tobillo

Aplicación web interactiva para la evaluación goniométrica cuantitativa y bilateral de la articulación del tobillo mediante visión por computadora. El sistema utiliza rangos articulares fisiológicos absolutos positivos (basados en los estándares clínicos de la AAOS) y evalúa el cumplimiento del criterio funcional de dorsiflexión ($\ge 10^\circ$) para la marcha humana.

---

## 📋 Requisitos del Sistema

* **Navegador Web Moderno:** Google Chrome, Microsoft Edge, Mozilla Firefox o Safari (con soporte para WebGL y acceso a dispositivos de medios).
* **Cámara Web:** Cámara integrada o USB (requerida para el análisis en tiempo real mediante *webcam*).
* **Conexión a Internet:** Necesaria para la carga inicial de las librerías a través de CDN.

---

## 🛠️ Dependencias e Integraciones

El proyecto se ejecuta en el entorno cliente (front-end) y carga las siguientes librerías mediante CDN:

* **[MediaPipe Pose](https://google.github.io/mediapipe/solutions/pose.html):** Detección e inferencia de puntos clave anatómicos tridimensionales en tiempo real.
* **[Chart.js](https://www.chartjs.org/):** Graficación dinámica e interactiva de la cinemática articular en función del tiempo.
* **[Tailwind CSS](https://tailwindcss.com/):** Framework de estilos para la interfaz gráfica responsive de grado clínico.
* **[FontAwesome](https://fontawesome.com/):** Iconografía para la interfaz de usuario.

---

## 📁 Archivos Principales del Proyecto

```text
├── index.html            # Interfaz principal, lógica goniométrica, estilos e integración de scripts
├── README.md             # Documentación general y guía de ejecución del repositorio
└── assets/               # (Opcional) Videos de muestra o archivos CSV de prueba
