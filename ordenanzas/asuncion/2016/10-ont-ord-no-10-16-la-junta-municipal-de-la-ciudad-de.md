---
numero: "10"
anio: 2016
titulo: "ont. Ord. Nº 10/16. LA JUNTA MUNICIPAL DE LA CIUDAD DE ASUNCIÓN, REUNIDA EN CONCEJO ORDENA: rt. 1"
short_title: "ont. Ord. Nº 10/16. LA JUNTA MUNICIPAL DE LA CIUDAD DE ASUNCIÓN, REUNIDA EN CONCEJO ORDENA: rt. 1"
municipio: asuncion
fuente: asuncion.gov.py
source: https://www.asuncion.gov.py/wp-content/uploads/2019/06/ORD-2016-10.pdf
ocr: opencode-go/deepseek-v4-flash
fecha_sancion: 2016-02-15
---

Listo. Extraje el texto del PDF (OCR con `pdftotext` + limpieza manual de artefactos) y guardé el Markdown en:

`files/ordenanzas/asuncion/10-2016.md`

**Resumen:** Ordenanza Nº 10/2016 que modifica el Inciso e) del Artículo 1º de la Ordenanza Nº 481/14, elevando de 2.500 a **3.000** el límite máximo de máquinas electrónicas de juegos de azar habilitadas en Asunción. Incluye 4 artículos: la modificación del límite, el encargo de adjudicar las 500 nuevas máquinas, dejar firme el resto de la ordenanza anterior, y encomendar control e inhabilitación de máquinas en mercados municipales. Sancionada el 9 de marzo de 2016.

Nota: el OCR del PDF original tiene bastantes artefactos (caracteres rotos tipo `m` → `rn`, `6` → `ó`, etc.). Para una versión más precisa, el pipeline documentado en `CLAUDE.md` sugiere usar vision-LLM vía `opencode run -m <modelo> -f <pdf> -- <prompt>`.