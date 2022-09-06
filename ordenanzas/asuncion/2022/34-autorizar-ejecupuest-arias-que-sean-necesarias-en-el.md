---
numero: "34"
anio: 2022
titulo: "AUTORIZAR Ejecupuest arias que sean necesarias en el adecuaciones y/o programaciones presu fiscal 2022, para la implementación de la presupuesto de ingresos y gastos del ejercicio públi municipal, para su posterior presente ordenanza con referencia a la deuda"
short_title: "AUTORIZAR Ejecupuest arias que sean necesarias en el adecuaciones y/o programaciones presu fiscal 2022, para la..."
municipio: asuncion
fuente: asuncion.gov.py
source: https://www.asuncion.gov.py/wp-content/uploads/2023/02/ord-34.pdf
ocr: opencode-go/mimo-v2-omni
fecha_sancion: 2022-09-06
---

Junta Municipal
3420
Asunción
Cont. ORD. N° 34/22

Que, de conformidad a todo lo precedentemente manifestado, teniendo en cuenta que dicho pedido se ha evaluado conforme a la Ley Orgánica Municipal N° 3.966/10, en su Art. 188 “Ampliación del Presupuesto General de la Municipalidad”, y desde el punto de vista de la Ordenanza N° 28/22 “QUE ESTABLECE EL REORDENAMIENTO ADMINISTRATIVO Y FINANCIERO DE LA MUNICIPALIDAD DE ASUNCIÓN, DISPONE MEDIDAS DE RACIONALIZACIÓN DEL GASTO PÚBLICO Y DE RESPONSABILIDAD FISCAL”, y en relación específica al Art. 17° que textualmente indica: “AUTORIZAR al Ejecutivo Municipal a realizar los proyectos de adecuaciones y/o programaciones presupuestarias que sean necesarias en el presupuesto de ingresos y gastos del ejercicio fiscal 2022, para la implementación de dicha Ordenanza con referencia a la deuda pública municipal”; es parecer de la Comisión Asesora dictaminante que corresponde aprobar el pedido de Ampliación Presupuestaria por un monto de Gs. 555.000.000.000 (Guaraníes Quinientos Cincuenta y Cinco Mil Millones), solicitado por la Dirección de Hacienda de la Intendencia Municipal, a través del Memorándum N° 107/2022, de fecha 27 de julio de 2022.

Por tanto;

LA JUNTA MUNICIPAL DE LA CIUDAD DE ASUNCIÓN, REUNIDA EN CONCEJO

ORDENA:

Art. 1° APROBAR el pedido de AMPLIACIÓN PRESUPUESTARIA por un monto total de GS. 555.000.000.000 (GUARANÍES QUINIENTOS CINCUENTA Y CINCO MIL MILLONES), solicitado por la Dirección de Hacienda, dependiente de la Dirección General de Administración y Finanzas, a través del Memorándum N° 107/2022, de fecha 27 de julio de 2022, a fin de prever en el Presupuesto 2022 la colocación de bonos municipales correspondiente a la Emisión de Bonos G8, de conformidad a las documentaciones presentadas a través de Formulario Anexo I, Formulario Anexo B-04-01, Formulario Anexo B-04-02, y Planillas de Ingresos que se adjuntan a la presente ordenanza.

Art. 2° Comuníquese a la Intendencia Municipal.

Dada en la Sala de Sesiones de la Junta Municipal de la Ciudad de Asunción, a los treinta y un días del mes de agosto del año dos mil veintidós.

![img-1.jpeg](img-1.jpeg)

TÉNGASE POR ORDENANZA, COMUNÍQUESE, DESE AL REGISTRO MUNICIPAL Y CUMPLIDO, ARCHIVAR.-

![img-2.jpeg](img-2.jpeg)Dada en la Sala de Sesiones de la Junta Municipal de la Ciudad de Asunción, a los treinta y un días del mes de agosto del año dos mil veintidós.

Junta Municipal

JOSÉ MARÍA OVIEDO V.
Secretario-General

ÁLVARO GRAU
Presidente Interino

