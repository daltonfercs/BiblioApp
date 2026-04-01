# BiblioApp 📚
### Gestor de Bibliotecas Personales

BiblioApp es una aplicación móvil intuitiva y elegante diseñada para los amantes de la lectura que desean llevar un control digital completo de su colección de libros. Olvídate de los excels complicados o de no recordar qué libros tienes; BiblioApp te permite catalogar, buscar y organizar tu biblioteca personal de forma sencilla y eficiente.

---

## 🎨 Conceptos Visuales y Funcionalidades Clave

Para este proyecto, se han diseñado conceptos visuales enfocados en la experiencia del usuario (UX) y la estética del Material Design. Aquí te mostramos cómo se han proyectado las pantallas principales para ofrecer una interfaz limpia y moderna:


### 1. Panel de Inicio (Dashboard): "Mi Biblioteca"

La pantalla de inicio está diseñada para ofrecer una vista global y ordenada de toda tu colección.
* **Vista en Cuadrícula:** Visualiza las portadas de tus libros en un diseño de tarjeta limpio.
* **Barra de Búsqueda:** Encuentra rápidamente cualquier libro por título, autor o género.
* **Acceso Rápido:** Un botón flotante (+) para agregar nuevos títulos instantáneamente.

### 2. Detalle del Libro y Gestión de Estado

Al seleccionar un libro, accedes a una ficha detallada con toda su información.
* **Ficha Completa:** Portada, título, autor, año de publicación, resumen de la trama y calificación (estrellas).
* **Gestión de Estados:** Marca los libros como 'leídos', 'leyendo' o 'por leer' para llevar un seguimiento de tu progreso.

### 3. Búsqueda y Escáner Avanzado

La aplicación está proyectada para facilitar la entrada de datos.
* **Escáner Integrado:** *(Concepto)* Usar la cámara para escanear el código de barras del libro e importar la información automáticamente.
* **Búsqueda Externa:** Conectarse a bases de datos de libros en línea para obtener información precisa sin escribirlo todo manualmente.

---

## 🛠️ Tecnologías y Arquitectura

Este proyecto se ha desarrollado siguiendo las mejores prácticas de la industria para garantizar un código limpio, escalable y mantenible.

* **Lenguaje:** Kotlin 100%
* **Plataforma:** Android Native SDK
* **Arquitectura:** MVVM (Model-View-ViewModel) con Clean Architecture.
* **Diseño:** Material Design
* **Componentes de Jetpack:**
    * *Navigation Component:* Para una navegación fluida entre fragmentos.
    * *ViewBinding/DataBinding:* Para la vinculación segura de vistas.
    * *ViewModel & LiveData:* Para la gestión de estados de la UI.
    * *Room Database:* Para el almacenamiento persistente y sin conexión (offline-first).
    * *Coroutine/Flow:* Para la gestión eficiente de procesos asíncronos y flujos de datos.

---

## 🚀 Instalación y Configuración

Sigue estos pasos para compilar y ejecutar el proyecto en tu entorno local.

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/daltonfercs/BiblioApp.git](https://github.com/daltonfercs/BiblioApp.git)
    ```
2.  **Abrir en Android Studio:**
    Abre Android Studio y selecciona `File > Open`, luego navega hasta la carpeta del proyecto clonado.
3.  **Sincronizar Gradle:**
    Android Studio detectará automáticamente el archivo `build.gradle` y te pedirá que sincronices el proyecto. Haz clic en el botón de sincronización de Gradle en la parte superior derecha.
4.  **Ejecutar:**
    * Selecciona un dispositivo virtual (AVD) o un dispositivo físico conectado.
    * Haz clic en el botón verde de "Play" para compilar y ejecutar la aplicación.

*(Nota: Asegúrate de tener instalado el SDK de Android y la versión de Kotlin correspondiente).*

---

## 📄 Licencia y Autor

* **Autor:** Dalton Fercs ([GitHub](https://github.com/daltonfercs))
* **Licencia:** Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
