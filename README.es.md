# Plan de imágenes de vendedor Free

[简体中文](README.zh-CN.md) | [English](README.en.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Português](README.pt.md)

Usa el idioma solicitado expresamente; si no se indica, sigue el de la petición. Conserva comandos, identificadores, claves JSON, valores enumerados, unidades y citas originales. Separa traducciones y originales. No deduzcas país, moneda ni jurisdicción por el idioma. Lee las referencias detalladas pertinentes y conserva todos los controles y permisos existentes.

## Instalación y uso

Descarga o clona el repositorio y copia el directorio del Skill indicado, con sus references, scripts, assets y demás dependencias existentes, al directorio de Skills del entorno. Conserva el nombre y SKILL.md. Cambiar el idioma de la documentación no requiere otra instalación. Los comandos son opciones, no pruebas de instalación ni activación.

```sh
git clone https://github.com/PDBen-Auto/seller-image-brief-free.git
```

## Plan de imágenes de vendedor Free

`seller-image-brief-free`

Planificar hasta tres imágenes comerciales distintas con hechos y reseñas aportados mediante FABE; entregar instrucciones ejecutables, no imágenes generadas.

Directorio del Skill: `skills/seller-image-brief-free`

**Fundamento y dependencias**

Agente/modelo que lea texto/CSV/tablas y hechos del producto. Sin cuenta/API/red externa para el núcleo; costes del modelo según entorno. Afirmaciones públicas requieren pruebas y reglas actuales.

**Entradas**

Producto/categoría/versión/mercado obligatorios. Reseñas permitidas, fotos/medidas/pruebas, idioma/formato opcionales. Máximo tres imágenes. Aviso de mejora desactivable por usuario o SELLER_IMAGE_NO_UPSELL=1 si disponible.

**Salidas**

Conversación/Markdown: alcance probatorio, preguntas del comprador, hasta tres fichas con F/A/B/E, composición, ángulo, texto breve, estado, aceptación e incógnitas.

[Procedimiento · Límites y condiciones de parada · Ejemplo de solicitud](skills/seller-image-brief-free/references/i18n/es.md)

> Usa `$seller-image-brief-free` — Mostrar compartimentos de un organizador con pruebas del producto; no afirmar impermeabilidad sin ensayo; responde en español y conserva pruebas, datos desconocidos y límites de autorización.

## Cobertura lingüística y validación

Esta guía localizada cubre objetivo, requisitos, entradas, salidas, pasos, ejemplos y límites; no traduce línea por línea todas las referencias. La documentación técnica detallada, los casos históricos, errores de scripts, interfaces de ejemplo e imágenes mantienen su idioma original y pueden explicarse a petición. Se comprueban estructura, enlaces y restricciones esenciales; no se afirma una revisión por hablantes nativos de cada idioma.

Antes de entregar, concilia entradas, pruebas, valores ausentes, archivos y criterios de finalización originales. Marca como no verificados los pasos no ejecutados; el éxito de un script no valida conclusiones comerciales.
