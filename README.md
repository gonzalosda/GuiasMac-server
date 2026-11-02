# GuiasMac-server			v1
****Notas****
    
**Servidor:**

Idioma de servidor: Español

Idioma de codigo de servidor: archivos .json

Versión actual: v1


***Aplicación***
Versión 0.5 Dev (No al público)

Versión centrada en la finalización del sistema de distribución remota de guías. Se completa el flujo de sincronización entre la aplicación y el servidor de GitHub, permitiendo descargar, actualizar y almacenar automáticamente las guías en el dispositivo mediante control de versiones, sin necesidad de publicar una nueva versión de la aplicación.

No disponible en la App Store ni TestFlight.

Novedades

✔ Implementación del sistema automático de descarga de guías desde GitHub.
✔ Descompresión automática de archivos ZIP.
✔ Importación automática de las guías a SwiftData.
✔ Sistema de actualización mediante control de versiones.
✔ Detección automática de guías ya instaladas.
✔ Sustitución automática de guías cuando existe una versión más reciente.
✔ Integración de NetworkMonitor.
✔ Detección en tiempo real del estado de la conexión a Internet.
✔ Aviso visual cuando no existe conexión a Internet durante el inicio de la aplicación.
✔ Animación de advertencia al intentar acceder sin conexión.
✔ Mejora del proceso de inicialización de StartupManager.

Mejoras

✔ Optimización del sistema de sincronización de contenido.
✔ Se evita descargar guías que ya se encuentran actualizadas.
✔ Mejor gestión del almacenamiento local de archivos ZIP y PDF.
✔ Optimización del proceso de actualización de SwiftData.
✔ Mayor estabilidad durante la sincronización inicial.
✔ Mejor gestión de errores durante la descarga de contenido.
✔ Código reorganizado y optimizado para futuras ampliaciones.

Correcciones

✔ Solucionado un problema que duplicaba las guías al actualizar su versión.
✔ Corregidos errores durante la lectura de manifest.json.
✔ Corregida la extracción de archivos ZIP generados en macOS.
✔ Se ignoran correctamente los directorios __MACOSX y archivos ._* durante la descompresión.
✔ Corregidos diversos errores relacionados con la actualización automática de contenido.

Pendiente

* Solucion de error en el panel de administrador
* Descarga automática de imágenes de las guías.
* Sistema de noticias remotas.
* Indicador de progreso durante las descargas.
* Comprobación de versión mínima de la aplicación
* Sistema de actualización forzada de la aplicación.
* Sincronización diferencial avanzada para futuras versiones.
* Integración futura con CloudKit 

⸻

Notas

* La versión 0.5 completa la infraestructura principal de distribución remota de contenido iniciada en la versión 0.4. A partir de esta versión, las guías pueden añadirse o actualizarse desde el servidor sin necesidad de publicar una nueva versión de GuiasMac, estableciendo la base para futuras funciones como noticias, imágenes remotas y actualizaciones automáticas del contenido.
