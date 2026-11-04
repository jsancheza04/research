# Rompecabezas de desarrollo humano en América Latina y el Caribe (sin Colombia), 2001-2026

Alcance tras la actualización del coordinador: solo se mantienen patrones cuyo movimiento, reversión o divergencia clave ocurre en 2001-2026; los datos anteriores a 2001 aparecen solo como línea de base. Colombia está excluida por completo.

Nota metodológica general (límites de búsqueda, léase primero):
- La API del Banco Mundial (api.worldbank.org) devolvió 403 desde el proxy; ourworldindata.org no resuelve; BigQuery (WDI público) no tiene proyecto/credenciales. **No pude descargar series WDI/UN WPP/UIS directamente.** Todas las cifras vienen de fuentes oficiales o académicas tal como aparecen en resultados de WebSearch (snippets). No abrí ninguna página con WebFetch: **todas las URLs son "solo buscador"** (la URL aparece en resultados, pero no leí el texto completo). Las cifras deben verificarse contra la fuente primaria antes de usarse en un paper.
- Escala de calidad de la evidencia usada: Ninguna / Especulación en prensa / Descriptiva / Parcial causal / Bien explicada (→ descartar).
- Consultas exactas usadas (WebSearch, en orden): "Chile tasa global de fecundidad 2024 INE estadísticas vitales"; "Uruguay tasa global de fecundidad 2024 nacimientos récord mínimo"; "Costa Rica tasa global de fecundidad 2024 INEC más baja"; "Argentina caída natalidad 2014-2023 fecundidad adolescente explicación estudio"; "Uruguay fertility decline 2016 adolescent subdermal implant Cabella Nathan Pardo"; "Uruguay egreso educación media superior 21 a 23 años porcentaje INEED informe"; "República Dominicana mortalidad materna paradoja 98% partos institucionales razón por 100.000"; "Guyana Suriname suicide rate highest Americas explanation study"; "Jamaica boys underachievement education gender gap tertiary enrollment females UWI explanation"; "República Dominicana tasa de cesáreas más alta del mundo mortalidad materna calidad atención estudio"; "Gasparini Marchionni deceleration female labor force participation Latin America stagnation"; "Guatemala desnutrición crónica ENSMI 2014-2015 46.5% persistencia por qué no baja estudio"; "Uruguay tasa de suicidio 2024 por 100.000 Ministerio de Salud Pública récord jóvenes"; "\"Caribbean's different gender gap\" women rise men stagnate World Bank"; "Uruguay culminación educación media comparación América Latina Chile Perú Bolivia por qué rezago explicación"; "Chile caída fecundidad 2024 explicaciones estudio académico Centro UC demografía causas debate"; "Dominican Republic maternal mortality ratio WHO UN MMEIG estimate 2000 2020 2023 trend"; "Jamaica Barbados tertiary enrollment gender parity index females per male UNESCO highest world"; "Perú tasa de empleo informal 2007 2024 INEI porcentaje crecimiento económico no reduce informalidad"; "Uruguay suicide rate why highest South America study explanation Durkheim aging rural men"; "maternal mortality Dominican Republic quality of care study institutional delivery paradox Miller \"too much too soon\""; "América Latina caída fecundidad más rápida de lo previsto Naciones Unidas proyecciones sorpresa demógrafos 2025"; "Uruguay paradoja educación media bajo egreso alto gasto explicación investigación Fernández Cardozo desafiliación"; "IDB \"gender gaps in education in the Caribbean\" girls doing better than boys CSEC pass rates"; "participación laboral femenina América Latina estancada 2010 2024 OIT CEPAL porcentaje explicación".
- Ranking final (por grado de rompecabezas × promesa de investigación): (1) Paradoja de mortalidad materna en República Dominicana; (2) Colapso a fecundidad "ultra-baja" en Chile, Costa Rica, Uruguay y Argentina después de 2014-2016; (3) Caída de la fecundidad sin aumento de la participación laboral femenina en la región; (4) Rezago del egreso de educación media en Uruguay; (5) Suicidio: Uruguay y Guyana/Surinam como valores atípicos; (6) Brecha de género educativa invertida en el Caribe anglófono, sin traducción al mercado laboral; (7) Informalidad peruana estancada (~70%) tras dos décadas de crecimiento (rompecabezas bajo-medio).

---

## Rompecabezas 1 — República Dominicana: mortalidad materna alta y en aumento pese a un parto casi 100% institucional (y la tasa de cesáreas más alta medida)

### Takeaway
En RD, la razón de mortalidad materna (RMM) **subió** de 79 (2000) a 107 (2020) por 100.000 nacidos vivos según la serie modelada OMS/MMEIG, y la vigilancia nacional reporta máximos en 2023-2024 (~123-128), mientras la atención calificada del parto es prácticamente universal (~97-100%) y la cesárea pasó de 31% (2002) a 58% (2014). Esto va contra la relación estándar acceso institucional → menor mortalidad, y contra el crecimiento rápido del PIB dominicano. Hay un trabajo descriptivo de 2003 y uno correlacional de 2023; no hay evidencia causal sobre el mecanismo.

