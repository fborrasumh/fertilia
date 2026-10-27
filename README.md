# FertilIA

El laboratorio de nutrición vegetal y fertilización. Aplicación web de un solo fichero que acompaña la asignatura de **Nutrición Vegetal** (Carrera de Agropecuaria, Universidad Politécnica Estatal del Carchi) y sirve a cualquier estudiante de agronomía, ciencias del suelo o producción agrícola.

**Usar la app:** https://fborrasumh.github.io/fertilia/

**Idiomas:** español (por defecto), inglés y portugués; selector en la barra superior (o `?lang=en` / `?lang=pt` en la URL).

## Qué hace

- **Problemas individualizados.** Cada estudiante escribe un código o alias y recibe sus propios problemas, siempre los mismos para ese código (la profesora puede reproducirlos). La solución la calcula el código y, si la respuesta es errónea, recalcula los errores típicos (olvidar la eficiencia o la acidez intercambiable, no convertir a P₂O₅ o K₂O, la valencia del Ca o del CaCO₃, la humedad del abono, multiplicar por la riqueza en vez de dividir…) para decir cuál se cometió.
- **Nutrientes:** tabla de los elementos esenciales y beneficiosos (forma de absorción, movilidad en el floema, mecanismo de llegada a la raíz, función, deficiencia y exceso) y casos de campo con clave para distinguir deficiencias, toxicidades (Al, Mn, B, salinidad) y problemas abióticos (deriva de herbicida, helada, encharcamiento).
- **Suelo y absorción:** simulador cualitativo de pH y disponibilidad de nutrientes; problemas de CIC efectiva y saturación de bases, de mg/kg a kg/ha y de flujo masal frente a difusión.
- **Diagnóstico:** planificación del muestreo de suelo y de tejido por cultivo; interpretación de un análisis de suelo (pH, CE, MO, P Olsen, cationes, acidez, CICe, saturaciones y relaciones Ca/Mg, Mg/K, (Ca+Mg)/K); análisis foliar con niveles de suficiencia e índices DRIS; problemas de DRIS.
- **Balance:** extracción por la cosecha, dosis de N por balance, unidades fertilizantes (DAP + urea) y riqueza de mezclas; conversor de unidades (P↔P₂O₅, K↔K₂O…).
- **Fertilizantes y enmiendas:** fertilizantes químicos con su riqueza, reacción en el suelo e índice salino; abonos orgánicos (bovino, gallinaza, porquinaza, cuy, compost, humus, bocashi); biofertilizantes; problemas de abono orgánico y de encalado.
- **Plan de fertilización integrada (proyecto ABP):** del rendimiento objetivo al producto comercial y al calendario por etapa fenológica, con el aporte del suelo, de la fijación biológica y del abono orgánico; bitácora de campo y reporte en Word y CSV.
- **Lectura crítica de artículos** con IA opcional: pregunta, diseño, resultados y limitaciones con cita literal comprobada.
- **Práctica de parcial:** un intento distinto cada vez, corregido por el código.

## La IA propone, el código comprueba

La IA es opcional (OpenAI, Google Gemini o Anthropic Claude, con la clave de cada persona). Se usa solo para la ficha de lectura de un artículo y para proponer preguntas y un borrador de justificación del plan. El código comprueba que cada cita aparece literalmente en el texto y señala cualquier cifra del borrador que no salga del plan calculado. Ningún problema, interpretación ni dosis la calcula la IA.

## Privacidad

Todo se guarda en el navegador (IndexedDB). Hacia el proveedor de IA sale únicamente lo que la persona pide analizar: el texto del artículo o el **resumen numérico** del plan, con correos, números de identificación y teléfonos enmascarados y tras un aviso previo con muestra de lo que sale.

## Límites

- Los rangos de interpretación del análisis de suelo y foliar, las normas DRIS, la extracción por tonelada, el fraccionamiento por etapas y la composición de fertilizantes y abonos son **generales y orientativos**; en un informe real se usan los del laboratorio, el cultivo y la región. En el plan los coeficientes de extracción se pueden cambiar.
- El plan usa un balance simplificado: N = (extracción − fijación − suelo − abono) ÷ eficiencia; P₂O₅ y K₂O = extracción × factor de la clase del análisis − abono. No sustituye una recomendación profesional.
- El simulador de pH es un esquema cualitativo, no un modelo de concentraciones.
- La práctica de parcial es orientativa: no sustituye al examen ni a las prácticas en el centro experimental.
- El análisis de ejemplo, el plan de ejemplo y el resumen de artículo de ejemplo son ficticios.
- Probado con IA simulada; las respuestas reales de la IA pueden equivocarse: por eso se verifican las citas y las cifras.

## Autoría

Fernando Borrás Rocher (Universidad Miguel Hernández de Elche) y Haddy Daniela Jácome Lucero (Universidad Politécnica Estatal del Carchi).

Sigue el sílabo de Nutrición Vegetal (0811BNV5UP-AJ2025, nivel 5, Carrera de Agropecuaria, UPEC) de la profesora Haddy Daniela Jácome Lucero: sus contenidos, sus dos parciales, su proyecto integrador con cultivos de la zona y su lectura crítica de artículos.

ORCID: Fernando Borrás Rocher [0000-0002-5519-4573](https://orcid.org/0000-0002-5519-4573) · Haddy Daniela Jácome Lucero [0009-0006-5228-3905](https://orcid.org/0009-0006-5228-3905)

## Cómo citar

Borrás Rocher, F. y Jácome Lucero, H. D. (2026). *FertilIA* (v1.0.0) [Software]. (DOI en trámite)

## Licencia

MIT. Véase [LICENSE](LICENSE).
