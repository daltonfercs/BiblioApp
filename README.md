# 📚 BiblioApp (Android Library Management)

BiblioApp es una aplicación móvil nativa para Android diseñada para facilitar la gestión de libros, miembros y préstamos en una biblioteca. 

El ecosistema móvil utilizando las mejores prácticas, patrones de diseño y herramientas de desarrollo actuales de Android.

## ✨ Características Principales

* **Gestión de Libros:** Agregar, editar y listar el catálogo de libros disponibles.
* **Gestión de Miembros:** Registro y administración de los usuarios de la biblioteca.
* **Sistema de Préstamos:** Emisión y devolución de libros de forma sencilla y rápida.
* **Panel de Control (Dashboard):** Vista general del estado de la biblioteca e inventario.
* **Modo Oscuro:** Soporte nativo para temas claros y oscuros integrados con Material Design 3.

## 🛠️ Stack Tecnológico y Arquitectura

El proyecto está desarrollado con **Kotlin** y sigue la arquitectura **MVVM** (Model-View-ViewModel) recomendada por Google, garantizando un código limpio, escalable y fácil de mantener.

* **UI:** [Jetpack Compose](https://developer.android.com/jetpack/compose) - Kit de herramientas moderno y declarativo para construir interfaces nativas.
* **Base de Datos Local:** [Room](https://developer.android.com/training/data-storage/room) - Capa de abstracción sobre SQLite para un acceso fluido a los datos.
* **Asincronismo y Reactividad:** [Corrutinas](https://kotlinlang.org/docs/coroutines-overview.html) y [Flow](https://kotlinlang.org/docs/flow.html) de Kotlin.
* **Inyección de Dependencias:** [Hilt](https://dagger.dev/hilt/) (Recomendado/En progreso).
* **Navegación:** Jetpack Navigation Compose.

## 🚀 Empezando (Getting Started)

Para probar este proyecto en tu entorno local:

1.  Clona este repositorio:
    ```bash
    git clone [https://github.com/tu-usuario/BiblioApp.git](https://github.com/daltonfercs/BiblioApp.git)
    ```
2.  Abre el proyecto en **Android Studio** (se recomienda la versión más reciente, Iguana o superior).
3.  Espera a que Gradle sincronice todas las dependencias.
4.  Ejecuta la aplicación en un emulador o dispositivo físico (API 24+).

## 🗺️ Hoja de Ruta (Roadmap de Migración)

- [x] Configuración inicial del proyecto con Jetpack Compose.
- [ ] Diseño de las Entidades y DAOs con Room (Migración de Apache Derby).
- [ ] Implementación del Dashboard principal.
- [ ] Pantallas de registro de Libros y Miembros.
- [ ] Lógica de negocio para préstamos y devoluciones.
- [ ] Explorar alternativas para la exportación a PDF y notificaciones.

## 👨‍💻 Autor

Desarrollado por **Dalton** - Desarrollador Android.
