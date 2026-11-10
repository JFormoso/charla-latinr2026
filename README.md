# Crear un paquete R como infraestructura para documentos institucionales consistentes

**Jesica Formoso - Irene Vazano**

[LatinR 2026](https://latinr.org/)

Presentación oral (15 minutos)
Sesión: Manejo y gestión de datos
13:00 a 14:20 horas (UTC -5, hora Colombia)

## De qué trata

Flujo de trabajo basado en un paquete de R para centralizar y automatizar la producción de reportes y presentaciones con identidad visual institucional mediante Quarto. El paquete permite crear nuevos documentos a partir de plantillas y actualizar de forma centralizada colores, tipografías, logos y estilos, facilitando el mantenimiento, la consistencia visual y la adopción por equipos con distintos niveles de experiencia en R.

**Palabras clave:** identidad institucional, paquete de R, plantillas de Quarto

## Ideas centrales

- **Separar el contenido de la identidad.** Quien escribe edita un `.qmd`; quien mantiene el diseño actualiza el paquete.
- **Una sola fuente de verdad.** `_brand.yml` define colores, tipografías y logo, y lo leen tanto Quarto como R (por ejemplo, el tema y la paleta de ggplot2).
- **El paquete como vehículo de distribución.** Se instala en una línea, se versiona y suma funciones para crear y mantener documentos.

Funciones que se muestran en la charla:

| Función | Para qué sirve |
|---|---|
| `listar_tipos()` | Ver los tipos de documento disponibles |
| `nuevo_documento()` | Crear un documento nuevo con la identidad ya aplicada |
| `diagnosticar_brand()` | Detectar documentos con estilos desactualizados |
| `actualizar_brand()` | Aplicar la identidad vigente sin tocar el contenido |


## Enlaces

- Paquete: <https://github.com/metadocencia/metadocencia>
- Sitio de documentación: <https://metadocencia.github.io/metadocencia/>
- Contacto: jesica.formoso@gmail.com / irene.vazano@metadocencia.org

## Licencia

© 2026 Jesica Formoso e Irene Vazano.

Esta presentación y los materiales de este repositorio están bajo licencia [Creative Commons Atribución 4.0 Internacional (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.es). Se pueden compartir y adaptar, incluso con fines comerciales, siempre que se dé crédito a las autoras.

<!-- COMPLETAR: confirmar si el logo, las fuentes y la identidad visual de MetaDocencia quedan fuera de esta licencia -->

El paquete `metadocencia` tiene su propia licencia en su repositorio.