vj. Asunción, 6 de septiembre de 2022.

MARÍA CRISTINA SIGNORINO
Secretaria General

OSCAR RODRÍGUEZ QUIÑONEZ
Intendente Municipal

```

Ahora, voy a aplicar las transformaciones según las reglas:

1. **Normalizar notaciones**:
   - Cambiar "N°" a "Nº" en todo el documento.
   - Cambiar "Art. 1°" a "Artículo 1º", "Art. 17°" a "Artículo 17º", "Art. 188" a "Artículo 188º"? Pero "Art. 188" no tiene el símbolo, así que probablemente solo cambiar cuando haya "Art. X°". En el texto hay "Art. 17°" y "Art. 1°". También hay "Art. 188" sin símbolo. Para "Art. 188" no hay símbolo, así que lo dejaré como está, pero quizás normalizar a "Artículo 188"? La regla dice "Artículo 1º" no "Artículo 1*"/"1%". Así que solo cuando haya el símbolo ° lo cambio a º. Para "Art. 188" no tiene símbolo, así que lo dejaré como "Art. 188". Sin embargo, en el texto dice "Art. 188 “Ampliación del Presupuesto General de la Municipalidad”", así que lo dejaré como "Art. 188".
   - También hay "Ordenanza N° 28/22" → "Ordenanza Nº 28/22".
   - "Mensaje N° 895/2022" → "Mensaje Nº 895/2022".
   - "Memorándum N° 107/2022" → "Memorándum Nº 107/2022".
   - "Memorándum DGAF N° 1.100/2022" → "Memorándum DGAF Nº 1.100/2022".
   - "Memorándum DH N° 107/2022" → "Memorándum DH Nº 107/2022".
   - "Memorándum N° 293/2022" → "Memorándum Nº 293/2022".
   - "Ley Orgánica Municipal N° 3.966/10" → "Ley Orgánica Municipal Nº 3.966/10".
   - "Ordenanza N° 34/22" → "Ordenanza Nº 34/22".
   - "Art. 17°" → "Artículo 17º".
   - "Art. 1°" → "Artículo 1º".
   - "Art. 2°" → "Artículo 2º".

2. **Omitir ruido**:
   - Eliminar marcadores de página como "Junta Municipal\n1\nAsunción\nCont. ORD. N° 34/22" y "Junta Municipal\n3420\nAsunción\nCont. ORD. N° 34/22".
   - Omitir imágenes: "[img-0.jpeg]", "[img-1.jpeg]", "[img-2.jpeg]".
   - Omitir las firmas y sellos que son imágenes. En el contenido, hay líneas como "![img-0.jpeg](img-0.jpeg)" que debo eliminar.
   - Omitir la línea "---" debajo de las imágenes.
   - Omitir la línea "---\n---" al final.

3. **Junta palabras partidas**: En el PDF, veo algunas palabras partidas como "Cont. ORD. N° 34/22" pero eso no es una palabra partida. Quizás "Junta Municipal\n1" es un marcador de página, lo omitiré. También hay "Colección de Bonos" pero en una tabla dice "Colección de Bonos Municipales". En el OCR, "Colección" está bien. No veo palabras partidas obvias.

4. **Preservar estructura**: Mantener títulos con #, tablas en Markdown, citas con >, etc.

5. **Output debe empezar con "# ORDENANZA Nº NNN/YY"**: Según el documento, es "ORD. N° 34/22", así que el título应该是 "# ORDENANZA Nº 34/22". Pero el documento original tiene "# ORD. N° 34/22" y luego "## (Treinta y Cuatro / Veintidós)". Debo cambiar "# ORD. N° 34/22" a "# ORDENANZA Nº 34/22". Luego, el subtítulo "## (Treinta y Cuatro / Veintidós)" puede quedar.

6. **Omitir líneas en blanco innecesarias**: Pero preservar párrafos.

Ahora, voy a generar el Markdown resultante. Para ello, procesaré el texto extraído línea por línea, aplicando las transformaciones.

Primero, el título: "# ORDENANZA Nº 34/22" en lugar de "# ORD. N° 34/22".

Luego, el contenido normalizado.

Voy a escribir el resultado final:
# ORDENANZA Nº 34/22
## (Treinta y Cuatro / Veintidós)

### VISTO:

El dictamen de la Comisión de Hacienda y Presupuesto, con relación al Mensaje Nº 895/2022 S.G., a través del cual la Intendencia Municipal remite, para estudio y consideración, el pedido de Ampliación Presupuestaria de Ingresos y Gastos por la suma de Gs. 555.000.000.000 (Guaraníes Quinientos Cincuenta y Cinco Mil Millones), solicitado por la Dirección de Hacienda, a través del Memorándum Nº 107/2022, a fin de prever en el Presupuesto 2022 la colocación de bonos municipales correspondiente a la Emisión de Bonos G8; y,

### CONSIDERANDO:

Que, el Memorándum DGAF Nº 1.100/2022, de fecha 27 de julio de 2022, de la Dirección General de Administración y Finanzas de la Intendencia Municipal, remitido al Intendente Municipal, expresa cuanto sigue: “...esta Dirección General cumple en informar cuanto sigue: La Dirección de Hacienda solicita una Ampliación Presupuestaria por Gs. 555.000.000.000 (Guaraníes Quinientos Cincuenta y Cinco Mil Millones), a fin de prever en el Presupuesto 2022 cuanto sigue: *Colocación de Bonos Municipales; correspondiente a la Emisión de Bonos G8. Conforme a lo expuesto, se sugiere respetuosamente la autorización correspondiente para la remisión a la Junta Municipal para su estudio y consideración”.

Que, el Memorándum DH Nº 107/2022, de fecha 27 de julio de 2022, de la Dirección de Hacienda, remitido a la Dirección General de Administración y Finanzas de la Intendencia Municipal, manifiesta cuanto sigue: “Me dirijo a usted, en relación a la Ordenanza Nº 28/22 “QUE ESTABLECE EL REORDENAMIENTO ADMINISTRATIVO Y FINANCIERO DE LA MUNICIPALIDAD DE ASUNCIÓN, DISPONE MEDIDAS DE RACIONALIZACIÓN DEL GASTO PÚBLICO Y DE RESPONSABILIDAD FISCAL”. Al respecto, y en relación específica al Artículo 17º que textualmente indica: “AUTORIZAR al Ejecutivo Municipal a realizar los proyectos de adecuaciones y/o programaciones presupuestarias que sean necesarias en el presupuesto de ingresos y gastos del ejercicio fiscal 2022, para la implementación de la presente Ordenanza con referencia a la deuda pública municipal, para su posterior remisión a la Junta Municipal para su estudio y aprobación correspondiente”, en ese sentido, y a fin de dar cumplimiento, solicito el Bo. Vo. para realizar la ampliación presupuestaria, de conformidad a los siguientes cuadros:

### AMPLIACIÓN DE INGRESOS

| ORIGEN DEL INGRESO | MONTO |
| --- | --- |
| Colocación de Bonos | 555.000.000.000 |
| TOTAL | 555.000.000.000 |

### AMPLIACIÓN DE GASTOS

| DEPENDENCIA | OBJETO DE GASTO | MONTO |
| --- | --- | --- |
| D. HACIENDA | 735 - Amortización por Deuda Bonificada | 195.000.000.000 |
| D. GRAL. DE OBRAS | 521 - Construcción de Obras de Uso Público | 360.000.000.000 |
| TOTAL |  | 555.000.000.000 |

Que, el Memorándum Nº 293/2022, de fecha 27 de julio de 2022, del Departamento de Presupuesto, remitido a la Dirección de Hacienda, menciona cuanto sigue: “Por el presente se remite el pedido de Ampliación Presupuestaria de Ingresos y Gastos por Gs. 555.000.000.000 (Guaraníes quinientos cincuenta y cinco mil millones),.../...solicitado por la Dirección de Hacienda en el Memorándum Nº 107/2022, a fin de prever en el Presupuesto 2022, la colocación de Bonos G8, en el marco de la Ordenanza Nº 28/22, Artículo 17. Se adjuntan Formulario Anexo 1, Formulario Anexo B-04-01, Formulario Anexo B-04-02, Planilla de Ingresos, en Medios Magnéticos Anexo 1, Anexo B-04-01, B-04-02, Hojas Foliadas”.

# ANEXO I
AMPLIACIÓN DEL PRESUPUESTO DE INGRESOS 2022
INGRESOS

| Rubro |  |  |  | Descripción | Presupuesto 2022 | Ampliación | Presupuesto Modificado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 300 |  |  |  | RECURSOS DE FINANCIAMIENTO |  |  |  |
|  | 310 |  |  | ENDEUDAMIENTO INTERNO |  |  |  |
|  |  | 311 |  | CRÉDITO INTERNO |  |  |  |
|  |  |  | 21 | Colección de Bonos Municipales | 0 | 555.000.000.000 | 555.000.000.000 |
| TOTAL A AMPLIAR |  |  |  |  |  | 555.000.000.000 |  |

Anexo B-04-01

# CUADRO DE EJECUCIONES Y ESTIMACIONES DEL INGRESO

AMPLIACIÓN PRESUPUESTARIA COLOCACIÓN DE BONOS MUNICIPALES G8

JUSTIFICACION DEL INGRESO

| Niv. Est. Descripción |  |  |  |  |  |  |  |  | Fecha: |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | Municipilidad de Asunción |  |  |  |  |  |  | Julio 2022 |  |
| Código |  |  |  |  | Descripción | Presupuesto Año 2.022 | Ejercición o Abril | Ingresos Proyectados a Diciembre | Diferencia (Ing.Proy.-P.E.022) |  |
| Grupo | Trabajo | Div. | PP |  |  |  |  |  |  |  |
| 300 | 310 | 311 | 21 | RECURSOS DE FINANCIAMIENTO ENDEUDAMIENTO INTERNO CREDITO INTERNO Colección de Bonos Municipales | 0 | 0 | 555.000.000.000 | 555.000.000.000 |  |  |
| TOTAL |  |  |  |  | 0 | 0 | 555.000.000.000 | 555.000.000.000 |  |  |

ANEXO B-04-02

# ANEXO CUADRO AMPLIACION PRESUPUESTARIA

POR EL CUAL SE AUTORIZA LA AMPLIACION PRESUPUESTARIA MUNICIPAL, CORRESPONDIENTE AL EJERCICIO 2022

1-601-812-18

| Tipo de Presup: | 2 | PARTIDAD NO ALEJANDADA A PROGRAMAS |
| --- | --- | --- |
| Programa: | 022 | PARTIDAD NO ALEJANDADA A PROGRAMAS |
| Actividad/Proyecto: | 002 | ACTIVIDAD MUNICIPAL Y LA LICENCIA ANEXO II-A |
| Unidad Resp.: | 24 | TIR. DE HACIENDA |
| CORREO |  |  |  | MUNICIPIO | PROVINCIPIO INICIAL | REDAFICACIONES D.F.I. | PROVINCIPIO ACREDADO | INFORMACION |  | SALES PROPIEDADAS |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D.N. | I.V. | D.F. | OPEL |  |  |  |  | EJERCICIOS | MUNICIPIOS |  |
| 721 | 21 | 13 | 00 | JAMARRIZAC POR D.EXDA RONALCAZAS | 0 | 0 | 0 | 0 | 215.000.000.000 | 215.000.000.000 |
| SUB TOTAL |  |  |  |  | 0 | 0 | 0 | 0 | 215.000.000.000 | 215.000.000.000 |

1-662-862-14

| Tipo de Presup: | 2 | PROGRAMA JUSTIFICADO |
| --- | --- | --- |
| Programa: | 002 | PROGRAMA JUSTIFICADO |
| Actividad/Proyecto: | 002 | PROYECTO CONSIDERADO DE DICIEMBRE PEDIDOLES EN LA DURAD DE ADEMADOS BONOS |
| Unidad Resp.: | 24 | TIR. DE H. ORAZ |
| CORREO |  |  |  | CONCEPTO | PROVINCIPIO INICIAL | REDAFICACIONES D.F.I. | PROVINCIPIO ACREDADO | INFORMACION |  | SALES PROPIEDADAS |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D.N. | I.V. | D.F. | OPEL |  |  |  |  | EJERCICIOS | MUNICIPIOS |  |
| 511 | 20 | 14 | 00 | CONTRAT, DE SERIAS DE USO POR: | 0 | 0 | 0 | 0 | 200.000.000.000 | 200.000.000.000 |
| SUB TOTAL |  |  |  |  | 0 | 0 | 0 | 0 | 200.000.000.000 | 200.000.000.000 |

Que, de conformidad a todo lo precedentemente manifestado, teniendo en cuenta que dicho pedido se ha evaluado conforme a la Ley Orgánica Municipal Nº 3.966/10, en su Art. 188 “Ampliación del Presupuesto General de la Municipalidad”, y desde el punto de vista de la Ordenanza Nº 28/22 “QUE ESTABLECE EL REORDENAMIENTO ADMINISTRATIVO Y FINANCIERO DE LA MUNICIPALIDAD DE ASUNCIÓN, DISPONE MEDIDAS DE RACIONALIZACIÓN DEL GASTO PÚBLICO Y DE RESPONSABILIDAD FISCAL”, y en relación específica al Artículo 17º que textualmente indica: “AUTORIZAR al Ejecutivo Municipal a realizar los proyectos de adecuaciones y/o programaciones presupuestarias que sean necesarias en el presupuesto de ingresos y gastos del ejercicio fiscal 2022, para la implementación de dicha Ordenanza con referencia a la deuda pública municipal”; es parecer de la Comisión Asesora dictaminante que corresponde aprobar el pedido de Ampliación Presupuestaria por un monto de Gs. 555.000.000.000 (Guaraníes Quinientos Cincuenta y Cinco Mil Millones), solicitado por la Dirección de Hacienda de la Intendencia Municipal, a través del Memorándum Nº 107/2022, de fecha 27 de julio de 2022.

Por tanto;

LA JUNTA MUNICIPAL DE LA CIUDAD DE ASUNCIÓN, REUNIDA EN CONCEJO

ORDENA:

Artículo 1º APROBAR el pedido de AMPLIACIÓN PRESUPUESTARIA por un monto total de GS. 555.000.000.000 (GUARANÍES QUINIENTOS CINCUENTA Y CINCO MIL MILLONES), solicitado por la Dirección de Hacienda, dependiente de la Dirección General de Administración y Finanzas, a través del Memorándum Nº 107/2022, de fecha 27 de julio de 2022, a fin de prever en el Presupuesto 2022 la colocación de bonos municipales correspondiente a la Emisión de Bonos G8, de conformidad a las documentaciones presentadas a través de Formulario Anexo I, Formulario Anexo B-04-01, Formulario Anexo B-04-02, y Planillas de Ingresos que se adjuntan a la presente ordenanza.

Artículo 2º Comuníquese a la Intendencia Municipal.

Dada en la Sala de Sesiones de la Junta Municipal de la Ciudad de Asunción, a los treinta y un días del mes de agosto del año dos mil veintidós.

TÉNGASE POR ORDENANZA, COMUNÍQUESE, DESE AL REGISTRO MUNICIPAL Y CUMPLIDO, ARCHIVAR.-

Dada en la Sala de Sesiones de la Junta Municipal de la Ciudad de Asunción, a los treinta y un días del mes de agosto del año dos mil veintidós.

JOSÉ MARÍA OVIEDO V.
Secretario-General

ÁLVARO GRAU
Presidente Interino

Asunción, 6 de septiembre de 2022.

MARÍA CRISTINA SIGNORINO
Secretaria General

OSCAR RODRÍGUEZ QUIÑONEZ
Intendente Municipal