# Patrones colombianos sin explicar (1985-2026): demografía, fecundidad y familia

**Nota de método (leer primero).**
- Herramientas: solo WebSearch (buscador). WebFetch falló para `www.dane.gov.co` y `api.worldbank.org`: el entorno no los resuelve. Bash/curl a `api.worldbank.org` recibió 403 del proxy. **Ninguna URL de prensa ni PDF fue "abierto"**. Todo lo citado es **"solo buscador"**: proviene de títulos o fragmentos devueltos por el buscador. Las cifras deben verificarse contra el PDF original del DANE antes de usarse en un paper.
- No inventé URLs: todas aparecieron en resultados de búsqueda. Las "inferencias" van etiquetadas.
- Escala de calidad de la explicación: Ninguna / Especulación en prensa / Descriptiva / Parcial causal / Bien explicada (→ descartar).
- Consultas usadas (en orden): "DANE tasa global de fecundidad 2024 Colombia 1,2 nacimientos"; "Colombia caída natalidad explicación demógrafos 2025 nacimientos 2025 DANE"; "Colombia adolescent fertility paradox rise 1990-2005 DHS"; "Esteve Lesthaeghe cohabitation Colombia education gradient census"; "censo 2018 omisión censal 8,5% población menor proyecciones explicación DANE"; "Caldas fecundidad 0,7 hijos por mujer Eje Cafetero por qué tan baja"; "nacimientos niñas 10 a 14 años Colombia 2024 2025 DANE cifra"; "Colombia hogares unipersonales jefatura femenina porcentaje DANE 2024 GEIH"; "proyecciones de población DANE 2018 supuesto fecundidad sobrestimaron nacimientos Banco de la República…"; "Colombia embarazo adolescente caída desde 2015 causas implante subdérmico estudio causal"; "Latin America ultra-low fertility Colombia Chile Uruguay rapid decline 2015-2023 paper"; "Urdinola Ospino adolescent fertility Colombia Demographic Research 2015"; "DANE 2024 tasa específica fecundidad 15 a 19 años … madres venezolanas"; "unión libre Colombia censo 2018 porcentaje matrimonio … educación"; "World Bank fertility rate Colombia 2023 lowest Latin America…"; "Colombia fertility decline Venezuelan migration births economics paper"; "Banco de la República documento caída de la natalidad … Borradores"; "Colombia fecundidad 1,1 DANE vs Naciones Unidas 1,6 diferencia denominador…"; "Portafolio 'números históricos' principal razón caída fecundidad"; "teen pregnancy Colombia causal effect school day jornada única OR Familias en Acción"; "Batyra fertility timing childbearing Colombia"; "ENDS 2015 edad mediana primera unión región Caribe diferencia de edad pareja"; "jefatura femenina hogares Colombia aumentó 1993 2005 2018 censo explicación"; "ENDS 2025 resultados tasa global de fecundidad unión libre"; "censo 2018 omisión explicación académica emigración subestimada…"; "Early adolescent childbearing in Colombia time-trends 10-14"; "ENDS 2025 Colombia tasa global de fecundidad encuesta…"; "La FM Colombia registra más nacimientos en 2026"; "Esteve Lesthaeghe López-Gay 2012 … educated women"; "El Colombiano Antioquia fecundidad cae debajo de un hijo por mujer"; "sentencia C-055 2022 aborto caída de nacimientos"; "Universidad de los Andes informe caída natalidad…"; "hogares unipersonales Colombia censo 2005 censo 2018"; "adolescent fertility decline Colombia since 2015 explanation study"; "análisis demográfico fecundidad departamentos región cafetera 1998-2018…".
- **Ranking final (rompecabezas × promesa de investigación):**
  1. El desplome 2022-2025 de la fecundidad. ¿Por qué un 12% en un solo año sin un choque evidente?
  2. ¿Cuál es la verdadera fecundidad? DANE (1,0-1,1) frente a ONU/Banco Mundial (~1,6), con el censo 2018 y el denominador de fondo.
  3. Paradoja adolescente: subida 1990-2005 y colapso a la mitad entre 2015 y 2024.
  4. Inversión geográfica: el Eje Cafetero y Antioquia, antes región de familias grandes, hoy por debajo de 1 hijo por mujer.
  5. Boom de la unión libre: ¿transición de "desventaja" o "segunda transición demográfica"?
  6. La jefatura femenina casi se duplica (24% → 46,5%) y los hogares unipersonales pasan de 11% a 20%.
  7. Fecundidad de 10-14 años. La idea de que "no cae tan rápido" **no se confirma en tasas**, así que el puzzle es débil.
  8. Brechas de edad entre parejas, edad de primera unión por región y razón de sexos al nacer: **no verificado**. Va a Gaps.
- **Candidatos descartados por estar "explicados" o fuera de foco:**
  - Regularización (PEP) de migrantes venezolanos y fecundidad: tiene causal sólido (Amuedo-Dorantes, Ibáñez, Rozo y Traettino, *EDCC* 2025). Es estrecho y no explica la tendencia nacional.
  - Consecuencias de la maternidad adolescente (Urdinola y Ospino, 2015): tratan efectos, no causas.

---

## Puzzle 1. El desplome de la fecundidad de 2022-2025 (y no antes del COVID)

### Takeaway
La fecundidad DANE bajó lentamente entre 2016 y 2019 (1,7 → 1,6). La aceleración ocurrió **después** del COVID: 1,4 (2022) → 1,2 (2023) → 1,1 (2024) → 1,0 (2025pr). Los nacimientos cayeron 12% solo en 2024 y luego se estabilizaron (+1,5% en enero-julio de 2026). Nadie lo anticipó: las proyecciones del DANE ubicaban el decrecimiento poblacional en 2052. No hay ninguna explicación causal: la prensa repite "educación, trabajo femenino, anticonceptivos, costo de vida". Ninguno de esos factores cambió de forma discontinua en 2023-2024.

