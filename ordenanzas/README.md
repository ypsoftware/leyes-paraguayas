# Ordenanzas municipales

Ordenanzas de las Juntas Municipales del Paraguay, organizadas por municipio y año.
Cada ordenanza es un archivo Markdown extraído del PDF original mediante OCR + limpieza LLM.

## Estado

- Total: **316 ordenanzas**
- Municipios: **1** (Asuncion)
- Años cubiertos: **2015–2025**
- Fechas de sanción extraídas: **294/316 (93%)**

## Asuncion

Total: **316 ordenanzas**.

| Año | Ordenanzas | Con fecha |
|----:|----------:|----------:|
| [2015](asuncion/2015/) | 3 | 2 |
| [2016](asuncion/2016/) | 32 | 30 |
| [2017](asuncion/2017/) | 40 | 37 |
| [2018](asuncion/2018/) | 47 | 42 |
| [2019](asuncion/2019/) | 52 | 50 |
| [2020](asuncion/2020/) | 34 | 31 |
| [2021](asuncion/2021/) | 12 | 12 |
| [2022](asuncion/2022/) | 39 | 37 |
| [2023](asuncion/2023/) | 9 | 7 |
| [2024](asuncion/2024/) | 27 | 26 |
| [2025](asuncion/2025/) | 21 | 20 |

## Pipeline

1. Scrape sitio oficial → lista PDFs por año (TSV)
2. Download PDFs originales
3. OCR con `ocrmypdf -l spa` (Tesseract español); fallback `--rotate-pages --deskew` para escaneos rotados
4. Extracción de texto con `pdftotext`
5. Limpieza LLM: junta palabras OCR partidas, normaliza símbolos (Nº, º), reflow párrafos, extrae título del cuerpo
6. Extracción de fecha de sanción del cuerpo OCR (regex de patrones "Sesión Ordinaria del DD de mes de YYYY", "DD/MM/YYYY", etc.)
7. Pase vision-LLM (`mimo-v2-omni`) sobre PDF para datos faltantes
8. Commit por ordenanza, dated por fecha de sanción

## Formato de cada ordenanza

```yaml
---
numero: "167"
anio: 2025
titulo: "DECLARACIÓN DE EMERGENCIA AMBIENTAL ANTE FENÓMENOS CLIMÁTICOS..."
short_title: "Declaración de emergencia ambiental ante fenómenos climáticos 2025"
municipio: asuncion
fuente: asuncion.gov.py
source: https://www.asuncion.gov.py/wp-content/uploads/2025/05/ord-167.25.pdf
ocr: ocrmypdf+tesseract-spa
---
```

Cada commit de ordenanza incluye trailers:
- `Source-Ord-Id: <municipio>/<numero>/<anio>` (idempotencia)
- `Source: <URL del PDF original>`
- `Source-Date: YYYY-MM-DD` (fecha de sanción)
- `OCR-Engine: ocrmypdf+tesseract-spa[+rotate+deskew]`

## Fuente

Sitios oficiales de cada municipio. Las ordenanzas son de dominio público.

<!-- Auto-generado por copylegal/build_ordenanzas.py — no editar manualmente -->
