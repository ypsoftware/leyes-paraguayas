# Contribuir

Este repositorio contiene legislación paraguaya transcrita automáticamente desde [bacn.gov.py](https://www.bacn.gov.py). El objetivo es mantener una **transcripción fiel** del texto oficial, con historial git que refleje cómo cada ley modifica a otras.

## Qué aceptamos

### 1. Reportar errores de transcripción

Si encontrás un error en el texto de una ley (caracter raro, párrafo faltante, OCR defectuoso, etc.):

1. Abrí un issue indicando el archivo (`leyes/YYYY/NNNN-slug.md`) o el `bacn_id`.
2. Incluí cita literal del error y link al texto oficial en `https://www.bacn.gov.py/leyes-paraguayas/<bacn_id>/texto` para verificación.
3. Si ya corregiste localmente, abrí un PR.

**No aceptamos** "correcciones" que alteren el texto oficial, aun si tiene erratas del original — nuestra tarea es reflejar lo publicado, no enmendarlo.

### 2. Mejorar detección de mutaciones

Algunas leyes modificatorias no se aplicaron correctamente como commit sobre la ley base. Si notás un caso así (ej. Ley X debería modificar Ley Y pero no aparece reflejado en el historial de Y):

1. Abrí un issue con los `bacn_id` origen y destino.
2. Idealmente, indicá qué tipo de mutación es (sustitución, derogación, incorporación).

### 3. Metadatos

Mejorar front-matter YAML: agregar campos como `tipo_ley`, `materia`, `organo_emisor`, enlaces a leyes relacionadas, etc.

### 4. Herramientas

Las herramientas de conversión viven en un repositorio separado. Si querés mejorar el parser de cláusulas modificatorias, el scraper, o el aplicador de mutaciones, contactá al mantenedor.

## Qué NO aceptamos

- Comentarios interpretativos, notas doctrinarias, o "correcciones" al texto oficial.
- Traducciones (este repo es solo en castellano, idioma oficial junto con guaraní).
- Leyes ficticias, propuestas, o proyectos no promulgados.
- Contenido con copyright de terceros (resúmenes de editoriales, análisis académicos).

## Proceso

1. Fork del repo.
2. Branch por cambio: `fix/ley-<bacn_id>-<descripcion>`.
3. Commit con mensaje claro referenciando el issue o la ley.
4. PR contra `main`.

## Sobre la licencia

Este repo **no tiene licencia propia** porque el contenido no es obra original: son leyes del Paraguay que son de dominio público por Art. 2, Ley 1328/98. Cualquiera puede copiar, redistribuir, reutilizar o modificar el texto para cualquier fin.

La estructura y formato de los archivos (nombres, front-matter, etc.) son convenciones editoriales sin reclamo de autoría. Inspiración: [legalize-dev/legalize-es](https://github.com/legalize-dev/legalize-es).