### Cited Findings
**HECHOS**
- La serie de tasa global de fecundidad (TGF) del DANE es 1,7 (2016); 1,6 (2019); 1,5 (2020 y 2021); 1,4 (2022); 1,2 (2023); 1,1 (2024); 1,0 (2025pr). Fuente: DANE, comunicado EEVV II sem 2025pr, citado por la prensa — [DANE cp-EEVV-Defunciones-IIsem2025pr (solo buscador)](https://www.dane.gov.co/files/operaciones/EEVV/2026/20-mar-2026/cp-EEVV-Defunciones-IIsem2025pr.pdf); [La FM, 2026 (solo buscador)](https://www.lafm.com.co/sociedad/nacimientos-defunciones-colombia-2026-411916).
- **Hecho clave para la usuaria:** la hipótesis de una aceleración "antes del COVID (2016-2019)" **no se sostiene** con la serie DANE (1,7 → 1,6). El quiebre es 2022-2024 — mismas fuentes.
- Nacimientos 2024: 453.901 (definitivo), −12,0% frente a 2023. La cifra preliminar era 445.011, −13,7%. La caída en la década es de ~33% — [Bloomberg Línea (solo buscador)](https://www.bloomberglinea.com/latinoamerica/colombia/nacimientos-en-colombia-cayeron-14-en-2024-y-33-en-ultima-decada/); [Semana, mar-2025 (solo buscador)](https://www.semana.com/economia/macroeconomia/articulo/fuerte-caida-de-nacimientos-en-colombia-en-2024-se-reportaron-445001-el-descenso-mas-alto-desde-2015/202503/).
- Nacimientos 2025: 433.678 en la cifra preliminar de marzo de 2026 (−4,5%) — [Noticias RCN (solo buscador)](https://www.noticiasrcn.com/colombia/natalidad-en-colombia-sigue-en-caida-dane-confirma-4-5-menos-nacimientos-en-2025-1004237). La cifra definitiva es 441.537, según La FM — [La FM (solo buscador)](https://www.lafm.com.co/sociedad/nacimientos-defunciones-colombia-2026-411916). **Discrepancia:** las preliminares subestiman en ~8-9 mil nacimientos (~2%) por registro tardío. Los titulares de "caída récord" se escriben con cifras preliminares.
- Ene-jul 2026: 253.175 nacimientos, +1,5% frente a 2025 (cifra preliminar) — [La FM (solo buscador)](https://www.lafm.com.co/sociedad/nacimientos-defunciones-colombia-2026-411916); [Consultorsalud (solo buscador)](https://consultorsalud.com/nacimientos-en-colombia-aumentaron-2026-fecundi/); [Cambio, sep-2026 "¿Se revierte la tendencia?" (solo buscador)](https://cambiocolombia.com/pais/articulo/2026/9/se-revierte-la-tendencia-dane-publica-nuevas-cifras-de-nacimientos-en-colombia-con-un-dato-inusual).
- En 2025, la desaceleración de la caída se observó en todos los departamentos menos San Andrés. Guainía, Quindío, Tolima y La Guajira tuvieron **aumentos** de nacimientos — [El Colombiano / RCN vía buscador](https://www.elcolombiano.com/negocios/caida-nacimientos-2025-dane-cifra-historica-colombia-CP34801047).
- **Proyecciones que fallaron:** en las proyecciones originales del DANE (escenario E0) el decrecimiento poblacional empezaba en 2052. BanRep construyó escenarios con datos a abril de 2024: la población empezaría a caer en 2043, 2032 o 2027. BanRep afirma que la caída "sin precedentes" de la fecundidad, sumada a la emigración, "podría haber reducido la población en 2022" — [Blog BanRep, "Cambios demográficos recientes y envejecimiento poblacional" (solo buscador)](https://banrep.gov.co/es/blog/cambios-demograficos-recientes-envejecimiento-poblacional); [Portafolio (solo buscador)](https://www.portafolio.co/economia/finanzas/poblacion-colombiana-ya-habria-caido-segun-analistas-del-banco-de-la-republica-614071). La directora del DANE, Piedad Urdinola, anunció que se rehacen las proyecciones — [Blu Radio vía buscador](https://www.bluradio.com/nacion/cada-vez-menos-colombianos-quieren-ser-papas-caida-de-los-nacimientos-empeora-rg10).
- BanRep, Borradores n.º 1308 (Parra-Polanía y Ladino Rivero, mar-2025): con la nueva natalidad, la fuerza laboral empezaría a caer entre 2043 y 2045, no en 2054 — [BanRep (solo buscador)](https://banrep.gov.co/es/publicaciones-investigaciones/borradores-economia/fuerza-trabajo-envejecimiento-poblacional).
- **Comparación regional:** CEPAL (2025) da para 2024 Chile 1,14; Costa Rica 1,32; Uruguay 1,40; Argentina 1,50 — [Guyana Chronicle citando CEPAL (solo buscador)](https://guyanachronicle.com/?p=683831). Con la cifra DANE (1,1 en 2024; 1,0 en 2025), Colombia estaría **por debajo de Chile**. Con la del Banco Mundial (1,645 en 2023), estaría a media tabla. Ver Puzzle 2.
- Uruguay vivió un desplome similar (≈2,0 en 2015 → 1,37 en 2021). Sus autores dicen que no hubo un choque económico o social que lo explique y que las causas "remain poorly understood" — [Cabella et al., *Demographic Research* 50(16), 2024 (solo buscador)](https://www.demographic-research.org/articles/volume/50/16).

**CÓMO LO PRESENTA LA PRENSA** (todas "solo buscador")
- Encuadre de alarma fiscal y pensional: [Portafolio, análisis de Ricardo Ávila](https://www.portafolio.co/economia/regiones/analisis-de-ricardo-avila-las-consecuencias-de-la-caida-de-natalidad-en-colombia-626829); [Cambio, sep-2025, "factores, implicaciones, pensiones, trabajo"](https://cambiocolombia.com/pais/articulo/2025/9/colombia-registro-menor-natalidad-decada-factores-implicaciones-pensiones-trabajo); [El Heraldo, editorial 30-dic-2024, "ese gran problema del que no se habla"](https://www.elheraldo.co/editoriales/2024/12/30/editorial-la-caida-de-la-natalidad-ese-gran-problema-del-que-no-se-habla/); [El Tiempo](https://www.eltiempo.com/salud/caida-de-la-tasa-de-natalidad-cada-vez-nacen-menos-ninos-en-colombia-que-implica-eso-3439087).
- Encuadre de "récord / más bajo que Japón y Corea": [Minuto60](https://www.minuto60.com/colombia/colombia-alcanza-su-tasa-natalidad-mas-baja-supera-japon-corea-sur/2061). Es un medio sensacionalista: compara una TGF de registro con denominadores proyectados.
- Encuadre de decisión juvenil: [Noticias Caracol, "las razones que dan jóvenes para no ser papás"](https://www.noticiascaracol.com/colombia/las-razones-que-dan-jovenes-en-colombia-para-no-ser-papas-pr30); [Consultorsalud: "solo 1 de cada 6 mujeres quiere ser madre", según ENDS 2025](https://consultorsalud.com/declive-fecundidad-en-colombia1-6-mujeres-madre/). El titular no fue verificado contra el informe de la ENDS.

**EXPLICACIONES EXISTENTES**
- "Educación y trabajo femenino, anticonceptivos, menos embarazo adolescente". Proviene de un informe Uniandes reseñado por Portafolio y del documento del Proyecto Digna (Uniandes, cualitativo y cuantitativo, mujeres menores de 30), reseñado por El Tiempo — [Portafolio](https://www.portafolio.co/economia/regiones/la-economia-del-pais-se-podria-afectar-por-la-caida-de-los-nacimientos-en-colombia-623134); [El Tiempo, "La demográfica, una crisis más"](https://www.eltiempo.com/economia/sectores/la-demografica-una-crisis-mas-3355228). **Calidad: Descriptiva o especulación.** Son tendencias lentas y no explican el salto de 2023-2024.
- "Costo de vida": Bancolombia, citado en un boletín sectorial — [Porkcolombia, boletín may-2026 (solo buscador)](https://porkcolombia.co/wp-content/uploads/2026/05/20260504-Boletin-Economia-Porcicola.pdf). **Calidad: Especulación.**
- Migración: los migrantes venezolanos "habrían mitigado" la caída de nacimientos, y el flujo se redujo tras la pandemia — [Camacol, Informe Económico 122 (solo buscador)](https://camacol.co/sites/default/files/descargables/InformeEcon%C3%B3mico_122.pdf). **Calidad: Especulación o descriptiva.** Existe evidencia causal solo para un margen: la regularización (PEP) **redujo** la fecundidad de los hogares migrantes — [Amuedo-Dorantes, Ibáñez, Rozo y Traettino, *EDCC* 2025 (solo buscador)](https://econpapers.repec.org/RePEc:ucp:ecdecc:doi:10.1086/735692); [IZA DP 16170](https://econpapers.repec.org/RePEc:iza:izadps:dp16170). Es **Parcial causal** para ese canal, pero no se ha cuantificado su peso en el agregado.
- Despenalización del aborto (Sentencia C-055, feb-2022): **no encontré ningún estudio ni nota que la vincule con la caída de nacimientos.** Se reportan cifras de IVE: 43.691 (2022), 53.723 (2023), 56.949 (2024), 59.532 (año siguiente). La fuente institucional no está clara — [Cambio (solo buscador)](https://cambiocolombia.com/genero/articulo/2026/9/cuatro-anos-despues-de-la-despenalizacion-persisten-barreras-para-acceder-al-aborto-en-colombia). **Calidad: Ninguna** (hipótesis no planteada).
- BanRep, Documento de Trabajo sobre Economía Regional y Urbana n.º 338, "Fecundidad en Colombia: evolución reciente" (Rodríguez, 2025). Usa registros de nacimientos 1998-2024 y el censo 2018 — [BanRep (solo buscador)](https://banrep.gov.co/es/publicaciones-investigaciones/documentos-trabajo-economia-regional-urbana/fecundidad-colombia-evolucion-reciente); [IDEAS](https://ideas.repec.org/p/bdr/region/338.html). **Calidad: Descriptiva** (correlatos municipales).

**Por qué la explicación es pobre:** todas las causas propuestas son lentas y monótonas, mientras el fenómeno es un salto concentrado en 2023-2024 que luego se frena en 2025-2026. Nadie ha descompuesto la caída por edad, orden de nacimiento, nacionalidad de la madre y región, como sí hicieron Cabella et al. para Uruguay.

### Inferences
- *INFERENCIA, aritmética simple:* el aumento de IVE entre 2022 y 2024 (+~13 mil) es mucho menor que la caída de nacimientos de 2024 (~62 mil, implícita en 453.901 con −12%). La C-055 no puede explicar más que una fracción, salvo que el registro de IVE esté muy incompleto.
- *INFERENCIA, hipótesis candidatas y cómo discriminarlas:*
  1. **Reversión del "mini-baby boom" migrante.** Sacar los nacimientos de madres venezolanas (variable nacionalidad de la madre en EEVV, microdatos públicos) y ver si la caída de 2023-2024 es mayor en municipios con más stock migrante (Migración Colombia, PEP/PPT) y salida post-2022. Un shift-share por municipio de destino es viable.
  2. **Emigración de colombianos jóvenes en 2022-2023** (salidas netas ~450-550 mil, según BanRep). Si emigran mujeres de 20-34, los nacimientos caen, pero la TGF-DANE se exagera porque el denominador no las descuenta (ver Puzzle 2). Para discriminar: comparar la caída por departamento con la emigración por departamento.
  3. **Acceso a anticoncepción de larga duración / IVE post-C-055.** Usar el despliegue escalonado de prestadores (Oriéntame, Profamilia) y la contratación de EPS por municipio en un event-study. Los datos son RIPS/SISPRO (restringidos) y SIVIGILA.
  4. **Choque de inflación y tasas de interés 2022-2023** (tempo/postergación). Si es tempo, la cohorte "recupera": el rebote de +1,5% en 2026 es consistente con esto. Para discriminar: descomponer por orden de nacimiento y edad (EEVV tiene paridad). Una caída concentrada en primeros nacimientos a edades de 20-29 indica postergación.
  5. **Artefacto de cobertura del registro** (preliminar frente a definitivo). Comparar la serie de partos institucionales (RIPS) con nacimientos EEVV.
- *Comparación útil:* Colombia, Uruguay y Chile tuvieron caídas casi simultáneas tras 2015. Un diseño comparativo con datos armonizados (CELADE) permitiría separar factores comunes regionales (redes sociales, LARC, cambio de normas) de idiosincrásicos (migración venezolana).
- **Grado de rompecabezas: ALTO.** Es un salto anual sin choque identificado, más rápido que cualquier proyección oficial, y se frena solo.
- **Promesa de investigación: ALTA.** Los microdatos EEVV son públicos y tienen nacionalidad, edad, paridad, municipio y educación de la madre. Existen varias fuentes de variación municipal.

### Gaps
- No pude abrir el PDF del DANE (bloqueado) para extraer la TGF por edad y orden ni los nacimientos por nacionalidad de la madre en 2019-2025. El DANE tiene un informe de 2021 sobre la fecundidad de mujeres venezolanas, pero no pude leerlo — [DANE 2021 (solo buscador)](https://www.dane.gov.co/files/investigaciones/poblacion/informes-estadisticas-sociodemograficas/2021-12-22-caracterizacion-fecundidad-en-mujeres-procedentes-de-venezuela.pdf).
- No encontré la TGF de la **ENDS 2025**, que sería un estimador independiente del registro. Existen publicaciones del MinSalud (["cambios demográficos ENDS 2025"](https://www.minsalud.gov.co/sites/rid/Lists/BibliotecaDigital/RIDE/VS/ED/GCFI/cambios-demograficos-ends-2025.pdf), [anticoncepción y preferencias](https://www.minsalud.gov.co/sites/rid/Lists/BibliotecaDigital/RIDE/VS/ED/GCFI/publicacion-anticoncepcion-preferencias-fecundidad-ends-2025.pdf)) y un comentario académico ([Rev. Colomb. Obstet. Ginecol., UdeA](https://revistas.udea.edu.co/index.php/ginecologia_y_obstetricia/article/view/366892)), pero no pude ver las cifras. **Es la prioridad número 1 de verificación.**
- No encontré la proyección DANE 2020-2070 de nacimientos para 2024. Solo encontré la fecha de 2052 para el decrecimiento.

---

## Puzzle 2. ¿Cuál es la verdadera fecundidad y la verdadera población? (TGF DANE frente a ONU, y el censo 2018)

### Takeaway
Para casi el mismo año, el DANE publica una TGF de 1,2 (2023) y el Banco Mundial/ONU de 1,645 (2023). Es una diferencia de ~0,45 hijos, enorme y casi no discutida. Hay TGF municipales implausibles (Tarso, Antioquia: 0,3). El origen probable es el **denominador**: las proyecciones post-censo 2018 de mujeres de 15-49 años, construidas sobre un censo con 8,5% de omisión y una migración neta muy incierta. El "faltante" de ~4-6 millones del censo 2018 frente a las proyecciones de 2005 tiene explicaciones oficiales (proyecciones viejas, emigración no contada) que nunca se han contrastado con una reconciliación demográfica pública.

### Cited Findings
**HECHOS**
- La TGF de Colombia en 2023 fue 1,645 según el Banco Mundial (vía FRED, SP.DYN.TFRT.IN) y 1,663 en 2022. La de Chile en 2023 fue 1,167 — [FRED SPDYNTFRTINCOL (solo buscador)](https://fred.stlouisfed.org/series/SPDYNTFRTINCOL); [FRED Chile](https://fred.stlouisfed.org/series/SPDYNTFRTINCHL). El DANE da 1,2 (2023) y 1,4 (2022) — [DANE vía La FM](https://www.lafm.com.co/sociedad/nacimientos-defunciones-colombia-2026-411916); [La República](https://www.larepublica.co/economia/colombia-registro-caida-de-14-4-en-los-nacimientos-la-mas-alta-de-la-ultima-decada-4025516). Una nota basada en la ONU dio 1,7 para Colombia en 2023 — [Deseret News (solo buscador)](https://www.deseret.com/family/2025/07/18/world-population-birth-rate-shrinking-south-america-us-japan-korea).
- Una columna de Portafolio señala que "llaman la atención" las diferencias entre las proyecciones DANE 2020-2070 y el WPP 2024 de la ONU, sin cuantificarlas — [Portafolio, "¿Cayó la población?" (solo buscador)](https://www.portafolio.co/opinion/analisis/cayo-la-poblacion-opinion-611753).
- TGF departamentales 2024-2025 (DANE): Caldas 0,7 (la más baja); Vaupés 2,0; La Guajira 1,9; Guainía 1,6; Guaviare 1,5 — [El Espectador / buscador](https://www.elespectador.com/salud/nacimientos-y-decesos-en-colombia-tasas-de-fecundidad-siguen-en-descenso-segun-el-dane/); [DANE IIsem2025pr vía buscador](https://www.dane.gov.co/files/operaciones/EEVV/2026/20-mar-2026/cp-EEVV-Defunciones-IIsem2025pr.pdf). Antioquia: 0,9 en 2024. Por municipio: Tarso 0,3 y Murindó 2,1 — [El Colombiano (solo buscador)](https://www.elcolombiano.com/negocios/antioquia-nacimientos-fecundidad-cae-debajo-un-hijo-por-mujer-NI29474191).
- **Censo 2018:** se censaron 44,16 millones de personas efectivas. La población ajustada es 48.258.494, con una omisión de 4.094.077 (8,5%): 6,4% en cabeceras y 15% en rural disperso. La omisión fue de 4,2% en 2005 y ~8% en 1993 — [El Espectador](https://www.elespectador.com/economia/cali-y-villavicencio-donde-mas-personas-quedaron-sin-contar-en-el-censo-article-886507/); [La República](https://www.larepublica.co/economia/tasa-de-poblacion-omitida-en-el-censo-de-2018-fue-de-8-5-de-acuerdo-con-el-dane-2922041) (ambas solo buscador). La omisión fue mayor en Cali, Villavicencio y Popayán; el Valle tuvo ~11% — [La República](https://larepublica.co/economia/el-dane-cuadro-el-censo-con-las-cifras-de-omitidos-de-cali-villavicencio-y-popayan-2922211).
- La proyección basada en el censo 2005 esperaba ~50 millones. La prensa tituló "solo somos 45,5 millones, 9% menos" — [El Universal, nov-2018](https://www.eluniversal.com.co/colombia/2018/11/07/solo-somos-455-millones-de-colombianos-9-menos-de-las-estimaciones/). El DANE dijo que el error medio de las proyecciones censales en América Latina es de 5,7% y el de Colombia fue de 9% — vía [El País Cali](https://www.elpais.com.co/economia/que-fallo-en-el-polemico-censo-del-2018-responde-el-director-del-dane.html) (solo buscador).
- El DANE "reconoce por qué borró 1,4 millones de afros del censo de 2018" (problema de autorreconocimiento étnico) — [Cambio, may-2024 (solo buscador)](https://cambiocolombia.com/pais/articulo/2024/5/dane-reconoce-por-que-borro-14-millones-de-afros-del-censo-de-2018).

**PRENSA**
- [La República, "las deficiencias que se encontraron en el operativo del censo 2018"](https://www.larepublica.co/economia/las-deficiencias-que-se-encontraron-en-el-operativo-del-censo-de-poblacion-2018-2882389); [La Silla Vacía (solo buscador; URL de redirección)](https://www.lasillavacia.com/?p=343819); [Las2orillas, columna que acusa al DANE de mentir sobre la actualización de las proyecciones con Eduardo Arriaga (postura editorial)](https://www.las2orillas.co/?p=618210).

**EXPLICACIONES EXISTENTES**
- (a) "Las proyecciones de 2005 no se corrigieron; el censo se hizo con tres años de retraso" (DANE, Juan Daniel Oviedo, 2018-2019) — [El Espectador](https://www.elespectador.com/economia/en-colombia-somos-mas-de-482-millones-de-personas-informo-el-dane-articulo-869325); [El País](https://www.elpais.com.co/economia/que-fallo-en-el-polemico-censo-del-2018-responde-el-director-del-dane.html). **Calidad: Especulación institucional.** No se publicó la descomposición por componente (natalidad, mortalidad, emigración).
- (b) "Emigración de finales de los 90 no incorporada; población venezolana subestimada" — mismas fuentes y [Las2orillas](https://www.las2orillas.co/?p=618210). **Calidad: Especulación.**
- (c) "Fallas operativas: demoras, personal insuficiente, viviendas ocupadas sin respuesta" — [La República](https://www.larepublica.co/economia/las-deficiencias-que-se-encontraron-en-el-operativo-del-censo-de-poblacion-2018-2882389). Un comité de expertos dijo que una omisión de 8-12% es "normal" y que "no invalida" el censo. **Calidad: Descriptiva.**
- (d) "El error estuvo en el censo 2005, no en el de 2018" (Fernando Posada, citado en prensa). **Calidad: Especulación.**
- Sobre la brecha DANE frente a ONU en la TGF: **Ninguna** explicación encontrada.

**Por qué la explicación es pobre:** no existe una reconciliación pública por cohortes que diga *qué edades y lugares faltan* en 2018. Por ejemplo: ¿faltan hombres jóvenes (emigración) o niños (omisión)? Tampoco existe un análisis de sensibilidad de la TGF-DANE al denominador. Con TGF municipales de 0,3, el denominador está mal en al menos algunos lugares.

### Inferences
- *INFERENCIA:* si la TGF-DANE usa como denominador mujeres de 15-49 proyectadas que incluyen un stock migrante sobreestimado o la omisión censal imputada, y no descuenta la emigración post-2022, entonces **parte del "colapso a 1,0" es un artefacto del denominador**. La brecha con la ONU (~0,45 hijos) es del orden de magnitud que eso podría producir. Esto es una hipótesis, no un hecho.
- *Cómo discriminar:*
  1. Calcular la TGF con denominadores alternativos: SISBEN IV, afiliados BDUA por edad y sexo, matrícula SIMAT como control de cohortes infantiles, y la ENDS 2025 (TGF por historias de nacimientos, independiente del denominador). Si la ENDS 2025 da ~1,4-1,6, el puzzle 1 cambia de naturaleza.
  2. Reconciliación de cohortes: nacimientos EEVV 1985-2018 menos defunciones, comparado con la población censada por edad y municipio. El "faltante" por edad y sexo revela emigración frente a omisión.
  3. Variación municipal: correlacionar la omisión censal municipal (publicada por el DANE) con anomalías de TGF municipal 2019-2025.
- **Grado de rompecabezas: ALTO.** Es una discrepancia entre fuentes oficiales y no está discutida.
- **Promesa: ALTA.** Es un paper "de medición" muy citable, base para todo lo demás. Es factible con datos públicos más acceso administrativo.

### Gaps
- No pude abrir el WPP 2024 ni la ficha de proyecciones DANE 2020-2070 para ver supuestos de migración y fecundidad. Ficha listada: [DANE Ficha Estimaciones Proyecciones 85-2020 (solo buscador)](https://www.dane.gov.co/files/investigaciones/fichas/Ficha_Estimaciones_Proyecciones_85_2020.pdf).
- Busqué un paper académico revisado por pares sobre la cobertura del censo 2018. Solo apareció un artículo en Redalyc/Apuntes del CENES (2019), sin acceso al contenido — [Apuntes del CENES (DOAJ)](https://doaj.org/article/5e9124ceb59d41cbbc6e2f7f84121a4d).
- No verifiqué la cifra de afiliados BDUA frente a la población (uso frecuente como contraste). No la uso como hecho.

---

## Puzzle 3. Paradoja de la fecundidad adolescente: sube entre 1990 y 2005 mientras cae la TGF, y luego se desploma a la mitad entre 2015 y 2024

### Takeaway
Según las ENDS, la tasa de 15-19 años subió de 70 por mil (1990) a 89 (1995) y 90 (2005), mientras la TGF caía. La subida fue urbana. Las explicaciones son "próximas": inicio sexual más temprano y adelanto de la primera unión, sin causa estructural. Luego, entre 2015 y 2024, la tasa cayó más de la mitad (66,1 → ~30-32), una de las caídas más rápidas documentadas. La evidencia causal es fragmentaria: jornada completa (−25%, CEDE 2017). La subida no tiene buena explicación y la caída tampoco.

### Cited Findings
**HECHOS**
- Tasa de fecundidad de 15-19 años: 70 por mil (1990), 89 (1995), 90 (2005). El aumento fue urbano; la rural cayó levemente — [Center for Reproductive Rights 2006, con datos ENDS (solo buscador)](https://reproductiverights.org/wp-content/uploads/2020/12/sl_colombia_eng2006.pdf).
- Adolescentes madres o embarazadas: 12,8% (1990) → 20,5% (2005). La proporción de madres solteras entre ellas pasó de 21% a 44% — [Flórez, presentación CEPAL (solo buscador)](https://www.cepal.org/sites/default/files/events/files/florez_ppt.pdf); [Flórez y Soto, Notas de Población CEPAL (solo buscador)](https://repositorio.cepal.org/bitstream/handle/11362/12820/np83041074_es.pdf).
- Inicio sexual antes de los 15 años: 4,3% (1986) → 13,7% (2005). Es reporte secundario de cifras ENDS — [Colombia Reports](https://colombiareports.com/?p=7500).
- Urdinola y Ospino describen un aumento "inesperado" durante 24 años, a contracorriente de la TGF — [*Demographic Research* 32(55), 2015](https://ideas.repec.org/a/dem/demres/v32y2015i55.html).
- 2001-2011: los nacimientos de madres de 10-14 años subieron 2,6% anual y los de 15-19, 0,8% anual. Los de 20-34 bajaron 0,2% anual — [Jaramillo-Mejía y Chernichovsky, *Cad. Saúde Pública* 35(2), 2019](https://www.scielo.br/j/csp/a/6HcSZ4LM6MJd3rxMjpmKDjK/?lang=en).
- La ENDS 2015 mostró "por primera vez un descenso en 20 años" — [El Tiempo (solo buscador)](https://www.eltiempo.com/salud/encuesta-nacional-de-demografia-y-salud-38571).
- **Colapso 2015-2024 (DANE):** la tasa de 15-19 pasó de 66,1 a 30,3 según Bloomberg Línea — [Bloomberg Línea](https://www.bloomberglinea.com/latinoamerica/colombia/nacimientos-en-colombia-cayeron-14-en-2024-y-33-en-ultima-decada/). El comunicado DANE 2024pr dice que cayó 51,1%, es decir, 33,8 nacimientos menos por mil, lo que implica ~32,3. **Discrepancia 30,3 frente a ~32,3**, probablemente preliminar frente a definitivo — [Portafolio citando DANE](https://www.portafolio.co/economia/regiones/numeros-historicos-la-principal-razon-de-la-caida-de-la-fecundidad-en-colombia-626640). La tasa más alta en 2024 fue La Guajira, con 65,9.
- En 2024 hubo 63.527 nacimientos de madres de 15-19 y 3.159 de 10-14 (MinSalud con DANE preliminar). Alrededor del 20% de los nacimientos siguen siendo de madres de 10-19 años — [El Universal (solo buscador)](https://www.eluniversal.com.co/colombia/2025/09/12/mas-de-63000-bebes-nacieron-de-madres-entre-15-y-19-anos-en-2025/); [BanRep WP 338](https://banrep.gov.co/en/publications-research/working-papers-regional-urban-economics/fertility-colombia-recent-trends).
- Comparación internacional (CEPAL/LAC): la "paradoja de la fecundidad adolescente" latinoamericana (subida en los 90 con TGF a la baja) está documentada por Rodríguez Vignoli y otros. No obtuve una cita verificada en esta búsqueda; ver Gaps.

**PRENSA:** la caída se presenta como logro de política: ICBF dice que el embarazo de 15-19 cayó 27% entre 2021 y 2023 gracias a programas escolares — [ICBF](https://www.icbf.gov.co/node/279783). La Silla Vacía atribuye una caída de ~6% (2015-2018) en municipios del Conpes 147 al paquete de prevención — [La Silla Vacía (solo buscador)](https://www.lasillavacia.com/?p=32119). Portafolio ("números históricos") la presenta como el componente principal de la caída de la natalidad.

**EXPLICACIONES EXISTENTES**
- *Subida 1990-2005:*
  - Inicio sexual más temprano sin uso proporcional de anticoncepción; uniones tempranas y madres solteras (Flórez y Soto, CEPAL). **Calidad: Descriptiva** (determinantes próximos).
  - Adelanto de la edad al primer nacimiento junto con postergación del segundo; la edad al primer hijo dejó de caer hacia 2010 (Batyra, *Demographic Research* 35(46), 2016) — [link](https://www.demographic-research.org/articles/volume/35/46). El adelanto se concentra en las de baja educación y la postergación en las de alta educación, en la región andina (Batyra, *PRPR* 2019). **Calidad: Descriptiva.**
- *Caída 2015-2024:*
  - Jornada escolar completa: −0,6 pp de fecundidad adolescente (~−25%), solo urbana. Panel 2006-2009 con efectos fijos de colegio y estudiante (Borrero, Documento CEDE 2017) — [RePEc](https://econpapers.repec.org/RePEc:col:000089:015817). **Calidad: Parcial causal** (periodo anterior al colapso; la expansión de la Jornada Única post-2015 no se ha evaluado para fecundidad).
  - Implante subdérmico / LARC: uso de apenas 5,4% (mujeres unidas) y 8,1% (no unidas sexualmente activas) en la ENDS 2015 — [Gallego Vélez, Rev. UdeA (solo buscador)](https://revistas.udea.edu.co/index.php/ginecologia_y_obstetricia/article/download/346849/20808509/253876). Solo hay estudios clínicos observacionales. **Calidad: Ninguna** (como explicación agregada).
  - Correlatos municipales: informalidad y NBI (+), desarrollo (−) (BanRep WP 338, 2025). **Calidad: Descriptiva.**
  - Conpes 147 de 2012 (municipios priorizados). **Calidad: Especulación o descriptiva.**
- Explicado y descartado como subtema: las consecuencias de largo plazo de la maternidad adolescente (Urdinola y Ospino, 2015) tratan efectos, no causas.

**Por qué es pobre:** para la subida solo hay determinantes próximos ("más sexo temprano"), sin el porqué estructural: urbanización, conflicto y desplazamiento, normas. La caída de 50% en 9 años no tiene ninguna descomposición ni evaluación nacional. El único causal (jornada completa) es de un periodo previo y de magnitud insuficiente.

### Inferences
- *INFERENCIA, hipótesis para la subida 1990-2005:*
  1. El desplazamiento forzado y el conflicto (picos de 1998-2005) concentraron adolescentes en periferias urbanas. Esto es consistente con que la subida fue **urbana**. Variación: intensidad municipal de desplazamiento recibido (RUV) frente a fecundidad adolescente por municipio (EEVV desde 1998).
  2. Expansión de la secundaria sin educación sexual: escolarización con más interacción entre pares.
  3. Cambio en el registro (mayor cobertura de nacimientos adolescentes). Para chequearlo, comparar ENDS (historias) con EEVV.
- *INFERENCIA, hipótesis para la caída 2015-2024:*
  1. LARC gratuitos en el plan de beneficios para adolescentes y servicios amigables. Variación: rollout por EPS y municipio (RIPS).
  2. Jornada Única (expansión escalonada por colegio desde 2015). Variación: event-study colegio-cohorte con SIMAT más EEVV (vínculo restringido, por documento).
  3. Smartphones y redes: menos interacción presencial. Es un factor común internacional; contrastar con países vecinos.
  4. Acuerdo de Paz 2016 y reducción del conflicto en municipios PDET: diff-in-diff PDET frente a no-PDET.
  5. Efecto composición de madres venezolanas (adolescentes migrantes con alta fecundidad entre 2018 y 2021).
- **Grado de rompecabezas: ALTO.** Hay dos inversiones de signo en 30 años y la caída es de velocidad excepcional.
- **Promesa: ALTA.** Los EEVV municipales anuales desde 1998 tienen edad de la madre y hay múltiples políticas escalonadas. Es un tema ideal para micro-desarrollo aplicada.

### Gaps
- No obtuve la serie anual EEVV de la tasa de 15-19 entre 1998 y 2024 para fechar el pico (¿2008? ¿2012?).
- No verifiqué cifras CEPAL de la "paradoja" para comparar con Ecuador, Perú y Venezuela. La [tesis de Venezuela](https://saber.ucv.ve/ojs/index.php/rev_avn/article/view/28776) sugiere un patrón similar, pero no la leí.

---

## Puzzle 4. Inversión geográfica: Antioquia y el Eje Cafetero, de alta fecundidad a menos de 1 hijo por mujer

### Takeaway
Caldas (0,7), Antioquia (0,9 en 2024, desde 1,9 en 2008) y municipios como Tarso (0,3) tienen hoy fecundidades inferiores a las de Corea del Sur. Vaupés (2,0) y La Guajira (1,9) siguen cerca del reemplazo. Las explicaciones (envejecimiento, emigración, educación) son genéricas y en parte tautológicas. La variación intra-departamental es extrema: en Antioquia, Tarso tiene 0,3 y Murindó 2,1.

### Cited Findings
- Caldas tiene una TGF de 0,7 (2024 y 2025), la más baja del país, frente a Vaupés con 2,0 — [DANE vía buscador](https://www.dane.gov.co/files/operaciones/EEVV/2026/20-mar-2026/cp-EEVV-Defunciones-IIsem2025pr.pdf); [El Espectador](https://www.elespectador.com/salud/nacimientos-y-decesos-en-colombia-tasas-de-fecundidad-siguen-en-descenso-segun-el-dane/).
- Antioquia pasó de 1,9 (2008) a 0,9 (2024), −51,5% en 17 años. Tarso tiene 0,3; Murindó (Urabá) 2,1 y es el único municipio por encima del reemplazo — [El Colombiano, 26-sep-2025 (solo buscador)](https://www.elcolombiano.com/negocios/antioquia-nacimientos-fecundidad-cae-debajo-un-hijo-por-mujer-NI29474191); [El Colombiano, may-2026](https://www.elcolombiano.com/antioquia/caida-nacimientos-antioquia-colombia-causas-impactos-KC36079289).
- Caldas: los nacimientos cayeron 19,3% entre 2015 y 2021, frente a 7,8% nacional. Tasa bruta de natalidad en 2021: 8 por mil frente a 12 nacional — [Caldata, Gobernación de Caldas, Boletín 21 (solo buscador)](https://caldata.caldas.gov.co/wp-content/uploads/2025/04/Boletin-21-Natalidad-y-fecundidad-en-Caldas.pdf).
- Un estudio académico sobre el Eje Cafetero (1998-2018) halla niveles "similares a sociedades avanzadas" — [EconBiz (solo buscador)](https://econbiz.de/Record/an%C3%A1lisis-demogr%C3%A1fico-fecundidad-departamentos-regi%C3%B3n-cafetero-colombia-1998-2018-demographic-analysis-fertility-departments-colombian-coffee-region/10012828128). Una tesis doctoral (UAB) con preguntas retrospectivas de censos 1973-2018 halla que las mujeres emigrantes son las de menor fecundidad — [UAB DDD (solo buscador)](https://ddd.uab.cat/record/244252).
- Federación de Cafeteros: la escasez de mano de obra cafetera (1993-2005) se explica por emigración rural (Leibovich y Botello) — [FNC (solo buscador)](https://federaciondecafeteros.org/static/files/An%C3%A1lisis%20de%20los%20cambios%20demogr%C3%A1ficos%20en%20los%20municipios%20cafeteros%20y%20su%20relaci%C3%B3n%20con%20los%20cambios%20en%20la%20caficultura%20colombiana%20(1993%202005).pdf).
- Prensa: [Pulzo, "Eje Cafetero, región con más adultos mayores"](https://www.pulzo.com/nacion/eje-cafetero-region-pais-con-mas-adultos-mayores-colombia-PP1301198A). Ahí una investigadora atribuye la baja natalidad a envejecimiento, salida de jóvenes y educación y trabajo femenino. **Calidad: Especulación.**
- Explicación de la Gobernación de Caldas: "reducción de la fecundidad, estructura poblacional, migración, condiciones socioeconómicas" (boletín citado). **Calidad: Descriptiva o tautológica.**
- Uniandes, según Portafolio: Bogotá y Santander bajas; Amazonas, Guainía y Vaupés altas — [Portafolio](https://www.portafolio.co/economia/regiones/la-economia-del-pais-se-podria-afectar-por-la-caida-de-los-nacimientos-en-colombia-623134).

**Por qué es pobre:** "envejecimiento" no explica una TGF baja, porque la TGF ya controla por estructura de edad. "Emigración" solo la explica si el denominador está mal o si emigran selectivamente las mujeres con intención de tener hijos. Nadie ha separado artefacto, selección migratoria y comportamiento.

### Inferences
- *INFERENCIA, contexto histórico no verificado en esta búsqueda:* Antioquia y la zona de colonización antioqueña son, en la historiografía demográfica, ejemplo de familias numerosas y catolicismo fuerte en el siglo XX. Si se confirma, el puzzle es una **inversión**: la región más pronatalista pasa a la más baja. Esto contradice la intuición de "persistencia cultural" (estilo Alesina-Giuliano) y merece verificación con censos 1964/1973 (IPUMS).
- *Hipótesis:*
  1. **Artefacto del denominador** (Puzzle 2): TGF municipales de 0,3 son casi imposibles sin error de población. Para comprobarlo, recalcular con SISBEN o BDUA.
  2. **Emigración internacional selectiva post-1999** (crisis cafetera y terremoto del Eje en 1999 → España/EE. UU.). Las remesas reducen la necesidad de hijos como seguro, y las mujeres emigrantes o retornadas tienen baja fecundidad. Variación: intensidad de emigración municipal (censo 2005, pregunta por miembros en el exterior) con un shift-share del precio del café.
  3. **Choque a la economía cafetera** (precio internacional, roya 2008-2012) como Bartik municipal según la intensidad cafetera (Censo Cafetero/SICA).
  4. **Normas de género y educación femenina temprana en la región** (alta escolaridad femenina relativa).
- **Grado de rompecabezas: MEDIO-ALTO.** La magnitud es extrema y la inversión probable; parte puede ser artefacto.
- **Promesa: ALTA.** La variación municipal es muy rica y hay instrumentos naturales (precio del café, terremoto de 1999, ola migratoria a España 1999-2008 y retorno post-2008).

### Gaps
- No verifiqué las TGF departamentales históricas (1985-2005) para documentar formalmente la inversión. Fuente candidata: [DANE, "Evolución de la fecundidad en Colombia y departamentos 2005-2018" (solo buscador)](https://www.dane.gov.co/files/investigaciones/poblacion/informes-estadisticas-sociodemograficas/2021-12-29-evolucion-fecundidad-colombia-departamentos-2005-2018.pdf).
- No obtuve cifras de Quindío y Risaralda por separado.

---

## Puzzle 5. El boom de la unión libre: ¿transición "de la desventaja" o "segunda transición demográfica"?

### Takeaway
Entre las mujeres de 25-29 años, la cohabitación (sobre el total de unidas) pasó de 20% (1973) a 66% (2005), y la ENDS 2010 da ~73,6%. Colombia está entre los máximos de la región. El grupo de Esteve y Lesthaeghe concluye a la vez que a nivel latinoamericano hay un "catching up" de las mujeres educadas (lectura SDT) y que en Colombia el perfil social y espacial de quienes cohabitan **no ha cambiado** en cuatro décadas: más alta en baja educación, Caribe, Pacífico, Orinoquía y Amazonía. No hallaron correlación clara con factores económicos (la inflación sería solo "catalizador"). Falta un análisis con el censo 2018.

### Cited Findings
- Mujeres de 25-29 en cohabitación: 20% (1973) → 66% (2005); ~73,6% según la ENDS 2010. La cohabitación es mayor en baja educación, población étnica y regiones Caribe, Pacífico, Orinoquía y Amazonía. El "perfil social y distribución espacial... ha permanecido sin cambios" — [Esteve, Saavedra, López-Colás, López-Gay y Lesthaeghe, cap. Colombia/Andes en *Cohabitation and Marriage in the Americas* (Springer 2016) (solo buscador)](https://ddd.uab.cat/record/167461?ln=en); [Springer](https://link.springer.com/10.1007/978-3-319-31442-6_7).
- Nivel latinoamericano: aumento en regiones con y sin cohabitación tradicional; "striking catching up" de las mejor educadas. Sin correlación clara con factores económicos; la inflación como posible catalizador — [Esteve, Lesthaeghe y López-Gay, *PDR* 38(1), 2012 (solo buscador)](https://urbandemographics.blogspot.com/2013/06/latin-american-cohabitation-boom-1970.html?m=0). En México, la expansión reciente se debe a los estratos educados.
- Unión libre entre mujeres de un grupo de edad: 49,2% (1990) → 65,6% (2005), citado en columna — [Vanguardia, Laura Cuesta, 2015 (solo buscador)](https://www.vanguardia.com/opinion/columnistas/laura-cuesta/2015/02/23/cual-familia-tradicional/).
- Censo 2018: 9% de separados o divorciados. La ruptura de uniones libres explica 77% de ese estado y la de matrimonios 17% — [artículo en Dialnet sobre separación conyugal (solo buscador)](https://dialnet.unirioja.es/descarga/articulo/7900883.pdf). Tesis doctoral relacionada: "La separación conyugal en Colombia, 1951-2015" — [TDX](https://www.tdx.cat/handle/10803/666674).
- Ruiz-Vallejo (ENDS 2015): 48% de las primeras uniones se disuelven a los 20 años. El riesgo es mayor en cohortes jóvenes, unión libre, residencia urbana, **alta educación** y uniones tempranas — [Revista CS, 2021 (DOAJ)](https://doaj.org/article/92aab39f799449d8b94ad2d4dd83ca5e).
- Mujeres en unión libre aportan 57,5% de la fecundidad global — [Rev. Latinoamericana de Estudios de Familia, U. Caldas (solo buscador)](https://revistasojs.ucaldas.edu.co/index.php/revlatinofamilia/article/download/4065/3772/).
- Prensa: [Semana, "¿Colombianos tienen fobia al matrimonio?"](https://www.semana.com/pais/articulo/colombianos-tienen-fobia-matrimonio/180115); [Portafolio, "colombianos casan Latinoamérica"](https://www.portafolio.co/economia/finanzas/colombianos-casan-latinoamerica-71350); [La Silla Vacía](https://www.lasillavacia.com/?p=12707): el aumento de la unión libre frente al matrimonio fue proporcionalmente mayor en hogares pobres.
- **Calidad de las explicaciones:** SDT o ideacional (Lesthaeghe): **Descriptiva**, y contradicha en parte por el perfil colombiano. Economía e inflación: **Descriptiva negativa** (sin correlación). Legados histórico-étnicos: **Descriptiva**.

**Por qué es pobre:** las explicaciones son ecológicas y de corte transversal (censos). No hay ninguna con variación exógena. El hallazgo de "perfil sin cambios" y el de "catching up de las educadas" no se han reconciliado para Colombia con el censo 2018.

### Inferences
- *INFERENCIA:* ambos hallazgos pueden ser ciertos a la vez. El nivel sube en todos los grupos (los educados crecen más en términos relativos), pero el ranking se conserva. Para separarlo, usar IPUMS (censos 1973/1985/1993/2005/2018) por cohorte × educación × departamento.
- *Variación para causalidad (marco legal; las fechas son conocimiento general, no verificado en esta búsqueda):*
  1. Ley 54 de 1990, que reconoce derechos patrimoniales a la "unión marital de hecho".
  2. Constitución de 1991 y divorcio civil para matrimonio católico (Ley 25 de 1992).
  3. Jurisprudencia de la Corte sobre pensión de sobreviviente para compañeros permanentes.
  Son reformas nacionales: se identifican por exposición diferencial. Por ejemplo, mujeres con propiedad o afiliación pensional del compañero frente a sin, o cohortes que entran a unión antes y después.
- *Hipótesis económica:* el costo de la boda o los trámites y la incertidumbre de ingresos (informalidad) implican más unión libre. Variación: choques locales de ingreso (Bartik por precios de commodities o café) sobre el flujo de matrimonios registrados (EEVV de matrimonios, si se accede a registros notariales; restringido).
- **Grado de rompecabezas: MEDIO.** El patrón está bien descrito, pero el "porqué" es débil.
- **Promesa: MEDIA.** Hay datos censales abiertos (IPUMS) y una literatura demográfica fuerte; la identificación causal es difícil.

### Gaps
- No encontré la proporción de unión libre frente a matrimonio del censo 2018 ni de la ENDS 2025, ni su gradiente educativo. Existe el capítulo de nupcialidad de la ENDS 2025 ([MinSalud, solo buscador](https://minsalud.gov.co/sites/rid/Lists/BibliotecaDigital/RIDE/VS/ED/GCFI/publicacion-nupcialidad-ends-2025.pdf)), pero no extraje cifras.
- No obtuve las tasas brutas de nupcialidad (matrimonios registrados por 1.000) 1985-2025.

---

## Puzzle 6. Jefatura femenina casi duplicada y auge de hogares unipersonales

### Takeaway
La jefatura femenina pasó de 24% (censo 1993) a 30% (2005), 40,7% (censo 2018) y 46,5% (ECV 2024). Los hogares unipersonales pasaron de 11,1% (2005) a 18,1% (2018), 19,8% (2024) y 20,2% (2025). El tamaño medio del hogar cayó de 4,0 a 3,1 personas (2005-2018). El DANE lo presentó como "empoderamiento", pero la pobreza es mayor en los hogares de jefa. No hay ninguna descomposición publicada que separe causas demográficas (viudez, separación, migración masculina) de cambios en **quién se declara jefe** cuando hay pareja presente.

### Cited Findings
- Jefatura femenina: 24% (1993) → 30% / 29,9% (2005) → 40,7% (2018) — [DANE, presentación "jefes de hogar" (solo buscador)](https://www.dane.gov.co/files/censos/presentaciones/jefes_hogar.pdf); [El Espectador, "Mujeres en el censo: ¿empoderamiento femenino?"](https://www.elespectador.com/economia/mujeres-en-el-censo-empoderamiento-femenino-article-870064/). En 2018 la pobreza era de 21,7% en hogares de jefa frente a 18,5% en hogares de jefe (mismo artículo).
- ECV 2024: 46,5% de hogares con jefa, unos 8,5 millones — [DANE, boletín ECV 2024 (solo buscador)](https://www.dane.gov.co/files/operaciones/ECV/bol-ECV-2024.pdf); [Forbes: "casi la mitad con jefatura femenina"](https://forbes.co/economia-y-finanzas/colombia-llega-a-533-millones-de-habitantes-con-hogares-mas-pequenos-y-casi-la-mitad-con-jefatura-femenina).
- Hogares unipersonales: 11,1% (2005) → 18,1% (2018) — [El Tiempo](https://www.eltiempo.com/economia/sectores/que-implica-que-los-hogares-colombianos-sean-mas-pequenos-analisis-censo-2018-311776); [Semana](https://www.semana.com/economia/articulo/los-resultados-mas-curiosos-del-censo-nacional-de-poblacion-y-vivienda/585021). ECV: 19,8% (2024), 20,2% (2025) — [vivienda.com.co](https://vivienda.com.co/?p=3035). BBVA Research: desde 2002 son más representativos en ingresos altos — [BBVA (solo buscador)](https://www.bbvaresearch.com/wp-content/uploads/2019/04/SituacionConsumo.pdf). Vivir solo en la vejez es cada vez más común — [Portafolio](https://www.portafolio.co/economia/vivir-solo-en-la-vejez-cada-vez-mas-comun-en-colombia-531903).
- Asobancaria: los hogares con jefatura femenina crecieron 71,3% entre 1997 y 2022 — [Asobancaria (solo buscador)](https://www.asobancaria.com/wp-content/uploads/2024/04/1411-BE.pdf).
- **Explicaciones:** DANE ("empoderamiento"): **Especulación.** El Espectador (crítica por pobreza): **Descriptiva.** No encontré ningún análisis académico causal.

**Por qué es pobre:** la jefatura es autodeclarada. Un salto de 10 pp entre 2005 y 2018 podría ser en parte normativo o de medición (mujeres con cónyuge presente que se declaran jefas), en parte demográfico (separación de uniones libres, viudez) y en parte migratorio (emigración masculina, conflicto). Nadie lo ha separado.

### Inferences
- *INFERENCIA, descomposición inmediata con microdatos (IPUMS 1993/2005/2018; GEIH/ECV anuales):* ¿qué fracción de jefas tiene cónyuge en el hogar? Si sube mucho, el cambio es de **norma de reporte**: un indicador de poder de negociación intrahogar interesante en sí mismo. Si no, es estructura (monoparentalidad).
- *Hipótesis causales:*
  1. Conflicto y viudez masculina: diff-in-diff por intensidad de homicidios masculinos 1990-2005 por municipio.
  2. Inestabilidad de la unión libre (77% de las separaciones; ver Puzzle 5).
  3. Subsidios focalizados en madres (Familias en Acción paga a la madre) que incentivan declarar jefatura femenina. Variación: entrada escalonada del programa por municipio (2001-2007) y focalización SISBEN.
- **Grado de rompecabezas: MEDIO.** La magnitud es grande y la medición ambigua.
- **Promesa: MEDIA-ALTA.** El tema conecta con poder de negociación intrahogar, programas de transferencias y pobreza; los microdatos son abiertos.

### Gaps
- No pude verificar la definición operativa de "jefe" en cada censo o ECV ni si cambió.
- No obtuve la edad de salida del hogar parental (seed de la usuaria). Busqué indirectamente y no encontré fuente; requiere GEIH o IPUMS.

---

## Puzzle 7 (débil). Fecundidad de 10-14 años: ¿"no cae tan rápido"?

### Takeaway
La premisa **no se confirma en tasas**. Según el DANE, la tasa de 10-14 cayó de 3,1 a 1,6 por mil entre 2015 y 2024 (−48%), una magnitud parecida a la de 15-19 (~−51% a −54%). Sí hay un puzzle previo: entre 2001 y 2011 subió 2,6% anual, más rápido que la de 15-19. Las cifras de prensa de 2025 son inconsistentes (1.630 / 2.929 / 3.179). Esto es casi todo violencia sexual, una pregunta distinta a la fecundidad voluntaria.

### Cited Findings
- Tasa de 10-14 años: 3,1 (2015) → 1,6 (2024) por mil — [Bloomberg Línea / DANE](https://www.bloomberglinea.com/latinoamerica/colombia/nacimientos-en-colombia-cayeron-14-en-2024-y-33-en-ultima-decada/). Nacimientos 10-14 en 2024: 3.159 (preliminar, MinSalud) — [El Universal](https://www.eluniversal.com.co/colombia/2025/09/12/mas-de-63000-bebes-nacieron-de-madres-entre-15-y-19-anos-en-2025/).
- Cifras 2025 en conflicto: 1.630 (posible corte parcial, LEE Javeriana) — [El Colombiano](https://www.elcolombiano.com/tendencias/embarazo-infantil-1600-ninas-menores-de-14-anos-madres-colombia-2025-MD30664998); 2.929 (LEE) — [Consultorsalud](https://consultorsalud.com/?p=344396); 3.179 "embarazos" — [Vanguardia, 11-oct-2026](https://www.vanguardia.com/colombia/2026/10/11/violencia-sexual-contra-ninas-colombia-registro-mas-de-3100-embarazos-en-menores-de-14-anos-en-2025/); [LEE Javeriana, Informe 130 (oct-2025)](https://www.javeriana.edu.co/recursosdb/d/lee/inf-130-embarazo-adolescente-oct-2025).
- 2001-2011: subida de +2,6% anual. Las madres son más rurales, indígenas o afro, no unidas y con menor acceso a salud — [Jaramillo-Mejía y Chernichovsky 2019](https://www.scielo.br/j/csp/a/6HcSZ4LM6MJd3rxMjpmKDjK/?lang=en). DANE tiene un estudio poscensal sobre fecundidad en la niñez — [DANE (solo buscador)](https://webtest.dane.gov.co/files/censo2018/estudios-poscensales/01-poscensales-fecundidad-en-la-ninez-adolescencia.pdf).
- Prensa: [El Espectador, "nacimientos de niñas entre 10 y 14 siguen registrando altas cifras"](https://www.elespectador.com/salud/los-nacimientos-de-ninas-entre-10-y-14-anos-siguen-registrando-altas-cifras/); [El Tiempo, abuso y matrimonio infantil](https://www.eltiempo.com/datos/ninas-embarazadas-cifras-de-abuso-y-matrimonio-infantil-en-colombia-716422); UNFPA estima uniones tempranas — [UNFPA 2023](https://colombia.unfpa.org/sites/default/files/pub-pdf/estimacion_y_caracterizacion_de_los_matrimonios_infantiles_y_las_uniones_tempranas_forzadas_17-02-23.pdf).

### Inferences
- *INFERENCIA:* el puzzle interesante no es la velocidad nacional sino la **dispersión territorial** (Vichada, Guainía y La Guajira con aumentos) y la relación con uniones tempranas. La Ley 2447 de 2025, que prohíbe el matrimonio infantil (conocimiento general, no verificado aquí), ofrece una discontinuidad futura.
- **Rompecabezas: BAJO** (la premisa no se sostiene). **Promesa: MEDIA** (por políticas).

### Gaps
- No verifiqué la serie EEVV definitiva de 10-14 por año ni por departamento.

---

## Puzzle 8 (no verificado). Brechas de edad entre parejas, edad a la primera unión por región, razón de sexos y estacionalidad de nacimientos

### Takeaway
No logré verificar con cifras las brechas de edad, la edad mediana a la primera unión en el Caribe frente a la región andina, ni anomalías de razón de sexos o estacionalidad. Lo único confirmado es que la ENDS 2025 analiza la diferencia de edad con la primera pareja y la edad mediana de primera unión por sexo y región (solo en gráficos), y que una brecha en la que la mujer tiene igual o mayor edad que su pareja predice mayor disolución (ENDS 2015).

### Cited Findings
- La ENDS 2025 (capítulo de nupcialidad) reporta la edad mediana a la primera unión y la diferencia de edad con la primera pareja. Las cifras regionales solo aparecen en gráficos — [MinSalud (solo buscador)](https://minsalud.gov.co/sites/rid/Lists/BibliotecaDigital/RIDE/VS/ED/GCFI/publicacion-nupcialidad-ends-2025.pdf).
- Con la ENDS 2015, una brecha de edad en la que la mujer tiene igual o mayor edad que su pareja se asocia a mayor riesgo de disolución — [Ruiz-Vallejo, Revista CS 2021](https://doaj.org/article/92aab39f799449d8b94ad2d4dd83ca5e).

### Inferences
- *INFERENCIA:* no hay base para rankear este puzzle. Si la usuaria lo quiere, la fuente es la ENDS 2015/2025 (microdatos en el [catálogo IHSN / Banco Mundial](https://datacatalog.worldbank.org/search/dataset/0047829/colombia-encuesta-nacional-de-demograf-a-y-salud-2015)) más el censo 2018 (IPUMS) para las brechas de edad entre cónyuges co-residentes por departamento.

### Gaps
- Razón de sexos al nacer y estacionalidad: no busqué de forma específica por límite de llamadas. No hay evidencia en estas notas de que exista una anomalía colombiana.
- Edad de salida del hogar parental: sin fuente.
