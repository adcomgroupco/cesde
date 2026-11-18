# CESDE — Ruta Estratégica 2026

Mini-landing de presentación estratégica de pauta digital para CESDE.

## URLs (GitHub Pages)
- **Inicio:** `/index.html`
- **Ruta estratégica:** `/ruta.html`
- **Ruta de sostenimiento septiembre:** `/ruta-sostenimiento-septiembre.html`
- **Línea de tiempo TECPER:** `/linea-de-tiempo-tecper.html`
- **Reporte implementación:** `/tecnicos/anuncios-inicio-2026-2.html`
- **Privacidad:** `/legal/privacidad.html` *(requerida por Meta App Review)*
- **Términos:** `/legal/terminos.html` *(requerida por Meta App Review)*

## Estructura
```
assets/
  css/
    index.css                  ← estilos landing principal
    ruta.css                   ← estilos presentación interactiva
    reporte.css                ← estilos reporte de anuncios
    legal.css                  ← estilos compartidos privacy + terms
    linea-de-tiempo-tecper.css ← estilos línea de tiempo TECPER
  js/
    ruta.js                    ← lógica slides, mapa y filtros
    linea-de-tiempo-tecper.js  ← series semanales, columnas y tabla
pages/
  reporte-implementacion.html
index.html
ruta.html
ruta-sostenimiento-septiembre.html
linea-de-tiempo-tecper.html
legal/privacidad.html
legal/terminos.html
tiktokA7w...txt                ← verificación TikTok (no borrar)
```

## Línea de tiempo TECPER (may–jul 2026)

Evolución semanal del CPA de las 37 campañas `TECPERF*` (Medellín, Bello, Rionegro) del semestre 2026-2, con cada ajuste fechado y atribuido a la aplicación que lo ejecutó.

| | |
|---|---|
| **Cuenta** | ADCOM 2023 - CESDE (`act_236065353543774`) |
| **Ventana** | 6 may — 31 jul 2026 (13 semanas) |
| **Inversión** | $80.263.177 |
| **Leads** | 16.097 (`onsite_conversion.lead_grouped`) |
| **CPA promedio** | $4.986 · pico $8.475 (15–21 jun) · cierre $2.694 (27–31 jul) |

**Hitos.** Rotación de piezas `_29/05` el 1 jun · recorte y reconstrucción de presupuestos 22 y 25 jun · **reemplazo de los 33 formularios el 30 jun** (se quitan 4 preguntas de perfilamiento, entran 2 filtros de admisión) · piezas «Últimos cupos» y escalado 6–7 jul · estandarización de nomenclatura 22 jul · piezas «Sold out» 27 jul · cierre a presupuesto mínimo 28 jul.

**Atribución.** Meta registra qué aplicación hizo cada cambio: 2.952 de 6.133 eventos salieron de `App Marketing Adcom` (Meta Ads CLI), y las fechas coinciden con los scripts de `scripts/clients/cesde/` en el repo de la herramienta. El resto se hicieron a mano desde Power Editor.

## Cliente
**CESDE** · sebastian@adcom.group


## Organización de documentos

La portada es [index.html](index.html). Cada carpeta agrupa un tema. Los nombres
usan minúsculas, guiones y fechas `AAAA-MM` o `AAAA-MM-DD` cuando distinguen cortes.
El nombre del cliente vive en el repositorio y no se repite en cada URL.
Los títulos de la portada y de cada documento usan el mismo nombre.

Los HTML en las rutas anteriores solo redirigen para conservar enlaces compartidos,
incluidos sus parámetros y secciones. Los documentos nuevos se guardan en las
carpetas temáticas y se enlazan desde la portada.

