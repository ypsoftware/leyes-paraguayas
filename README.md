# Leyes del Paraguay

Legislación paraguaya como repositorio Git — cada ley es un archivo Markdown, cada modificación un commit. **6,601 leyes** (1916–2026).

Extraídas de [bacn.gov.py](https://www.bacn.gov.py) (Biblioteca y Archivo del Congreso Nacional) y convertidas a Markdown. Cuando una ley modifica a otra, se aplica la modificación como commit sobre el archivo base, para que el historial git muestre cómo evolucionó el texto vigente.

Inspirado en [legalize-dev/legalize-es](https://github.com/legalize-dev/legalize-es) (legislación española con el mismo formato).

## Cómo usar

Ver la evolución de una ley:

```bash
git clone https://github.com/ypsoftware/leyes-paraguayas.git
cd leyes-paraguayas
git log --follow leyes/1996/834-organiza-el-regimen-electoral-de-la-republica.md
```

## Estado

- Leyes únicas: **6,601**
- Años cubiertos: **1916–2026**
- Relaciones detectadas: **2,217** (modifica / amplía / deroga / aprueba)
- Resueltas a ley destino: **1,469**
- Mutaciones aplicadas como commit: **646**

## Composición por tipo

| Tipo | Cantidad |
|------|---------:|
| sin_clasificar | 6,601 |

## Índice por año

- [1916](leyes/1916/) — 1 leyes
- [1951](leyes/1951/) — 3 leyes
- [1954](leyes/1954/) — 3 leyes
- [1955](leyes/1955/) — 2 leyes
- [1956](leyes/1956/) — 10 leyes
- [1957](leyes/1957/) — 4 leyes
- [1958](leyes/1958/) — 3 leyes
- [1960](leyes/1960/) — 4 leyes
- [1961](leyes/1961/) — 4 leyes
- [1962](leyes/1962/) — 3 leyes
- [1963](leyes/1963/) — 4 leyes
- [1964](leyes/1964/) — 5 leyes
- [1965](leyes/1965/) — 5 leyes
- [1966](leyes/1966/) — 5 leyes
- [1967](leyes/1967/) — 2 leyes
- [1968](leyes/1968/) — 8 leyes
- [1969](leyes/1969/) — 12 leyes
- [1970](leyes/1970/) — 6 leyes
- [1971](leyes/1971/) — 8 leyes
- [1972](leyes/1972/) — 5 leyes
- [1973](leyes/1973/) — 7 leyes
- [1974](leyes/1974/) — 2 leyes
- [1975](leyes/1975/) — 5 leyes
- [1976](leyes/1976/) — 3 leyes
- [1977](leyes/1977/) — 2 leyes
- [1978](leyes/1978/) — 2 leyes
- [1979](leyes/1979/) — 5 leyes
- [1980](leyes/1980/) — 15 leyes
- [1981](leyes/1981/) — 8 leyes
- [1982](leyes/1982/) — 1 leyes
- [1983](leyes/1983/) — 5 leyes
- [1984](leyes/1984/) — 1 leyes
- [1985](leyes/1985/) — 7 leyes
- [1986](leyes/1986/) — 5 leyes
- [1987](leyes/1987/) — 10 leyes
- [1988](leyes/1988/) — 6 leyes
- [1989](leyes/1989/) — 3 leyes
- [1990](leyes/1990/) — 19 leyes
- [1991](leyes/1991/) — 26 leyes
- [1992](leyes/1992/) — 17 leyes
- [1993](leyes/1993/) — 42 leyes
- [1994](leyes/1994/) — 103 leyes
- [1995](leyes/1995/) — 243 leyes
- [1996](leyes/1996/) — 201 leyes
- [1997](leyes/1997/) — 185 leyes
- [1998](leyes/1998/) — 54 leyes
- [1999](leyes/1999/) — 134 leyes
- [2000](leyes/2000/) — 123 leyes
- [2001](leyes/2001/) — 155 leyes
- [2002](leyes/2002/) — 189 leyes
- [2003](leyes/2003/) — 263 leyes
- [2004](leyes/2004/) — 201 leyes
- [2005](leyes/2005/) — 302 leyes
- [2006](leyes/2006/) — 283 leyes
- [2007](leyes/2007/) — 232 leyes
- [2008](leyes/2008/) — 241 leyes
- [2009](leyes/2009/) — 255 leyes
- [2010](leyes/2010/) — 185 leyes
- [2011](leyes/2011/) — 303 leyes
- [2012](leyes/2012/) — 275 leyes
- [2013](leyes/2013/) — 282 leyes
- [2014](leyes/2014/) — 222 leyes
- [2015](leyes/2015/) — 144 leyes
- [2016](leyes/2016/) — 199 leyes
- [2017](leyes/2017/) — 200 leyes
- [2018](leyes/2018/) — 216 leyes
- [2019](leyes/2019/) — 202 leyes
- [2020](leyes/2020/) — 201 leyes
- [2021](leyes/2021/) — 168 leyes
- [2022](leyes/2022/) — 144 leyes
- [2023](leyes/2023/) — 125 leyes
- [2024](leyes/2024/) — 108 leyes
- [2025](leyes/2025/) — 161 leyes
- [2026](leyes/2026/) — 6 leyes
- [sin fecha](leyes/sin-fecha/) — 8 leyes

## Formato de cada ley

Cada archivo tiene front-matter YAML con metadatos:

```yaml
---
bacn_id: 1000        # identificador en bacn.gov.py
numero: "3448"       # número oficial de la ley
titulo: "..."        # título tal como aparece en la ley
fecha_promulgacion: 2008-04-04
fecha_publicacion: 2008-05-13
fuente: bacn.gov.py
---
```

Fuente oficial de cada ley: `https://www.bacn.gov.py/leyes-paraguayas/<bacn_id>/texto`

## Contribuir

Ver [CONTRIBUTING.md](CONTRIBUTING.md).

## Fuente

Texto tomado de la Biblioteca y Archivo del Congreso Nacional. Las leyes del Paraguay son de dominio público (Art. 2, Ley 1328/98 "De derecho de autor y derechos conexos"; las leyes no constituyen obra protegida). Este repositorio no agrega licencia propia porque el contenido no es obra original: es transcripción fiel del texto oficial publicado.
