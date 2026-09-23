MBS – Gestión real de lecciones

Versión preparada para integración con ESP32-S3.

Cambios principales:
- Eliminado el modo demo y toda detección de GitHub Pages/file:.
- Restaurado el CSS original.
- Eliminado el script externo inyectado por Kaspersky.
- Guardar en MBS usa siempre POST /api/lecciones/upload?name=...
- Actualizar lista usa siempre GET /api/lecciones
- La carpeta de destino prevista sigue siendo /lecciones/.
- La herramienta no modifica /web/.

Importante: esta versión está diseñada para ser servida por el ESP32-S3.
Si se abre desde GitHub Pages o como archivo local, la interfaz se verá, pero las operaciones de SD indicarán que MBS no está disponible.
