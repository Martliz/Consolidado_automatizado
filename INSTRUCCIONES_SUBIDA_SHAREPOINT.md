# Archivos para subir a SharePoint

## 1) Crear la lista con las causas

Sube este archivo a SharePoint al crear una lista nueva desde CSV:

- `causas_sharepoint.csv`

### Nombre exacto de la lista
`CausasCallCenter`

## 2) Subir la página HTML

Sube este archivo a una biblioteca de documentos del mismo sitio:

- `guia_atencion_sharepoint_final.html`

## 3) Configurar el Embed en la página de SharePoint

1. Crea o edita una página moderna en SharePoint.
2. Agrega el web part **Embed**.
3. En el campo del Embed pega la **URL directa del archivo HTML**.
4. Publica la página.

### Importante
Usa la **URL directa del archivo HTML** dentro de SharePoint.

Debe verse parecido a esto:

`https://tuempresa.sharepoint.com/sites/TU_SITIO/Documentos%20compartidos/TU_CARPETA/guia_atencion_sharepoint_final.html`

No uses:

- links largos de Teams para compartir
- rutas de tu disco C:
- `file:///`

## 4) Primera configuración al abrir la guía

Cuando abras el HTML por primera vez, te pedirá:

### URL del sitio SharePoint
Debe ser solo la URL del sitio, por ejemplo:

`https://tuempresa.sharepoint.com/sites/callcenter`

### Nombre de la lista
`CausasCallCenter`

## 5) Permisos que deben tener los ejecutivos

Los ejecutivos deben tener al menos:

- lectura sobre la lista `CausasCallCenter`
- acceso al archivo `guia_atencion_sharepoint_final.html`
- acceso a la página de SharePoint donde está el Embed

## 6) Qué corrige esta versión

- elimina la pantalla de carga duplicada
- corrige textos que todavía decían Google Sheets
- corrige el botón de recarga para SharePoint
- deja una sola inicialización de la app
- entrega un CSV con IDs únicos

## 7) Si no carga

### Revisa esto primero
- que la lista se llame exactamente `CausasCallCenter`
- que la URL del sitio no sea un link de Teams
- que el archivo HTML abra por sí solo en el navegador
- que los usuarios tengan permisos de lectura
- que SharePoint permita mostrar ese contenido en Embed
