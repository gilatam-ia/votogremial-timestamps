# Anclaje de sello de tiempo — CódigoVoto

Este repositorio público registra el **hash** de cada acta generada por
[CódigoVoto](https://app.votacion.grupointelecto.cl) (Grupo Intelecto) como evidencia
de que ese documento existía en un momento determinado.

## Qué es

Cada archivo en `anclajes/` contiene únicamente:
- El **hash SHA-256** del acta (nunca el contenido del acta ni datos personales).
- La referencia del gremio/sesión.
- La fecha de generación según el sistema.

Al quedar como un commit público en GitHub, ese hash recibe un **timestamp
independiente** (el reloj del servidor de GitHub, no el de CódigoVoto), verificable
por cualquiera en `https://github.com/gilatam-ia/votogremial-timestamps/commits/main`.

## Qué NO es

- **No es un prestador de servicios de certificación (PSC) acreditado** ante la
  Entidad Acreditadora del Ministerio de Economía de Chile.
- **No constituye Firma Electrónica Avanzada** en los términos del artículo 2° letra
  g) de la Ley N° 19.799, ni el "fechado electrónico de prestador acreditado" al que
  se refiere el artículo 5° de esa misma ley.
- **No reemplaza asesoría legal.** Es un mecanismo técnico adicional de integridad,
  gratuito, pensado como evidencia complementaria — no como certificación legal por
  sí sola.

## Cómo verificar un hash

1. Busca el commit correspondiente en el historial de este repositorio.
2. Confirma que el hash coincide con el que muestra el acta descargada desde
   CódigoVoto.
3. La fecha del commit (visible en GitHub) es la evidencia de existencia-en-el-tiempo.

---
Grupo Intelecto · CódigoVoto
