GS ASISTENTE — V1.0 MVP
=======================

Aplicación independiente de GS Diagnósticos.

FUNCIONES INCLUIDAS
- Varias visitas guardadas simultáneamente.
- ID numérico automático AAAAMMDD0001.
- Guardado automático offline con IndexedDB.
- Sede y municipio dependiente, con las listas de GS Diagnósticos.
- Varias áreas recorridas por visita y contexto activo.
- Varios CD por visita, GPS opcional exacto o aproximado.
- Evaluación técnica mediante opciones múltiples.
- NITS local: descripción de infraestructura, clasificación de hallazgos y sugerencia de estado.
- Hallazgos sociales, ambientales, prediales, institucionales y de acceso.
- Fotografías múltiples, pie de foto y herramienta para marcar en rojo.
- Gestión social, contactos y pendientes opcionales.
- Alertas mediante archivo de calendario .ics cuando se define fecha.
- Vista previa completa.
- Word editable con portada, logo INMEL solo en portada, logo Gestión Social en páginas internas,
  KPI, estados en color, Arial, párrafos justificados y glosario dinámico.
- Exportación e importación de respaldo JSON.

INSTALACIÓN / PRUEBA
1. Publique todos los archivos juntos en un servidor HTTPS (Vercel, GitHub Pages, etc.).
2. Abra index.html desde el enlace publicado.
3. Instale como PWA desde el navegador cuando esté disponible.

IMPORTANTE
- No abrir directamente index.html desde el administrador de archivos: el navegador puede bloquear el Service Worker
  y algunas funciones de descarga.
- El NITS incluido en esta versión funciona localmente mediante reglas y biblioteca de redacción.
- La mejora avanzada en línea y la sincronización con el Libro Maestro quedan para una fase posterior.
- Generar el Word NO borra la visita. La información permanece hasta que se elimine manualmente.


V2.1 CORRECCIONES:
- Icono GS Asistente actualizado.
- CD en mayúsculas alfanuméricas.
- kVA mediante lista desplegable.
- Estado asignado únicamente por NITS.
- GPS reubicado debajo de coordenadas.
- Eliminada opción Mixta redundante.
- Dictado continuo con indicador visual.
- Nombres propios y siglas normalizados.
- Plantilla Word ajustada con KPI, tabla técnica y registro fotográfico.
