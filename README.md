# Casa en Orden 2.0 — versión de prueba

Esta es una vista previa funcional y **separada de tu app 1.0**. Todavía no se debe sobrescribir el repositorio original.

## Probarla en iPhone sin reemplazar tu aplicación actual
1. Descomprime este ZIP desde Archivos.
2. Crea en GitHub un repositorio público **distinto** llamado `casa-en-orden-v2-prueba`.
3. Sube los **nueve** archivos de esta carpeta a la raíz del repositorio (no subas el ZIP).
4. En Settings > Pages selecciona Deploy from a branch, `main`, `/(root)` y Save.
5. Abre `https://TU-USUARIO.github.io/casa-en-orden-v2-prueba/` desde Safari.
6. Puedes probarla desde Safari antes de añadir otro ícono a Inicio. No modifica el repositorio original.

## Funciona durante la prueba
- Lista por categorías, despensa y vencimientos.
- Menús generados usando productos registrados en la despensa; separa adultos y bebé (edad predeterminada 8 meses), edición de recetas y lista de ingredientes faltantes.
- Tareas por zonas y frecuencias; calendario de citas y recordatorios (solo **dentro de la aplicación**).
- Pagos de servicios, tarjetas, planes móviles; registro automático de egresos al marcar pagado.
- Finanzas: ingresos, egresos, inversiones, soportes (fotos y PDF hasta 4 MB), copias JSON.
- Impresión de menús semanales y calendario: desde el diálogo de impresión en iPhone se puede guardar PDF.
- Funciona de manera local y guarda los datos de esta prueba en el iPhone (localStorage + IndexedDB).

## Limitaciones importantes
- La invitación de familiares y sincronización en tiempo real **todavía NO están activadas**. Requieren cuentas, base de datos y almacenamiento privado con permisos. No se deben almacenar soportes personales en GitHub público.
- Las alertas son visibles dentro de la app. **No hay notificaciones automáticas** cuando la app está cerrada.
- Los menús son sugerencias de una biblioteca pequeña de recetas, basadas en coincidencias por nombres de ingredientes. No son un plan nutricional médico y hay que revisar seguridad alimentaria del bebé.
- Las recetas elegidas manualmente pueden requerir ingredientes que no estén disponibles, y la app lo indicará.
- Al probar otro enlace o borrar datos del navegador, podrías perder registros. Exporta copias de seguridad periódicamente.
- Si publicas la prueba bajo otro repositorio en el **mismo dominio de usuario** de GitHub Pages, podrá detectar datos de la v1 en la misma origin del navegador y **copiarlos** para la prueba. No sobrescribirá la clave de almacenamiento de la v1.
