# landing-clinicaguemes

Landing de demostración para **Clínica Güemes — Medicina Integral** (Villa Krause, Rawson, San Juan, Argentina).

Sitio estático de una sola página (`index.html`, CSS y JS inline), mobile first, con:

- Presentación de la clínica y sus **especialidades** (clínica médica, cardiología, dermatología, ginecología, pediatría, traumatología, nutrición y laboratorio) y sus **profesionales**.
- **Sistema de turnos en línea** interactivo: especialidad → profesional → día → horario (con turnos de mañana y de tarde), con confirmación de resumen y botón que abre WhatsApp con los datos cargados.
- **Recordatorios automáticos por WhatsApp** (explicación del flujo).
- Cómo el paciente **pide y consulta sus estudios**.
- **Obras sociales y formas de pago** (a modo de texto; sin convenios concretos: «consulte por su obra social»).
- **Reseñas** (20 · 4.8★ en Google) y **ubicación** con mapa.

Contacto: WhatsApp / teléfono **+54 264 482-2705** (`wa.me/5492644822705`), con mensaje precargado.

## Despliegue

Se construye con un `Dockerfile` de dos líneas (`nginx:alpine` + copia de los archivos) y se publica en EasyPanel desde este repositorio (rama `main`).

## Nota

Sitio de referencia hecho por Nocodeveloper. Los profesionales, horarios, obras sociales y reseñas que se muestran son ilustrativos para esta demostración; no reemplazan información médica. Para la versión final se usan los datos y las fotos reales de la clínica.
