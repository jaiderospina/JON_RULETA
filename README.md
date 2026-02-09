# 🎯 Ruleta Jaider

**Ruleta Jaider** es una aplicación web interactiva y dinámica diseñada para realizar sorteos aleatorios a partir de listas cargadas externamente. Es ideal para elegir ganadores, asignar turnos en clase o tomar decisiones grupales de forma justa y emocionante.

![](ruleta.jpg)

## ✨ Características Principales

* **Carga de Datos Flexible:** Soporta la importación de archivos de hojas de cálculo en formatos `.xlsx`, `.xls` y `.csv`.
* **Animación Realista:** Cuenta con una animación de giro suave con desaceleración gradual para aumentar la expectativa.
* **Sistema de Audio Dinámico:** Incluye efectos de sonido de "clic" durante el giro y una fanfarria de victoria al seleccionar un nombre.
* **Gestión de Historial:** Muestra los nombres seleccionados recientemente para evitar repeticiones inmediatas (mantiene un registro de los últimos 5 resultados).
* **Interfaz Adaptable:** Diseño moderno y responsivo con degradados elegantes, optimizado para una visualización clara.

## 🚀 Cómo Utilizar la Aplicación

1. **Preparar el archivo:** Crea un archivo Excel o CSV que contenga una columna con los nombres de los participantes.
2. **Cargar nombres:** Haz clic en el botón **"📁 Cargar Hoja de Cálculo"** y selecciona tu archivo. La aplicación te confirmará cuántos nombres se han cargado exitosamente.
3. **Configurar Sonido:** Puedes activar o desactivar el audio en cualquier momento usando el botón de **"🔊 Sonido"**.
4. **Girar:** Presiona el botón **"🎲 Girar Ruleta"**. La ruleta mostrará nombres aleatorios a gran velocidad hasta detenerse en el ganador.
5. **Ver Resultado:** El nombre del seleccionado aparecerá resaltado en el centro de la ruleta y en una sección de resultados en la parte inferior.

## 🛠️ Detalles Técnicos

La aplicación está construida utilizando tecnologías web estándar, lo que garantiza que funcione en cualquier navegador moderno sin necesidad de instalación:

* **HTML5 & CSS3:** Estructura y estilos, incluyendo animaciones mediante `keyframes` y transformaciones 3D.
* **JavaScript (ES6+):** Lógica de selección aleatoria y control de la interfaz.
* **SheetJS (XLSX.js):** Librería integrada vía CDN para procesar y leer archivos de Excel directamente en el navegador.
* **Web Audio API:** Generación de sonidos sintéticos en tiempo real para una experiencia interactiva sin depender de archivos de audio externos pesados.

## 📋 Requisitos del Archivo

Para que la ruleta funcione correctamente, asegúrate de que tu archivo:

* No esté protegido por contraseña.
* Tenga los nombres en una columna clara (la aplicación aplanará los datos de la primera hoja encontrada).

---