### Cited Findings
**Hechos (con fuente)**
- [HECHO] RMM modelada OMS/MMEIG: 79 (2000) → 107 (2020); RD por encima del promedio regional — [Banco Mundial, Gender Data Portal, perfil RD (cita *Trends in Maternal Mortality 2000-2020*)](https://genderdata.worldbank.org/data/download/pdfs/countries/dominican-republic.pdf). Discrepancia: Knoema reporta 69 en 2001 y 107 en 2020 (crecimiento medio anual 2,39%) — [Knoema](https://knoema.com/atlas/embed/Dominican-Republic/Maternal-mortality-ratio). La versión anterior MMEIG (2000-2017) daba 95 para 2017 — [IndexMundi](https://www.indexmundi.com/facts/dominican-republic/maternal-mortality-ratio). Las cifras modeladas cambian entre rondas; usar la ronda más reciente (MMEIG 2000-2023) — **no verificada aquí**.
- [HECHO, vigilancia nacional] RMM ~94,8 (2019), >100 en 2017-2018 — [El Caribe](https://www.elcaribe.com.do/panorama/salud/la-mortalidad-materna-sigue-en-ascenso-en-rd/); 127,7 por 100.000 nacidos vivos al cierre de 2024 — [El Nuevo Diario](https://elnuevodiario.com.do/morir-por-parir/); ACOG-RD estima 123 por 100.000 *partos* en 2024 (diferencia de denominador). Un estudio con datos de SINAVE indica aumento durante COVID, baja en 2022 y **máximo récord en 2023** — [medRxiv 2024](https://medrxiv.org/content/10.1101/2024.03.11.24304148v1.full.txt). CIPAF proyecta 154 en 2025 (estimación de ONG, no oficial) — [Acento](https://acento.com.do/actualidad/cipaf-mas-de-mil-mujeres-murieron-por-causas-maternas-en-rd-entre-2019-y-2025-9676698.html).
- [HECHO] Parto con personal calificado "cercano al 100%" (II Informe Nacional Voluntario ODS) — [El Caribe](https://www.elcaribe.com.do/panorama/salud/la-mortalidad-materna-sigue-en-ascenso-en-rd/); 97% de partos institucionales (MSP, 2017) — [Acento](https://acento.com.do/salud/salud-publica-colocara-mortalidad-materna-principales-retos-2017-8418521.html).
- [HECHO] Cesáreas: 31% (2002) → 58% (2014) según UNICEF (en paralelo cayó la lactancia en la primera hora) — [Acento](https://acento.com.do/actualidad/lactancia-materna-primera-hora-vida-menor-al-40-republica-dominicana-8592656.html); 58,1% en datos de 2015 según estudio de *The Lancet*, la más alta entre países analizados — [Diario Digital](https://www.diariodigital.com.do/2020/03/02/republica-dominicana-tiene-la-tasa-mas-alta-de-cesareas-en-el-mundo.html); ~87% en clínicas privadas según Colectiva Mujer y Salud (fuente ONG; verificar). Una columna cita 68% en 2024 sin fuente — [El Caribe, opinión](https://www.elcaribe.com.do/opiniones/cuando-nacen-los-dominicanos/) (**no verificado**).
- [HECHO] Un análisis de 2017 identificó 88% de muertes maternas como evitables y 85% de ellas ligadas a atención inadecuada (citado en prensa; fuente primaria no localizada) — [El Nuevo Diario](https://elnuevodiario.com.do/morir-por-parir/).
- [HECHO, medición] Un estudio con método de hermanas en la provincia Monseñor Nouel halló RMM de 348/100.000 frente a estimaciones nacionales de 72-250 → probable subregistro — [IHSN catálogo de citas](https://catalog.ihsn.org/citations/3404). Diario Libre cita subregistro de ~25% — [Diario Libre](https://www.diariolibre.com/actualidad/observatorio-de-insalud-vigilar-muertes-maternas-AMDL511001).

**Cómo lo presenta la prensa (todas "solo buscador")**
- Diario Libre (fecha no visible en el snippet): "106 por 100 mil… cuestionable porque el 98% de los partos ocurren en hospitales"; atribuye a baja calidad y fallas de referencia/contrarreferencia — [URL](https://www.diariolibre.com/actualidad/observatorio-de-insalud-vigilar-muertes-maternas-AMDL511001).
- El Caribe, "La mortalidad materna sigue en ascenso en RD" — [URL](https://www.elcaribe.com.do/panorama/salud/la-mortalidad-materna-sigue-en-ascenso-en-rd/).
- El Nuevo Diario, "Morir por parir" (fecha dudosa: muestra 2026 pero el contenido parece de 2018) — [URL](https://elnuevodiario.com.do/morir-por-parir/).
- elDinero, "Madres invisibles: investigación revela persistencia de la crisis…" — [URL](https://eldinero.com.do/364549/madres-invisibles-investigacion-revela-persistencia-de-la-crisis-de-el-estudio-examina-la-crisis-silenciosa-de-la-mortalidad-materna-en-el-pais-durante-los-ultimos-seis-anos-en-rd/).
- Encuadre dominante: "problema de calidad, no de acceso", "violencia obstétrica", "cesáreas innecesarias", "penalización total del aborto". No encontré cobertura de BBC Mundo/El País/Bloomberg Línea específicamente sobre la paradoja (búsqueda no exhaustiva).

**Explicaciones existentes**
- H1 Calidad de la atención institucional (demoras, manejo de hemorragia/preeclampsia, referencia) — Miller et al. (2003), "Quality of care in institutionalized deliveries: the paradox of the Dominican Republic", *Int. J. Gynecol. Obstet.* 82(1):89-103 — [Scilit](https://scilit.net/publications/625bc1bbbe1e9813fa991262ebd20e71). Calidad: **Descriptiva** (solo vi título y objetivo).
- H2 Correlatos ecológicos provinciales — De Jesus et al. (2023), IJERPH 20(14):6413: cama hospitalaria, fecundidad adolescente y desempleo **no** correlacionan con RMM; RMM sube con tasa de partos vaginales y mortalidad infantil; piden estudiar *near-miss* — [PMC10379411](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10379411/). Calidad: **Descriptiva** (correlaciones agregadas; el signo de "partos vaginales" probablemente refleja composición/complicaciones, no causalidad).
- H3 Epidemia de cesáreas (morbilidad quirúrgica) — Colectiva Mujer y Salud, ACOG-RD, especialistas citados por BBC — [Diario Digital](https://www.diariodigital.com.do/2020/03/02/republica-dominicana-tiene-la-tasa-mas-alta-de-cesareas-en-el-mundo.html); [blog BID](https://blogs.iadb.org/salud/es/partos-cesarea-una-moda-deberia-la-excepcion). Calidad: **Especulación en prensa** para el caso dominicano (la OMS indica que tasas >10% no reducen la mortalidad a nivel poblacional, pero eso no implica que la eleven).
- H4 Demoras para acceder a atención de complicaciones (enfermeras dominicanas) — estudio cualitativo — [PMC2946473 (resultado de búsqueda; contenido no verificado)](https://pmc.ncbi.nlm.nih.gov/articles/PMC2946473). Calidad: **Descriptiva**.
- H5 Prohibición total del aborto → abortos inseguros — prensa/ONG. Calidad: **Especulación en prensa**.
- H6 Artefacto de medición (mejor registro eleva la RMM) — implícito en el estudio de Monseñor Nouel. Calidad: **Ninguna** evaluación formal.

### Inferences
- [INFERENCIA] Por qué la explicación es pobre: la literatura identifica "calidad" como causa residual, pero nadie ha separado (a) mejora del registro, (b) composición (más partos de alto riesgo, más migrantes haitianas), (c) práctica clínica (cesáreas, manejo de hemorragia) y (d) sector público vs. privado. La tendencia creciente 2000-2023 no tiene explicación cuantitativa.
- [INFERENCIA] Hipótesis candidatas: (i) composición por nacionalidad: la proporción de partos de madres haitianas en hospitales públicos dominicanos ha sido reportada como alta (no verificado aquí) — su RMM podría elevar el agregado; (ii) intensidad de cesárea por hospital/médico (incentivos de pago privados, seguro SeNaSa); (iii) mejora en vigilancia SINAVE tras ~2010; (iv) saturación de maternidades públicas de referencia (Santo Domingo).
- [INFERENCIA] Variación discriminante: diferencias entre hospitales y provincias en cesárea y RMM; cambios en reglas de pago del SeNaSa/aseguradoras (diff-in-diff por régimen subsidiado vs. contributivo); expansión de vigilancia (fecha de implementación por provincia); shift-share por nacionalidad de la madre (natalidad haitiana) para descomponer la tendencia.
- [INFERENCIA] Datos: estadísticas vitales y SINAVE (MSP, posiblemente restringidos); ENDESA 2013 y ENHOGAR-MICS (módulo de hermanas para RMM); registros hospitalarios; Lancet/WHO global cesarean dataset. Microdatos de defunciones por establecimiento serían la pieza clave (acceso restringido).
- Grado de rompecabezas: **alto**. Promesa de investigación: **alta** (pocas personas trabajan en esto desde economía; datos administrativos plausibles; relevancia de política).

### Gaps
- No obtuve la RMM MMEIG 2023 (ronda 2025) para RD ni el promedio LAC comparable (un snippet cita 68/100.000 para LAC, sin año claro).
- No verifiqué la proporción de partos de madres haitianas ni RMM por nacionalidad.
- No vi el texto de Miller et al. (2003); su argumento concreto queda sin verificar.
- No encontré un estudio causal sobre cesáreas → mortalidad materna en RD.

---

## Rompecabezas 2 — Colapso a fecundidad "ultra-baja" (<1,3) en Chile, Costa Rica, Uruguay y Argentina después de 2014-2016

### Takeaway
En menos de una década, cuatro países pasaron de fecundidad cercana al reemplazo a niveles de Asia del Este: Chile 1,03 (2024) y 0,99 provisional (2025); Costa Rica 1,12 (2024) desde 1,78 (2014); Uruguay de ~2,0 (2015) a ~1,3-1,4; Argentina con ~40-46% menos nacimientos entre 2014 y 2023. La velocidad y sincronía sorprendieron a las proyecciones de la ONU/CEPAL. Hay evidencia causal parcial (implantes subdérmicos en Uruguay explican ~1/3 de la caída en hospitales públicos) y descomposiciones descriptivas (menos parejas en Chile), pero los propios demógrafos uruguayos dicen que "las causas reales siguen poco comprendidas".

### Cited Findings
**Hechos**
- [HECHO] Chile: TGF 1,16 (2023) → 1,03 (2024; nacimientos −11,3%) → 0,99 (2025, provisional INE); otra fuente cita 0,97 para 2025 (presentación Censo 2024) — **discrepancia; usar boletín INE** — [Bloomberg Línea](https://www.bloomberglinea.com/latinoamerica/chile/chile-registro-la-tasa-de-fecundidad-mas-baja-de-su-historia-en-2025-claves-del-informe-de-ine/); [CNN Chile](https://www.cnnchile.com/pais/ine-alerta-por-tasa-de-fecundidad-chile-registra-por-primera-vez-menos-de-un-hijo-por-mujer/); [INE Demografía y vitales](https://www.ine.gob.cl/estadisticas/sociales/demografia-y-vitales); [Forbes Chile 2025 (1,16)](https://forbes.cl/actualidad/2025-03-17/la-tasa-de-fecundidad-cae-a-su-minimo-historico-en-chile-116-hijos).
- [HECHO] Chile: mujeres de 15-19 con hijos 14,6% (1992) → 2% (2024); mujeres de 20-29 con hijos ~65% hace tres décadas → 32,3% actual (Censo) — [Universidad de O'Higgins, documento](https://www.uoh.cl/investigacion/wp-content/uploads/sites/12/2026/01/Que-hay-en-el-fondo.pdf).
- [HECHO] Costa Rica: TGF 1,78 (2014) → 1,12 (2024, INEC), mínimo histórico; "ultra baja" (<1,5) desde 2020. CEPAL estima 1,32 para 2024 — **discrepancia INEC vs. CEPAL** — [Revista EyN](https://www.revistaeyn.com/centroamericaymundo/fecundidad-en-costa-rica-toca-minimo-historico-apenas-112-hijos-por-mujer-en-2024-LB28290029); [Teletica, 24-feb-2026](https://www.teletica.com/nacional/el-pais-sin-relevo-costa-rica-cae-a-una-de-las-tasas-de-fecundidad-mas-bajas-del-mundo_402877); [Observador CR](https://observador.cr/ultra-baja-fecundidad-en-costa-rica-cantidad-de-hijos-por-mujer-pasa-de-176-a-119/).
- [HECHO, con incertidumbre] Uruguay: ~2 hijos/mujer (2015) → 1,37 (2021); CEPAL estima ~1,28 "actual"; otra fuente (probablemente UN WPP) da 1,4 para 2024 — **no confirmé el dato oficial MSP/INE 2024** — [Ámbito](https://www.ambito.com/uruguay/tiene-una-las-tasas-fecundidad-mas-bajas-la-region-y-suma-otro-desafio-demografico-n6208149). Nacimientos: casi 49.000 (2015) → <36.000 (2020) — [Montevideo Portal](https://www.montevideo.com.uy/Noticias/Eramos-pocos-y-seremos-menos-la-tasa-de-nacimientos-se-desploma-en-Uruguay-uc800999); 31.381 nacimientos vs. 34.677 defunciones en 2023 (mismo snippet de Ámbito).
- [HECHO] Argentina: tasa de natalidad −46% 2014-2023 (Tierra del Fuego −62%); fecundidad adolescente 11,5 por mil mujeres de 10-19 en 2023, −64% vs. 2005; la caída fue mayor en madres adolescentes y de menor nivel educativo — [Chequeado](https://chequeado.com/investigaciones/tasa-de-natalidad-en-la-argentina-se-redujo-mas-en-madres-adolescentes-y-de-menor-nivel-educativo/). Infobae (vía otros medios) da −43% en fecundidad y 316.000 nacimientos menos en 2023 vs. 2014 (no abrí la nota).
- [HECHO] Región: TGF 1,8 en América Latina y 1,5 en el Caribe (2024); bajo reemplazo desde 2015; descenso "fuertemente relacionado" con fecundidad adolescente y joven — [CEPAL, Observatorio Demográfico 2025](https://repositorio.cepal.org/server/api/core/bitstreams/5a21ab2b-3d99-4105-8c37-8dddf040ae66/content); población regional 663 millones, 3,8% menos de lo previsto hace dos décadas — [ABC Color](https://www.abc.com.py/internacionales/2024/11/28/poblacion-de-america-latina-crece-menos-de-lo-esperado-cuantos-somos-segun-cepal/).

**Cómo lo presenta la prensa (todas "solo buscador")**
- Bloomberg Línea (2026), "Chile registró la tasa de fecundidad más baja de su historia en 2025" — [URL](https://www.bloomberglinea.com/latinoamerica/chile/chile-registro-la-tasa-de-fecundidad-mas-baja-de-su-historia-en-2025-claves-del-informe-de-ine/).
- CNN Chile, "INE alerta… por primera vez menos de un hijo por mujer" — [URL](https://www.cnnchile.com/pais/ine-alerta-por-tasa-de-fecundidad-chile-registra-por-primera-vez-menos-de-un-hijo-por-mujer/); Forbes Chile (28-may-2026), "Chile sin hijos" — [URL](https://forbes.cl/actualidad/2026-05-28/chile-sin-hijos-se-anota-la-fecundidad-mas-baja-en-la-historia-del-pais/).
- Teletica (24-feb-2026), "El país sin relevo…" — [URL](https://www.teletica.com/nacional/el-pais-sin-relevo-costa-rica-cae-a-una-de-las-tasas-de-fecundidad-mas-bajas-del-mundo_402877); La Nación CR, "Ultra baja fecundidad en Costa Rica" — [URL](https://www.nacion.com/el-pais/ultra-baja-fecundidad-en-costa-rica-como-ha/TUFYA5DY35GL5HHKR4AKKI4VYQ/story/).
- El Observador (Uruguay, 10-mar-2025), "Se derrumban las tasas de natalidad en Latinoamérica" — [URL](https://www.elobservador.com.uy/estados-unidos/sociedad/se-derrumban-las-tasas-natalidad-latinoamerica-cuales-son-los-paises-mayor-caida-n5986892); la diaria/La Mañana, "Infierno demográfico" (opinión) — [URL](https://www.xn--lamaana-7za.uy/opinion/infierno-demografico).
- RPP (Perú) sobre Argentina: atribuye a crisis económica, descarta la Ley IVE (aprobada 6 años después del inicio de la caída) — [URL](https://rpp.pe/mundo/argentina/cuales-son-las-causas-de-la-baja-natalidad-en-argentina-noticia-1703244).
- Encuadres: "invierno demográfico", crisis de pensiones, costo de vida, "las jóvenes no quieren ser madres", feminismo/ESI, anticonceptivos.

**Explicaciones existentes**
- H1 Anticoncepción de larga duración (implantes) en el sector público, Uruguay — Ceni et al. (2021): estudio de eventos con el calendario de despliegue; ~1/3 de la caída de nacimientos en hospitales públicos, efectos mayores en adolescentes y primeros hijos — [Studies in Family Planning, 10.1111/sifp.12171 (vía Zendy)](https://zendy.io/title/10.1111/sifp.12171). Ferre, Triunfo y Antón (2023), RDD sobre programa de implantes posparto: −10 pp en probabilidad de otro hijo en 48 meses — [Health Economics 32(12):2679-2693, RePEc](https://econpapers.repec.org/RePEc:wly:hlthec:v:32:y:2023:i:12:p:2679-2693). Calidad: **Parcial causal** (explica parte en Uruguay; no explica Chile/Costa Rica ni las caídas en edades 25-34).
- H2 Descripción del "gran descenso" uruguayo, motor adolescente y temprano — Cabella, Fernández Soto, Pardo y Pedetti (2024), Demographic Research 50(16), "The big decline: lowest-low fertility in Uruguay (2016–2021)": afirman que las causas "siguen poco comprendidas" — [RePEc](https://econpapers.repec.org/RePEc:dem:demres:v:50:y:2024:i:16); [N-IUSSP "Plummeting fertility in Uruguay"](https://niussp.org/?p=9242). Calidad: **Descriptiva**.
- H3 Menos parejas (sobre todo cohortes nacidas en dictadura) — Estudio CEP (sept. 2025): contrafactual, si la proporción de mujeres en pareja se mantuviera desde 2006, la caída sería 20% menor — [Emol](https://www.emol.com/noticias/Nacional/2025/09/27/1178563/estudio-cep-natalidad-generaciones-pareja.html). Calidad: **Descriptiva** (descomposición; desplaza la pregunta a por qué cae la formación de parejas).
- H4 Segunda transición demográfica + educación — Salinas y Wiegand-Cruz, *Estudios Públicos* 183 — [CEP](https://estudiospublicos.cl/index.php/cep/issue/download/191/Ver%20PDF%20183). Calidad: **Descriptiva**.
- H5 Incompatibilidad trabajo-familia / roles de género — Encuesta Bicentenario UC 2024; Policy Brief Centro de Políticas Públicas UC (nov. 2025) — [UC Policy Brief](https://politicaspublicas.uc.cl/content/uploads/2025/11/NATALIDAD-y-DEMOGRAFIA_POLICY-BRIEF.pdf). Calidad: **Descriptiva/opinión** (preferencias declaradas).
- H6 Crisis económica / costo de vivienda (Argentina) — ONU vía RPP — [RPP](https://rpp.pe/mundo/argentina/cuales-son-las-causas-de-la-baja-natalidad-en-argentina-noticia-1703244). Calidad: **Especulación en prensa** (Chile y Costa Rica cayeron sin crisis comparable).
- H7 ESI + anticonceptivos gratuitos + Plan ENIA (Argentina) — especialistas citados en prensa; Mabel Bianco (FEIM) en Chequeado. Calidad: **Especulación en prensa** (no encontré evaluación causal del Plan ENIA en esta búsqueda).

### Inferences
- [INFERENCIA] Por qué la explicación es pobre: lo mejor identificado (implantes en Uruguay) explica una fracción en un país; nada explica la **sincronía** del quiebre ~2014-2016 en países con políticas, ciclos y estructuras distintas, ni por qué Chile/Costa Rica caen más que Brasil/México. Las descomposiciones (parejas, edad) son contables, no causales.
- [INFERENCIA] Hipótesis candidatas: (i) difusión tecnológica de LARC + anticoncepción de emergencia en sistemas públicos casi simultánea; (ii) shock en la formación de uniones (vivienda, apps, cambio en mercado matrimonial por migración venezolana en Chile — la inmigración masiva 2017-2019 debería haber *subido* la TGF, lo que hace el caso chileno más extraño); (iii) caída de embarazos no deseados en adolescentes con transmisión a la fecundidad de 20-24 vía efecto cohorte; (iv) efecto de expansión educativa terciaria (Chile gratuidad 2016).
- [INFERENCIA] Variación discriminante: calendario de despliegue de implantes por departamento/hospital (Uruguay, Argentina — Plan ENIA se implementó en provincias seleccionadas desde 2017, buen diseño diff-in-diff); fecundidad por nacionalidad de la madre en Chile (estadísticas vitales registran nacionalidad) para descomponer el efecto migrante; cohortes de la gratuidad chilena (RDD por quintil); comparación de comunas con distinta presión de vivienda.
- [INFERENCIA] Datos: estadísticas vitales de nacimientos con microdatos públicos (DEIS Chile, DEIS Argentina, MSP Uruguay, INEC CR); ENIA/registro de insumos de anticoncepción; censos 2024 (Chile) e IPUMS-International para historia de uniones; encuestas de hogares (CASEN, ECH, EPH, ENAHO CR).
- Grado de rompecabezas: **medio-alto** (famoso pero sin explicación causal comprehensiva). Promesa: **alta** (datos públicos abundantes, variación de política subnacional).

### Gaps
- No obtuve la TGF oficial 2024 de Uruguay (MSP/INE) ni la de Argentina (DEIS); las cifras de Uruguay son de CEPAL/agregadores.
- No verifiqué el tamaño de la revisión a la baja de UN WPP entre rondas (2019 vs. 2024) para estos países.
- No encontré evaluaciones causales del Plan ENIA (Argentina).
- No verifiqué la fecundidad por nacionalidad de la madre en Chile.

---

## Rompecabezas 3 — La fecundidad se desplomó, pero la participación laboral femenina se estancó (~50-52%) desde mediados de los 2000

### Takeaway
La teoría (y la experiencia de la región entre 1960 y 2000) predice que menos hijos → más participación laboral femenina. Pero la participación femenina se desaceleró marcadamente en los 2000s y se estancó alrededor de 50-53% hasta 2024, justo mientras la TGF regional caía bajo el reemplazo (desde 2015) y a 1,8 (2024). La explicación de Gasparini y Marchionni (efecto ingreso del boom de los 2000s) es plausible pero descriptiva y no encaja bien con el estancamiento posterior a 2014, cuando el crecimiento terminó.

### Cited Findings
**Hechos**
- [HECHO] Con microdatos de 15 países (1992-2012), la tasa de aumento de la participación laboral femenina se desaceleró significativamente en los 2000s, terminando una tendencia de al menos 50 años; la desaceleración es más visible entre mujeres casadas y vulnerables — Gasparini y Marchionni (2015/2017), CEDLAS WP 181; *Economía* 18(1):197-224 — [CEDLAS](https://www.cedlas.econo.unlp.edu.ar/wp/en/?p=3952); [LSE Research Online](https://researchonline.lse.ac.uk/id/eprint/123208); [RePEc WP 0181](https://econpapers.repec.org/RePEc:dls:wpaper:0181).
- [HECHO] CEPAL (2017): participación femenina "estancada en torno al 53%" — [elDinero](https://eldinero.com.do/?p=38051); [La Prensa HN](https://www.laprensa.hn/mundo/cepal-participacion-laboral-femenina-se-ha-estancado-en-53-en-america-PALP1050870).
- [HECHO] Máximo histórico 51,8% (2019) vs. 75,5% hombres; caída a 46,4% en 2020 (−5,4 pp, 13,1 millones de empleos femeninos perdidos); 52,1% en 2T-2024 vs. 74,3% hombres (OIT, Panorama Laboral 2024) — [Revista EyN](https://www.revistaeyn.com/especiales/mujeres-desafiantes/por-que-las-mujeres-siguen-marginadas-en-el-ambiente-laboral-HL14869824); [Bolsamanía](https://www.bolsamania.com/noticias/economia/economia--la-pandemia-destruye-mas-de-13-millones-de-empleos-entre-las-mujeres-de-latinoamerica-y-el-caribe--7833430.html); [Bloomberg Línea](https://bloomberglinea.com/latinoamerica/participacion-laboral-en-america-latina-bolivia-y-peru-lideran-segun-la-oit/). Discrepancia: CEPAL ~50% vs. OIT 52,1% (metodologías distintas).
- [HECHO] TGF regional bajo reemplazo desde 2015; 1,8 en 2024 — [CEPAL Observatorio Demográfico 2025](https://repositorio.cepal.org/server/api/core/bitstreams/5a21ab2b-3d99-4105-8c37-8dddf040ae66/content).
- [HECHO] Brecha de participación entre mujeres con hijos <6 años: 42,6 pp vs. 29,2 pp promedio (OIT) — [Revista EyN](https://www.revistaeyn.com/especiales/mujeres-desafiantes/por-que-las-mujeres-siguen-marginadas-en-el-ambiente-laboral-HL14869824).

**Cómo lo presenta la prensa (solo buscador)**
- Encuadre "brecha que no se cierra" y "economía del cuidado": La Prensa HN/elDinero (2017, citando CEPAL); Revista EyN; Bloomberg Línea (2024, ranking de participación con Bolivia y Perú a la cabeza). La prensa casi nunca conecta el estancamiento con la caída de la fecundidad.

**Explicaciones existentes**
- H1 Efecto ingreso del boom 2003-2013 (menor desempleo masculino, mayores salarios de la pareja, transferencias) redujo la necesidad de trabajos de baja calidad — Gasparini y Marchionni (2015/2017). Calidad: **Descriptiva** (descomposiciones; hipótesis consistente, no identificada).
- H2 Carga de cuidado infantil / falta de oferta de cuidado — OIT, CEPAL. Calidad: **Descriptiva** (correlación transversal; no explica el cambio en el tiempo cuando el número de hijos cae).
- H3 Transferencias condicionadas desincentivan oferta laboral — la evidencia experimental de PTC en general encuentra efectos pequeños/nulos en oferta laboral adulta (conocimiento previo; **no verificado en esta búsqueda**). Calidad: Parcial causal en contra de H3.

### Inferences
- [INFERENCIA] Por qué la explicación es pobre: H1 predice que el estancamiento termina con el fin del boom (2014); pero continuó en 2014-2019 pese a la recesión en Brasil/Argentina y a la caída de la fecundidad. La caída de la fecundidad fue concentrada en adolescentes y jóvenes de bajo nivel educativo (ver Rompecabezas 2), cuyo margen de participación podría ser menor, pero nadie lo ha cuantificado.
- [INFERENCIA] Hipótesis candidatas: (i) composición: la caída de fecundidad ocurre en grupos (adolescentes estudiantes) que de todos modos no participan → la elasticidad agregada es baja; (ii) aumento de matrícula terciaria femenina retrasa la entrada; (iii) envejecimiento: cuidado de adultos mayores sustituye cuidado infantil; (iv) informalidad y el "techo" de empleos de calidad.
- [INFERENCIA] Variación discriminante: usar el shock de fecundidad de los implantes en Uruguay (Ceni et al.) o el Plan ENIA en Argentina como instrumento para la oferta laboral de mujeres jóvenes; comparar Chile/Costa Rica (caída brutal de TGF) vs. países con caída lenta en un diseño de cohortes; descomposición shift-share por edad-educación-estado conyugal con SEDLAC.
- [INFERENCIA] Datos: SEDLAC/CEDLAS armonizado (público con registro), IPUMS-International (censos 2001-2024), encuestas de empleo nacionales (CASEN, ECH, EPH, ENAHO CR, PNAD-C).
- Grado de rompecabezas: **medio-alto**. Promesa: **alta** (combina dos tendencias documentadas con una pregunta causal nítida).

### Gaps
- No obtuve series WDI/ILOSTAT por país (API bloqueada); no verifiqué si Chile y Costa Rica en particular aumentaron participación femenina 2015-2024 (posible heterogeneidad).
- No vi el texto completo de Gasparini-Marchionni para citar magnitudes exactas.

---

## Rompecabezas 4 — Uruguay: país de ingreso alto con uno de los egresos de educación media más bajos de América Latina

### Takeaway
Uruguay —el país con mayor PIB per cápita, menor desigualdad y menor pobreza de la región en varios rankings, y pionero educativo del siglo XX— tenía solo 42,7% de jóvenes de 21-23 años con educación media completa en 2019 (+10,5 pp desde 2006), una de las peores posiciones de la región, pese a la expansión fuerte del gasto educativo y de transferencias en 2005-2019. Luego el egreso saltó a 50,9% (2022) y 51,6% (2023). Ni el rezago ni el salto reciente tienen una explicación convincente.

### Cited Findings
**Hechos**
- [HECHO] Egreso de educación media (21-23 años): 42,7% en 2019, +10,5 pp desde 2006 (INEEd, Mirador Educativo) — [El Observador, ago-2019](https://www.elobservador.com.uy/nota/anep-incumplio-tres-de-las-cuatro-metas-de-egreso-fijadas-para-liceales-en-2018-2019811470); otra fuente da 43,3% para 2019 → 50,9% en 2022 — [Montevideo Portal](https://www.montevideo.com.uy/Noticias/Sube-porcentaje-de-jovenes-que-terminan-bachillerato-paso-de-43-3-a-50-9-en-tres-anos-uc872595); 51,6% en 2023 (ECH-INE), "una de las peores posiciones en ALC" — [INEEd, "Adolescentes, jóvenes y empleo en la educación media"](https://redi.anii.org.uy/jspui/bitstream/20.500.12381/3795/1/Adolescentes-jovenes-empleo-educacion-media.pdf); [Prensa Mercosur, jun-2024](https://prensamercosur.org/2024/06/19/1476144-el-preocupante-estado-de-la-educacion-media-en-uruguay-segun-el-ineed/).
- [HECHO] ANEP no cumplió 3 de 4 metas de egreso para 2018 (ciclo básico 65,7% vs. meta 68%) — [El Observador](https://www.elobservador.com.uy/nota/anep-incumplio-tres-de-las-cuatro-metas-de-egreso-fijadas-para-liceales-en-2018-2019811470).
- [HECHO] CAF (2021): entre nacidos en los 1980s solo 40% completó secundaria en Uruguay vs. 50% promedio de ALC; Uruguay quedó rezagado desde cohortes nacidas en 1950 (citado en resultado de búsqueda; no abrí el informe CAF — **verificar**) — [INEEd/ANII "40 años de egreso de la educación media en Uruguay"](https://redi.anii.org.uy/jspui/bitstream/20.500.12381/3839/1/40-anos-de-egreso-de-la-educacion-media-en-Uruguay.pdf).
- [HECHO] Varones con más rezago, deserción y menor culminación (UdelaR) — [Dialnet](https://dialnet.unirioja.es/descarga/articulo/8665791.pdf).

**Cómo lo presenta la prensa (solo buscador)**
- El Observador (8-feb-2024), "Por qué en el 'campeonato educativo' Uruguay no le compite a los mejores de la clase" — [URL](https://www.elobservador.com.uy/nota/por-que-en-el-campeonato-educativo-uruguay-no-le-compite-a-los-mejores-de-la-clase--20242719590).
- la diaria/La Mañana, "Educación y empleo en jóvenes: dos caras de una misma moneda" — [URL](https://www.xn--lamaana-7za.uy/actualidad/educacion-y-empleo-en-jovenes-dos-caras-de-una-misma-moneda).
- Montevideo Portal (2023-2024): celebra el salto 43,3% → 50,9% como logro de la reforma educativa — [URL](https://www.montevideo.com.uy/Noticias/Sube-porcentaje-de-jovenes-que-terminan-bachillerato-paso-de-43-3-a-50-9-en-tres-anos-uc872595).
- Encuadre: "paradoja uruguaya", disputa política (reforma "Transformación Educativa" vs. sindicatos docentes), desigualdad socioeconómica.

**Explicaciones existentes**
- H1 Origen socioeconómico / segregación — literatura sociológica; Menese Camargo sostiene que las explicaciones solo por nivel socioeconómico "están agotadas" — [Cuadernos de Investigación Educativa, DOAJ](https://doaj.org/article/d24c123ad29540e48f4d14165d4c5ef9). Calidad: **Descriptiva**.
- H2 Transferencias (Asignaciones Familiares-Plan de Equidad 2008) con condicionalidad educativa: efecto positivo en media básica, nulo/negativo en media superior — Menese Camargo (2021) — [Dialnet](https://dialnet.unirioja.es/descarga/articulo/7848135.pdf). Calidad: **Parcial causal** (sobre la política, no sobre el rezago).
- H3 Repetición/extraedad (Uruguay entre los peores junto a Brasil) — [Redipe](https://revista.redipe.org/index.php/1/article/download/1907/1879/3066). Calidad: **Descriptiva** (mecanismo próximo, no causa última).
- H4 Diseño institucional: matriz humanista/academicista del liceo, déficit docente, expansión sin diversificación — Filardo y Mancebo (2013); tesis sobre déficit docente — [CLACSO](https://biblioteca-repositorio.clacso.edu.ar/bitstream/CLACSO/10607/2/32parte.pdf). Calidad: **Especulación/descriptiva**.
- H5 Mercado laboral juvenil atractivo (alto salario relativo sin título) — implícito en INEEd ("adolescentes, jóvenes y empleo"). Calidad: **Descriptiva**.

### Inferences
- [INFERENCIA] Por qué la explicación es pobre: ninguna hipótesis explica por qué Uruguay diverge de Chile o Argentina con ingreso y gasto similares, ni por qué la mejora 2006-2019 fue tan lenta y la de 2019-2022 tan rápida. **Advertencia de medición (inferencia):** la ECH del INE cambió de diseño en 2020-2021 (pandemia: modalidad telefónica y panel; **no verificado en esta búsqueda**); el salto 2019→2022 podría ser parcialmente artefacto. Debe verificarse antes de usar.
- [INFERENCIA] Hipótesis candidatas: (i) altos retornos a la experiencia laboral temprana y bajos retornos al bachillerato en el interior (boom agropecuario 2004-2014 elevó salarios no calificados); (ii) política de repetición/promoción (cambios de reglamento de pasaje de grado en 2023 podrían mecánicamente elevar egreso); (iii) shock de expansión de la oferta técnica (UTU) vs. liceo.
- [INFERENCIA] Variación discriminante: variación departamental en el boom agrícola (precios de commodities × especialización departamental, shift-share) y egreso por cohorte; cambios de reglamento de evaluación/promoción con discontinuidades de cohorte; apertura escalonada de liceos de tiempo completo/extendido.
- [INFERENCIA] Datos: ECH (INE, pública) 2006-2024; registros administrativos ANEP (Sistema de Protección de Trayectorias, acceso restringido); censos 2011 y 2023 (IPUMS-I tendrá 2011); PISA y ERCE para logro.
- Grado de rompecabezas: **alto** (contradice ingreso y tradición educativa). Promesa: **alta** (Uruguay tiene excelentes datos administrativos y una reforma reciente con calendario).

### Gaps
- No obtuve comparaciones internacionales precisas de egreso (CEPAL/SITEAL/UIS) para 2019-2023; la afirmación "una de las peores de ALC" proviene del INEEd.
- No verifiqué el cambio metodológico de la ECH ni su efecto en este indicador.
- No abrí el informe CAF 2021.

---

## Rompecabezas 5 — Suicidio: Uruguay como valor atípico creciente en el Cono Sur; Guyana y Surinam con las tasas más altas de las Américas

### Takeaway
Uruguay alcanzó 23,3 suicidios por 100.000 en 2022 (récord), 21,35 en 2024 y 19,16 en 2025, más del doble del promedio de las Américas (~9 en 2019), con una tendencia ascendente desde los 1990s-2000. Guyana fue estimada por la OMS como el país con la tasa más alta del mundo en 2012, y Guyana y Surinam encabezan las Américas. Los dos casos combinan alto desarrollo (Uruguay) y baja capacidad estatal (Guyana), y las explicaciones son sociológicas genéricas o centradas en el acceso a plaguicidas, sin identificación.

### Cited Findings
**Hechos**
- [HECHO] Uruguay: 23,3/100.000 en 2022 (récord), solo detrás de Guyana y Surinam en Sudamérica; promedio de las Américas 9/100.000 en 2019 — [MercoPress](https://en.mercopress.com/2022/07/01/uruguay-the-worst-in-the-americas-for-suicides-reached-a-new-record-for-self-murders-in-2021); [infonews/AP](https://infonews.ca/?p=2445277).
- [HECHO] Uruguay 2024: 764 suicidios, tasa 21,35/100.000; intentos de autoeliminación 161,74/100.000 (2024) vs. 132,42 (2023); 2025: 668 muertes, 19,16/100.000 (MSP) — [Montevideo Portal](https://www.montevideo.com.uy/Modo-saludable/Suicidio-en-Uruguay-764-personas-se-quitaron-la-vida-durante-el-2024-segun-el-MSP-uc930443); [El Observador, 17-jul-2025](https://www.elobservador.com.uy/nacional/datos-suicidios-2024-uruguay-cifras-autoeliminacion-jovenes-tuvieron-un-aumento-significativo-los-ultimos-anos-n6008945); [Prensa Mercosur, abr-2026](https://prensamercosur.org/2026/04/16/se-suicidan-25-personas-cada-100-000-en-uruguay-id192093/) (titular "25 por 100.000" no coincide con 21,35 — **discrepancia; usar MSP**). 2023: 763 muertes (−7,3%) — [Montevideo Portal](https://www.montevideo.com.uy/Archivo/Suicidios-bajaron-7-3--en-2023-hubo-763-muertes-por-esa-causa-segun-MSP-uc894351).
- [HECHO] Perfil: 78% hombres; tasas más altas en >75 años y 25-29 años; más alto en zonas rurales; MSP señala 20-24 como grupo de preocupación — [infonews/AP](https://infonews.ca/?p=2445277); [El Observador](https://www.elobservador.com.uy/nacional/datos-suicidios-2024-uruguay-cifras-autoeliminacion-jovenes-tuvieron-un-aumento-significativo-los-ultimos-anos-n6008945).
- [HECHO] En Argentina y Uruguay el suicidio ya causa más muertes que los homicidios — [Vozpópuli](https://www.vozpopuli.com/internacional/el-suicidio-ya-causa-mas-muertes-en-argentina-y-uruguay-que-los-homicidios.html).
- [HECHO] Guyana: tasa estimada más alta del mundo en 2012 (OMS); Surinam sexta — [Stabroek News](https://stabroeknews.com/?p=303508). Revisión 2024 (IJERPH): Guyana y Surinam primera y segunda en las Américas; más prevalente en comunidades indo-caribeñas; métodos principales plaguicidas y ahorcamiento; casos concentrados en Essequibo y Berbice; datos domésticos escasos — [IJERPH 21(6):801 (espejo)](https://p.gyb.elementfx.com/1660-4601/21/6/801); [WTOP/AP 2014](https://wtop.com/news/2014/10/sleepy-guyana-wrestles-with-high-rate-of-suicides/). Una cifra de 30,2 (Guyana) y 19,4 (Surinam) para 2019 aparece solo en un blog — **no verificado**.

**Cómo lo presenta la prensa (solo buscador)**
- BBC Mundo (Gerardo Lissardy), "¿Por qué se suicidan los uruguayos?" (republicado por IntraMed; fecha no visible) — [URL](https://www.intramed.net/content/por-que-se-suicidan-los-uruguayos).
- AP (2023), "Uruguay suicide rate reaches new record in 2022, cementing position as outlier in region"; el sociólogo Pablo Hein (citado) dice que ningún parámetro explica la tasa, que es "cultural y social", y menciona posible subregistro médico — [infonews/AP](https://infonews.ca/?p=2445277).
- Cuenca HighLife, "Why does one of the happiest countries have one of the highest suicide rates?" — [URL](https://cuencahighlife.com/?p=127289).
- Guyana: Stabroek News, Fox News/AP ("haunted by link to cult deaths") — [Fox](https://www.foxnews.com/world/report-finds-highest-suicide-rate-world-in-guyana-a-country-haunted-by-link-to-cult-deaths).

**Explicaciones existentes**
- H1 Anomia/integración durkheimiana; fenómeno masculino creciente con la edad; alto desde los 1960s — Robertt (1999), "El suicidio en Uruguay", *Salud Problema* — [PDF UdelaR](https://suicidioprevencion.cienciassociales.edu.uy/wp-content/uploads/2015/09/El-suicidio-en-Uruguay-Pedro-Robertt.pdf). Calidad: **Descriptiva**.
- H2 Envejecimiento, ruralidad, aislamiento, alcohol, acceso a armas de fuego (Uruguay) — prensa y psicólogos (Di Pascua). Calidad: **Especulación en prensa**.
- H3 Plaguicidas + pobreza rural + alcohol + etnia indo-caribeña (Guyana/Surinam) — revisiones y prensa. Calidad: **Descriptiva** (la evidencia causal de restricción de plaguicidas existe en Sri Lanka, no en Guyana — conocimiento previo, **no verificado aquí**).
- H4 Diferencias de registro (Uruguay registra bien; otros países subregistran) — implícito. Calidad: **Ninguna** evaluación formal.

### Inferences
- [INFERENCIA] Por qué la explicación es pobre: "cultura" y "anomia" son explicaciones no falsables; el envejecimiento no explica el aumento entre jóvenes (25-29) ni que Uruguay supere a Argentina/Chile con estructuras etarias parecidas; la hipótesis de registro no ha sido cuantificada (p. ej., comparando "muertes de intención indeterminada" entre países).
- [INFERENCIA] Hipótesis candidatas: (i) subregistro diferencial en países vecinos (reclasificación de causas mal definidas); (ii) acceso a medios letales (armas de fuego en zonas rurales uruguayas; plaguicidas en Guyana); (iii) choques económicos sectoriales (precio de commodities agrícolas) en departamentos rurales; (iv) contagio mediático (Uruguay tiene pautas de comunicación del MEC).
- [INFERENCIA] Variación discriminante: series departamentales de suicidio vs. shocks de precios agrícolas (shift-share); regulaciones de plaguicidas en Guyana/Surinam (prohibiciones de paraquat u otros, fechas por verificar) en un diseño de eventos; comparación de causas mal definidas entre Uruguay, Argentina y Chile para un ajuste de subregistro.
- [INFERENCIA] Datos: microdatos de defunciones MSP Uruguay, DEIS Argentina/Chile (públicos); OPS/PAHO mortality database; Guyana: datos escasos (Ministerio de Salud; posible acceso restringido).
- Grado de rompecabezas: **alto** (Uruguay contradice la relación desarrollo–bienestar). Promesa: **media** (datos de Uruguay buenos; Guyana pobres; dificultad de identificación).

### Gaps
- No obtuve la serie anual de Uruguay 2000-2020 de fuente oficial (la afirmación "ascenso desde 2000" viene del MSP vía resumen de búsqueda).
- No verifiqué tasas OMS estandarizadas por edad recientes para Guyana/Surinam.
- No vi el texto del artículo BBC Mundo ni su fecha.

---

## Rompecabezas 6 — Caribe anglófono: las mujeres superan ampliamente a los hombres en educación, pero no en el mercado laboral; los varones se estancan

### Takeaway
En Jamaica, Barbados y Trinidad y Tobago, las mujeres tienen tasas de aprobación CSEC más altas en todas las materias y en todos los grupos socioeconómicos, y la matrícula terciaria femenina es ~1,4-1,6 veces la masculina (índice de paridad). Jamaica tiene la mayor proporción de gerentes mujeres del mundo (OIT 2015). Sin embargo, las mujeres siguen teniendo menor empleo y salario. La explicación dominante (socialización de la masculinidad, "marginación del varón") es sociológica y casi sin identificación; un trabajo descompone el 78% de la brecha CSEC en atributos escolares y elección de materias.

### Cited Findings
**Hechos**
- [HECHO] Índice de paridad de género en matrícula terciaria (UNESCO, mujer/hombre): Barbados 1,55 (2011), Antigua y Barbuda 1,55 (2012), Jamaica 1,43 (2015); máximo jamaicano 1,57 (2009) vs. 0,61 (1974) — [IndexMundi ranking](https://www.indexmundi.com/facts/indicators/SE.ENR.TERT.FM.ZS/rankings/central-america); [IndexMundi Jamaica](https://www.indexmundi.com/facts/jamaica/ratio-of-female-to-male-tertiary-enrollment). (Datos recuperados en 2019 — **actualizar con UIS**.)
- [HECHO] Datos CSEC de Jamaica (2020), Barbados (2020) y Trinidad y Tobago (2016): mujeres con mayores tasas de aprobación y más resultados sobresalientes en todas las materias; ventaja femenina en todos los grupos socioeconómicos; matrícula y conclusión primaria similares, divergencia en la secundaria — [BID 2024](https://www.iadb.org/en/gender-gaps-education-caribbean-are-girls-doing-better-boys); [comunicado BID](https://www.publicnow.com/view/FBA33ADFBD8D6149B45C45D1E1D5A90B839AD0FE).
- [HECHO] Jamaica: mujeres 8,5 pp más probables de aprobar una materia CSEC; atributos escolares, mezcla y elección de materias explican hasta 78% de la brecha — Wright, FIU Working Paper 2410, "Girls Dominate, Boys Left Behind" — [RePEc](https://econpapers.repec.org/RePEc:fiu:wpaper:2410).
- [HECHO] 2013: 3.878 varones vs. 7.373 mujeres alcanzaron el estándar de matriculación universitaria en Jamaica (fuente académica citada en resultados) — [Springer capítulo (vía proxy)](https://springerlink.bibliotecabuap.elogim.com/10.1007/978-3-319-33344-1_7).
- [HECHO] Jamaica tenía la mayor proporción de gerentes mujeres del mundo según estudio OIT (2015) — [Nation News/AP](https://nationnews.com/?p=105381). Pese a mayor educación, las mujeres trabajan en sectores peor pagados y ganan menos (Banco Mundial, OECS + Jamaica) — [Blog Banco Mundial](https://blogs.worldbank.org/en/latinamerica/five-trends-gender-inequality-caribbean); brecha salarial persistente (BDC 2025) — [Jamaica Observer](https://www.jamaicaobserver.com/2025/05/30/cdb-study-urges-policy-reform-tackle-labour-market-inequities/); los resultados laborales de las mujeres son peores que los de los hombres — [BID CIMA Brief 24](https://publications.iadb.org/publications/english/document/CIMA-Brief-24-Are-Gender-Gaps-Increasing-in-the-Caribbean.pdf).
- [HECHO] Ministerio de Educación de Jamaica anunció (ago-2026) intervenciones focalizadas para varones — [Jamaica Gleaner, 28-ago-2026](https://jamaica-gleaner.com/article/news/20260828/education-ministry-moves-address-boys-underperformance-schools).

**Cómo lo presenta la prensa (solo buscador)**
- AP (feb-2015), "Caribbean's different gender gap: women rise, men stagnate" (Nation News, CARICOM Today, Jakarta Post) — [Nation News](https://nationnews.com/?p=105381); [CARICOM Today](https://today.caricom.org/?p=4069).
- Jamaica Observer (27-jul-2026), "Failing the boys" — [URL](https://www.jamaicaobserver.com/2026/07/27/failing-the-boys/).
- Kaieteur News (Guyana, 18-ago-2025), opinión: los varones recuperan terreno en matemáticas/ciencias — [URL](https://kaieteurnewsonline.com/2025/08/18/boys-starring/).
- Encuadre: "crisis de los varones", criminalidad juvenil, masculinidad tóxica, escuelas mono-sexo.

**Explicaciones existentes**
- H1 Socialización de género en la escuela (los varones esperan ser "duros", más castigos; burlas a varones estudiosos como "afeminados") — Evans (1999), análisis de género UWI — [UWI Mona](https://www.mona.uwi.edu/cop/node/396). Calidad: **Descriptiva/cualitativa**.
- H2 Costo de oportunidad: varones retirados para trabajar; niñas se quedan para retrasar embarazo; empleo masculino más alto a todo nivel educativo (rendimiento educativo menor para varones) — BID 2024. Calidad: **Descriptiva**.
- H3 Atributos escolares y elección de materias — Wright (FIU WP 2410). Calidad: **Descriptiva** (descomposición Oaxaca-Blinder; mecanismo contable).
- H4 Tesis de la "marginación del varón negro" — Errol Miller (1986, libro) — **referencia de memoria, no verificada en esta búsqueda**. Calidad: **Especulación/teoría sociológica**.
- H5 Escuelas mono-sexo — grupo de educadores jamaicanos (anecdótico). Hay un estudio experimental/cuasi-experimental de K. Jackson sobre escuelas mono-sexo en Trinidad y Tobago (**de memoria, no verificado aquí**). Calidad: Parcial causal en un mecanismo.

### Inferences
- [INFERENCIA] Por qué la explicación es pobre: las explicaciones de "socialización" no explican por qué la brecha es mucho mayor en el Caribe anglófono que en América Latina hispana con normas de masculinidad similares, ni por qué la ventaja educativa femenina no se traduce en salarios (contradice modelos de capital humano).
- [INFERENCIA] Hipótesis candidatas: (i) retorno educativo diferencial (mercados laborales masculinos en construcción/turismo/economía ilícita pagan poco por credenciales); (ii) estructura familiar (alta proporción de hogares con jefatura femenina y padres ausentes) afecta más a varones (como en la literatura de EE.UU. sobre "boys and family structure"); (iii) migración selectiva de varones calificados; (iv) violencia y pandillas como opción exterior.
- [INFERENCIA] Variación discriminante: asignación de escuelas secundarias por examen (GSAT/PEP en Jamaica; SEA en Trinidad) → RDD por género; variación entre parroquias en tasa de homicidios/economía ilícita; shocks de demanda de trabajo masculino (construcción, bauxita) por parroquia × cohorte.
- [INFERENCIA] Datos: microdatos CXC/CSEC (restringidos, vía Ministerios/CXC); Jamaica Survey of Living Conditions y Labour Force Survey (STATIN); censos IPUMS-I (Jamaica 2001, 2011; Trinidad y Tobago 2000, 2011 — disponibilidad por verificar).
- Grado de rompecabezas: **medio** (el hecho es conocido regionalmente pero poco en la literatura de economía del desarrollo). Promesa: **media-alta** (diseños RDD de asignación escolar disponibles).

### Gaps
- No obtuve índices de paridad terciaria UIS posteriores a 2015 ni la composición actual de la UWI.
- No verifiqué Miller (1986) ni el trabajo de Jackson sobre escuelas mono-sexo.
- No obtuve brechas salariales cuantitativas recientes por educación.

---

## Rompecabezas 7 (bajo-medio) — Perú: la informalidad se estanca en ~70% tras dos décadas de crecimiento

### Takeaway
El empleo informal cayó de 79,9% (2007) a 73,2% (2015) durante el auge, y luego se estancó en torno a 70-74% (74% en 2022; ~71% posteriormente). La correlación crecimiento–formalización se debilitó tras 2013. El patrón es famoso y tiene explicaciones parciales (productividad, regulación, estructura de empresas), así que su valor como "rompecabezas poco conocido" es bajo; se mantiene como caso de control para los demás.

### Cited Findings
- [HECHO] Empleo informal 79,9% (2007) → 73,2% (2015) (INEI) — [ProActivo](https://proactivo.com.pe/empleo-informal-retrocedio-a-732-entre-2007-y-2015-dice-inei/).
- [HECHO] Empleo informal en el sector informal: 60,8% → 54,2% en 2007-2013 (PIB +6,1% anual); 53,1% → 52,4% en 2014-2017 (PIB +3,2%) (INEI, Cuenta Satélite) — [INEI Lib1589](https://www.inei.gob.pe/media/MenuRecursivo/publicaciones_digitales/Est/Lib1589/libro.pdf).
- [HECHO] 74% en 2022 (EPEN); 70,9% al cierre del año siguiente (según Gestión; año exacto en el snippet poco claro) — [Gestión](https://gestion.pe/economia/informalidad-en-peru-cayo-pero-en-10-ciudades-la-situacion-fue-otra-como-entenderlo-empleo-en-peru-puestos-de-trabajo-inei-mercado-laboral-noticia/); "siete de cada diez" en 2024 — [UNIR](https://www.unir.net/actualidad/internacional/siete-cada-diez-trabajadores-peruanos-informales/).
- Prensa: Gestión, Expreso ("Formalización laboral como política de Estado") — [Expreso](https://www.expreso.com.pe/opinion/formalizacion-laboral-como-politica-de-estado/). Explicaciones: BCRP (revista Moneda) — [BCRP Moneda 196](https://www.bcrp.gob.pe/docs/Publicaciones/Revista-Moneda/moneda-196/moneda-196-08.pdf) (no abierta).

### Inferences
- [INFERENCIA] La explicación existente (baja productividad de microempresas, costos de formalización, desaceleración) es **Parcial causal/Descriptiva** y ampliamente estudiada (Loayza, Levy, etc.; **no verificado en esta búsqueda**). Lo menos explicado es la heterogeneidad urbana (Gestión reporta que en 10 ciudades la informalidad subió mientras la nacional bajaba).
- [INFERENCIA] Variación útil: ciudades con distinta exposición al boom minero (shift-share por precio de metales) vs. trayectoria de informalidad; datos ENAHO (pública, panel).
- Grado de rompecabezas: **bajo-medio**. Promesa: **media** (literatura saturada).

### Gaps
- No obtuve una serie INEI consistente 2007-2024 con una sola definición.

---

## Patrones verificados parcialmente, descartados o desprioritizados

### Takeaway
Varios candidatos semilla se descartaron por estar bien explicados, por concentrarse antes de 2001, por falta de verificación numérica en esta búsqueda, o por estar fuera del tema de desarrollo humano.

### Cited Findings
- **Guatemala, desnutrición crónica ~46,5% (ENSMI 2014-2015)**: persistente; ritmo ~0,34 pp/año; rango 25% (Ciudad de Guatemala) a 70% (Totonicapán); quintil más rico 17% vs. más pobre 66%; madres sin educación 67% — [Boletín USAC](https://en-ccqqfar.usac.edu.gt/wp-content/uploads/2018/10/Boletín-No.-1-Derecho-a-la-Alimentación.pdf); [FANTA PROFILES](https://www.fantaproject.org/sites/default/files/resources/Guatemala-PROFILES-Report-Summary-ESPANOL-Oct2017.pdf). Sin nueva ENSMI reciente según El Observador GT — [Boletín Enfoque 90](https://elobservadorgt.org/wp-content/uploads/2024/03/Boletin-Enfoque-Analisis-de-situacion-No.-90-Se-cumplieron-las-promesas-de-la-Gran-Cruzada-Nacional-por-la-Nutricion-GCNN.pdf). **Decisión: desprioritizado** — la persistencia está razonablemente explicada por pobreza indígena rural, 1.000 días, talla materna e intergeneracionalidad (literatura extensa INCAP/Lancet; no verifiqué aquí), y el principal problema actual es la falta de datos nuevos más que un rompecabezas. El contraste Guatemala vs. Perú (que redujo la desnutrición fuertemente después de 2008; **cifra no verificada aquí**) podría convertirse en rompecabezas si se verifica.
- **Ecuador, aumento de homicidios post-2018**: no verificado en esta búsqueda; además la explicación (rutas de cocaína, crisis carcelaria y fragmentación de bandas) es ampliamente aceptada → **descartado**.
- **Brecha de fecundidad adolescente (RD, Nicaragua, Ecuador altas)**: no pude descargar la serie WDI SP.ADO.TFRT (API bloqueada) → **sin verificar**; se recomienda verificar con UN WPP 2024 antes de incluir. Parcialmente subsumido en el Rompecabezas 2 (divergencia Cono Sur vs. Centroamérica/Caribe).
- **México estancamiento salarial, Costa Rica aumento de la desigualdad, Brasil "nem-nem", Haití, Cuba envejecimiento**: no investigados por límite de llamadas; Costa Rica (aumento de Gini en los 2000s) tiene literatura (Gindling y Trejos, **no verificado**).
- Patrones centrados en 1985-2000 eliminados por la actualización de alcance.

### Inferences
- [INFERENCIA] El hilo común más prometedor para una tesis es el vínculo entre los Rompecabezas 2 y 3: un shock de fecundidad grande, rápido y parcialmente exógeno (implantes en Uruguay, Plan ENIA en Argentina) que puede usarse para estudiar oferta laboral, educación y uniones, en un contexto de datos públicos excelentes.
- [INFERENCIA] El caso dominicano (Rompecabezas 1) es el más "olvidado" por la economía del desarrollo y tiene una pregunta nítida: ¿por qué la mortalidad materna sube con acceso universal?

### Gaps
- Las restricciones de red impidieron verificar series WDI/UN WPP/UIS/ILOSTAT directamente; todas las cifras dependen de snippets de búsqueda de fuentes oficiales o prensa que citan fuentes oficiales.
- Ninguna URL fue abierta con WebFetch (todas "solo buscador"); ninguna URL fue inventada.