| Documento | Ruta |
|---|---|
| [Seguimiento semanal](tableros/seguimiento.html) | `tableros/seguimiento.html` |
| [Plan de Técnicos · 2026-2](tecnicos/plan-2026-2.html) | `tecnicos/plan-2026-2.html` |
| [Plan de Técnicos · 2027-1](tecnicos/plan-2027-1.html) | `tecnicos/plan-2027-1.html` |
| [Historial de pauta · 2026-2](tecnicos/historial-2026-2.html) | `tecnicos/historial-2026-2.html` |
| [Creatividades de Técnicos · 2026-2](tecnicos/creatividades-2026-2.html) | `tecnicos/creatividades-2026-2.html` |
| [TikTok de Técnicos · Mayo a julio 2026](tecnicos/tiktok-2026-05-a-07.html) | `tecnicos/tiktok-2026-05-a-07.html` |
| [WhatsApp de Técnicos · Julio 2026](tecnicos/whatsapp-2026-07.html) | `tecnicos/whatsapp-2026-07.html` |
| [Anuncios de inicio · 2026-2](tecnicos/anuncios-inicio-2026-2.html) | `tecnicos/anuncios-inicio-2026-2.html` |
| [Anuncios de últimos cupos · 27 julio 2026](tecnicos/anuncios-cupos-2026-07-27.html) | `tecnicos/anuncios-cupos-2026-07-27.html` |
| [Anuncios de extensión · 5 agosto 2026](tecnicos/anuncios-extension-2026-08-05.html) | `tecnicos/anuncios-extension-2026-08-05.html` |
| [Anuncios generales · 9 octubre 2026](tecnicos/anuncios-generales-2026-10-09.html) | `tecnicos/anuncios-generales-2026-10-09.html` |
| [Anuncios por programa · 19 octubre 2026](tecnicos/anuncios-programas-2026-10-19.html) | `tecnicos/anuncios-programas-2026-10-19.html` |
| [Calidad de contactos · Agosto 2026](empresas/calidad-2026-08.html) | `empresas/calidad-2026-08.html` |
| [Contactos de Empresas · Septiembre 2026](empresas/contactos-2026-09.html) | `empresas/contactos-2026-09.html` |
| [Creatividades de Empresas · Octubre 2026](empresas/creatividades-2026-10.html) | `empresas/creatividades-2026-10.html` |
| [Creatividades de Empresas · Octubre y noviembre 2026](empresas/creatividades-2026-10-a-11.html) | `empresas/creatividades-2026-10-a-11.html` |
| [Metas y costo por contacto · Agosto a octubre 2026](empresas/metas-2026-08-a-10.html) | `empresas/metas-2026-08-a-10.html` |
| [Anuncios de Empresas · Agosto 2026](empresas/anuncios-2026-08.html) | `empresas/anuncios-2026-08.html` |
| [Anuncios de Empresas · 1 septiembre 2026](empresas/anuncios-2026-09-01.html) | `empresas/anuncios-2026-09-01.html` |
| [Anuncios de Empresas · 16 septiembre 2026](empresas/anuncios-2026-09-16.html) | `empresas/anuncios-2026-09-16.html` |
| [Anuncios de Empresas · 30 octubre 2026](empresas/anuncios-2026-10-30.html) | `empresas/anuncios-2026-10-30.html` |
| [Prueba de logo en Empresas · 17 noviembre 2026](empresas/prueba-logo-aliado-2026-11-17.html) | `empresas/prueba-logo-aliado-2026-11-17.html` |
| [Plan de Microcredenciales · 2026](microcredenciales/plan-2026.html) | `microcredenciales/plan-2026.html` |
| [Resultados de Microcredenciales · 8 octubre 2026](microcredenciales/resultados-2026-10-08.html) | `microcredenciales/resultados-2026-10-08.html` |
| [Anuncios de Microcredenciales · 8 octubre 2026](microcredenciales/anuncios-2026-10-08.html) | `microcredenciales/anuncios-2026-10-08.html` |
| [Anuncios de gastronomía · 11 noviembre 2026](educon/anuncios-gastronomia-2026-11-11.html) | `educon/anuncios-gastronomia-2026-11-11.html` |
| [Plan de sostenimiento · Septiembre 2026](planes/sostenimiento-2026-09.html) | `planes/sostenimiento-2026-09.html` |
| [Prueba en ChatGPT Ads · Noviembre 2026](planes/chatgpt-ads-2026-11.html) | `planes/chatgpt-ads-2026-11.html` |
| [Gestión de Empresas, Técnicos y CRM · Noviembre 2026](informes/gestion-2026-11.html) | `informes/gestion-2026-11.html` |
| [Spotify y pantallas · Junio y julio 2026](informes/spotify-y-pantallas-2026-06-a-07.html) | `informes/spotify-y-pantallas-2026-06-a-07.html` |
| [Perfiles de audiencia](recursos/audiencias.html) | `recursos/audiencias.html` |
| [Zonas seguras de diseño](recursos/zonas-seguras.html) | `recursos/zonas-seguras.html` |
| [Política de privacidad](legal/privacidad.html) | `legal/privacidad.html` |
| [Términos del servicio](legal/terminos.html) | `legal/terminos.html` |
