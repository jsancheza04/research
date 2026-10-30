# PAE (Programa de Alimentación Escolar, Colombia): eventos fechados y poco visibles, con poca o ninguna literatura causal

**Nota de método y límites (leer primero).**
- Herramientas: WebSearch (buscador genérico, EE. UU.) y WebFetch. **WebFetch falló (dominio no permitido en esta sesión) para** ideas.repec.org, elpais.com.co, radionacional.co, infobae.com y mineducacion.gov.co. Por eso **todas las fuentes de abajo son "solo buscador"**: título, URL y fragmento devueltos por el buscador, sin haber abierto el texto completo. Ninguna URL es inventada; todas salieron en los resultados de búsqueda.
- No pude consultar Google Scholar, SSRN, NBER ni IDEAS de forma directa. La "verificación académica" se hizo con consultas en WebSearch dirigidas a esas bases (por palabra clave y nombre de serie). Es una verificación de **primer paso**: un "No estudiado" significa "no encontré nada en estas consultas", no "no existe".
- Consultas académicas realizadas (exactas):
  1. `school feeding program Colombia PAE causal effect dropout paper` (modo extendido)
  2. `"Programa de Alimentación Escolar" Colombia efecto deserción Documento CEDE OR "Borradores de Economía"`
  3. `"Indigenous zoom" School Feeding Program Indigenous Peoples Colombia enrollment Lecturas de Economía authors`
  4. `Documento CEDE 2026 alimentación escolar escuelas rurales deserción Saber 11 PAE autores`
  5. `canastas receso escolar PAE impacto evaluación OR estudio "PAE en receso" OR "PAE+" universidad`
  6. `"PAE en casa" OR "ración para preparar en casa" pandemia Colombia efecto estudio evaluación seguridad alimentaria tesis`
  7. `Ley 2046 de 2020 compras públicas locales alimentación escolar evaluación efecto productores estudio académico`
  8. `corruption school feeding Colombia PAE learning outcomes paper sanctions contractors evidence`
  9. `Resolución 29452 de 2017 lineamientos PAE cambio minuta ración efecto estudio OR tesis OR evaluación`
  10. `evaluación de operaciones y resultados Programa de Alimentación Escolar DNP Econometría 2013 SINERGIA`
- Correcciones a las premisas del encargo: (i) la Ley 2046 de 2020 fija un mínimo de **30 %** de compras locales, no 20 %; el 20 % venía de la **Resolución 16432 de 2015** del MEN. (ii) La evaluación del PAE de 2013 que aparece en el catálogo del ICBF figura como **DNP – G|Exponencial – CINDE**, no Econometría.

---

## Descartados: eventos o dimensiones del PAE que ya tienen estudios con identificación

### Takeaway
El efecto "promedio" del PAE sobre la deserción y la repitencia ya tiene al menos dos Documentos CEDE causales recientes (Uniandes). La modalidad indígena (PAEPI, Resolución 18858 de 2018) ya tiene un diferencias en diferencias publicado, aunque débil. Por eso descarto esos dos frentes como "eventos" para proponer.

### Cited Findings
- **"The power of a meal. School feeding and its educational effects: Evidence from Colombia"**, Documento CEDE 2024-24 (Uniandes). Según el resumen, la deserción es entre 10 % y 25 % menor y la repitencia entre 7 % y 13 % menor en los grados con PAE; la finalización de la media sube 39 %. La identificación aprovecha la expansión escalonada del PAE por grado (DiD escalonado, con comparación entre cohortes tratadas, nunca tratadas y aún no tratadas). — [Repositorio Uniandes](https://repositorio.uniandes.edu.co/entities/publication/6ddf030d-55ac-477e-8ec6-efb48ccaad82); [VoxDev](https://voxdev.org/topic/education/power-meal-school-feeding-has-wide-ranging-long-term-effects-education); [RedCol/Minciencias](https://redcol.minciencias.gov.co/Record/UNIANDES2_28c20e95268f2ce7048f282969282fd0/Details). **Estado: Estudiado → descartado.** Autores: no aparecieron en los fragmentos (no los invento).
  - Hay una versión en ResearchGate con un **RD difuso** basado en reglas de focalización por tasas de deserción y repitencia, que **no** encuentra efectos significativos. Sus resultados contradicen los de la versión CEDE. — [ResearchGate](https://www.researchgate.net/publication/381976574_The_Power_of_a_Meal_School_Feeding_and_its_Educational_Effects_Evidence_from_Colombia). No pude confirmar qué versión es la final.
- **Malagón, Manuela y Rico Torres, Kevin (2026)**, "Alimentación escolar y permanencia educativa: evidencia causal en zonas rurales de Colombia", Documentos CEDE 2026-40. Encuentran que la deserción baja ~1,9 p.p. en sedes rurales oficiales y que el ausentismo también cae. — [IDEAS/RePEc (solo buscador)](https://ideas.repec.org/p/col/000089/023151.html). **Estudiado → descartado.**
- **Prada Camacho, Carol Nataly (2024)**, "Indigenous zoom: Impact of the Implementation of the School Feeding Program for Indigenous Peoples in Colombia on Enrollment", *Lecturas de Economía* n.º 101. DiD con 24 departamentos entre 2017 y 2021; el efecto sobre la matrícula indígena es positivo pero no significativo. La PAEPI se creó con la Resolución 18858 de 2018. — [SciELO](http://www.scielo.org.co/scielo.php?script=sci_arttext&pid=S0120-25962024000200047); [DOAJ](https://doaj.org/article/91fe9368d902499dae0dc9e9c8af12e3); [IDEAS](https://ideas.repec.org/a/lde/journl/y2024i101p47-70.html). **Estudiado (con identificación débil) → descartado**, según la regla del encargo.
- **Medellín:** un artículo en la *Revista de Economía del Rosario* (probit con matrícula de 2019) estima −1,0 p.p. en la probabilidad de deserción para quienes acceden al PAE. Hay además un DT 80 del Externado sobre estrategias de permanencia en Medellín (PAE, transporte y jornada complementaria). — [Redalyc](https://www.redalyc.org/journal/5095/509581879003/html/); [Externado DT 80](https://www.uexternado.edu.co/wp-content/uploads/2024/09/DT_80.pdf). La identificación es débil (probit/selección en observables), pero el tema ya está cubierto.
- **Evaluación institucional 2013**: "Evaluación de Operaciones y Resultados para determinar el grado de efectividad del PAE", DNP / G|Exponencial / CINDE (2013), según el catálogo de monitoreo y evaluación del ICBF. — [ICBF](https://www.icbf.gov.co/monitoreo-y-evaluacion?page=6). Una fuente secundaria la cita diciendo que el PAE focalizado reduce la deserción, sobre todo en zonas rurales ([resumen de búsqueda, consulta 1]). **Descartado** (evaluación conocida).
- **Corrupción → aprendizaje**: no encontré ningún paper causal. Solo aparecen tesis jurídicas y cualitativas (U. Santo Tomás, U. de Medellín) y periodismo. — [USTA](https://repository.usta.edu.co/bitstreams/47bf6124-af9d-403a-963f-e5cefc339a10/download); [U. de Medellín](https://repository.udemedellin.edu.co/bitstreams/08c00193-02cc-4f09-a174-d0edfd7e9cb2/download). No hay nada que descartar por este frente, pero no lo desarrollé como caso.

### Inferences
- **Inferencia:** las dos variaciones "obvias" ya están tomadas: la expansión por grado (CEDE 2024-24) y la implementación rural (CEDE 2026-40). Los casos de abajo se apoyan en **otra** variación: interrupciones y retrasos (margen intensivo: días sin PAE), modalidades transitorias y cambios de reglas de compra o lineamientos.

### Gaps
- No obtuve los autores de CEDE 2024-24 ni el PDF completo de CEDE 2026-40 (no pude abrir IDEAS). Hay que verificar si 2026-40 usa fechas de inicio del PAE por sede, porque eso se acercaría al Caso 1.
- No busqué papers del BID ni del Banco Mundial sobre el PAE colombiano con una consulta propia. Quedan pendientes las consultas: `site:publications.iadb.org "alimentación escolar" Colombia` y `site:openknowledge.worldbank.org school feeding Colombia`.

---

## Caso 1. Retrasos en el arranque del PAE por ETC y año (calendario A, 2022–2026)

### Takeaway
Cada enero, y también al volver de mitad de año, un subconjunto distinto de las ~96–97 ETC arranca clases sin PAE porque no ha cerrado la contratación. Hay conteos oficiales y periodísticos por año, lo que da una variación escalonada, **año × ETC**, en los días sin alimentación. No encontré ningún estudio que la use. **Clasificación: No estudiado.** **Promesa: ALTA.** La variación es recurrente, se puede fechar con SECOP II y se cruza con SIMAT.

### Cited Findings (Hechos)
- **2022:** según la UApA (Noticias RCN, 30 ene. 2022), en la semana del 17 de enero entraron a clases 19 territorios y 8 seguían sin PAE. — [Noticias RCN](https://www.noticiasrcn.com/colombia/preocupante-panorama-estudiantes-regresan-a-clases-sin-el-pae-403605) (solo buscador).
- **2022:** 65 de 92 entidades territoriales iniciaron el PAE a tiempo; la rendición de cuentas de la UApA habla de 67 ETC (las cifras no coinciden entre fuentes). — [Radio Nacional](https://www.radionacional.co/actualidad/pae-65-entidades-territoriales-iniciaron-tiempo) (solo buscador).
- **2022 (enero):** Huila y Neiva no comenzaron el PAE porque seguían contratando. — [El Espectador](https://www.elespectador.com/educacion/comenzo-el-ano-escolar-y-algunos-municipios-no-han-cerrado-contratos-para-el-pae/) (solo buscador).
- **2022 (julio):** la Procuraduría alertó que ~183.731 estudiantes no recibían PAE tras el regreso de mitad de año y pidió a las 96 ETC evitar interrupciones. Ciénaga y Pitalito figuran entre los más afectados. — [El Espectador](https://www.elespectador.com/judicial/procuraduria-dice-que-mas-de-180000-estudiantes-no-reciben-alimentacion-del-pae/); [Radio Nacional](https://radionacional.co/actualidad/educacion/pae-180-mil-estudiantes-no-lo-estan-recibiendo-procuraduria) (solo buscador; algunas páginas muestran fechas de 2026 que parecen ser de indexación).
- **2023 (10 mar.):** la Procuraduría pidió explicaciones a 10 ETC por no tener el PAE operando. — [Infobae](https://www.infobae.com/colombia/2023/03/10/procuraduria-solicito-explicaciones-por-incumplimiento-del-pae-en-10-etc/) (solo buscador).
- **2023 (sep.):** el Gobierno pidió a los gobernadores garantizar el inicio oportuno del PAE en 2024 (Circular Externa 06 de 2023). — [El Heraldo, 5 sep. 2023](https://www.elheraldo.co/atlantico/2023/09/05/gobierno-nacional-hace-llamado-a-gobernadores-para-garantizar-el-inicio-oportuno-del-pae-en-2024-1030851); [Circular Ext. 06-2023 (Ámbito Jurídico)](https://ambitojuridico.com/sites/default/files/2023-09/CIRCULAREXT-06-2023.pdf) (solo buscador).
- **2024 (julio):** el primer semestre cerró con cerca de 6 millones de estudiantes con PAE. Al regreso de mitad de año, la UApA reportó dificultades en 9 de 97 ETC para reactivar el programa. — [MEN comunicado](https://www.mineducacion.gov.co/portal/salaprensa/Comunicados/421489:Primer-semestre-del-2024-cerro-con-cerca-de-6-millones-de-estudiantes-con-Programa-de-Alimentacion-Escolar-PAE); [El Heraldo, 24 jul. 2024](https://www.elheraldo.co/colombia/2024/07/24/seis-millones-de-estudiantes-recibieron-pae-durante-primer-semestre-escolar-1113477/) (solo buscador).
- **2026 (17 ene.):** el MEN alertó que más de 860.000 estudiantes podían iniciar 2026 sin PAE por retrasos en **17 ETC**, y mencionó comunidades étnicas afectadas. — [Vanguardia, 18 ene. 2026](https://www.vanguardia.com/colombia/2026/01/18/mas-de-860000-estudiantes-podrian-iniciar-2026-sin-alimentacion-escolar-por-retrasos-en-el-pae/); [El Colombiano](https://www.elcolombiano.com/colombia/mas-de-860000-estudiantes-quedarian-sin-alimentacion-por-demoras-en-contratacion-del-pae-IG32619537); [El País Cali](https://www.elpais.com.co/colombia/mas-de-860000-estudiantes-podrian-iniciar-2026-sin-alimentacion-escolar-en-colombia-1718.html); [Diario del Sur](https://www.diariodelsur.com.co/?p=473683) (solo buscador).
- **Mitad de año (año por verificar):** la Contraloría reportó al menos 350.000 estudiantes sin PAE tres semanas después del regreso, en 5 ETC. Otra nota dice que solo 22 de 96 ETC entregaban alimentos. — [Asuntos Legales](https://www.asuntoslegales.com.co/actualidad/cinco-entidades-territoriales-retrasadas-en-el-programa-de-alimentacion-escolar-para-ninos-y-ninas-desde-el-regreso-a-clases-en-julio-3665266); [Asuntos Legales](https://www.asuntoslegales.com.co/actualidad/advierten-que-74-entidades-territoriales-ejecutoras-del-pae-no-estan-entregando-alimentos-3122125). **Fecha no verificada**: la página muestra "agosto 2026", que parece fecha de indexación.
- Contexto de cobertura según el Gobierno: 76 % en 2022 y 85,5 % en 2026. — [Radio Nacional](https://radionacional.co/actualidad/educacion/programa-de-alimentacion-escolar-llego-al-855-de-cobertura-en-2026) (solo buscador).

### Inferences
- **Pregunta (INFERENCIA):** ¿Los días sin PAE al inicio del año escolar reducen la asistencia y la matrícula efectiva, y aumentan la deserción intra-anual, sobre todo en primaria y zona rural?
- **Variación explotable (INFERENCIA):** la fecha de inicio de ejecución del contrato PAE por ETC y año (SECOP II: fecha de firma y acta de inicio) frente a la fecha de inicio del calendario (que también varía por ETC: según la Circular 035 de 2024, las ETC fijan el arranque entre mediados de enero y mediados de febrero; fuente secundaria en [El Cronista](https://www.cronista.com/colombia/actualidad-co/regreso-a-clases-2025-educacion-ya-confirmo-la-fecha-de-inicio-en-febrero)). Diseño posible: DiD con tratamiento continuo ("días de rezago") o event-study de ETC con retraso frente a ETC a tiempo, año a año. Un riesgo es que el retraso sea endógeno a la capacidad administrativa. Se puede mitigar con efectos fijos de ETC y cambios de gobierno (2024 es el primer año de nuevos mandatarios locales, cuando la Ley de Garantías y el empalme retrasan la contratación).
- **Datos:** SECOP II (público); SIMAT (agregados públicos por ETC en datos.gov.co, microdatos restringidos por solicitud al MEN); reportes de cobertura de la UApA (públicos, semanales en 2021; ver informes en escuelasecretarias.mineducacion.gov.co); Saber 3-5-9 y 11 (ICFES, públicos).
- **Por qué no se ha estudiado (INFERENCIA):** la literatura se centró en la expansión (margen extensivo). Los retrasos solo aparecen en comunicados dispersos y no hay una base consolidada de "fecha de arranque PAE por ETC".

### Gaps
- No encontré una tabla oficial consolidada por ETC y año con la fecha de arranque; hay que construirla desde SECOP II y los informes de la UApA.
- No verifiqué la lista nominal de las 17 ETC de 2026 ni de las 10 de 2023 (las fuentes no se pudieron abrir).

---

## Caso 2. Interrupción prolongada del PAE en Magdalena (2022) y episodios departamentales análogos (Cauca 2023)

### Takeaway
El departamento del Magdalena (ETC no certificada en municipios como Ciénaga) estuvo más de 100 días sin PAE en 2022, con más de 140–147 mil estudiantes afectados, por un conflicto sobre quién ejecutaba el contrato (OCAD designó al ICBF). Es un choque grande, fechado y de origen institucional. Volvió a haber aplazamientos en 2023. **Clasificación: No estudiado.** **Promesa: ALTA–MEDIA.** El choque es nítido y largo, pero es un solo departamento.

### Cited Findings (Hechos)
- **Julio de 2022:** la Procuraduría señaló al Magdalena como el caso más grave, con más de 100 días sin servicio para más de 147 mil estudiantes. — [El Espectador](https://www.elespectador.com/judicial/procuraduria-dice-que-mas-de-180000-estudiantes-no-reciben-alimentacion-del-pae/); [RTVC](https://www.rtvcnoticias.com/pae-estudiantes-sin-alimentos-procuraduria) (solo buscador).
- **Origen:** el OCAD aprobó el PAE del Magdalena el 6 de diciembre de 2021 y designó como ejecutor al ICBF, decisión cuestionada judicialmente. La Procuraduría pidió "celeridad" al gobernador Carlos Caicedo. — [El Espectador](https://www.elespectador.com/judicial/procuraduria-le-pide-celeridad-al-gobernado-caicedo-para-que-avance-el-pae/) (solo buscador).
- **Mayo de 2022:** cinco meses sin PAE para más de 140.000 estudiantes. — [Radio Nacional](https://www.radionacional.co/regiones/caribe/pae-en-magdalena-140-mil-estudiantes-afectados-por-retrasos) (solo buscador). Una nota sin año visible habla de 113 días de retraso y de inicio del nuevo contrato el 17 de mayo (**año no verificado**).
- **2023:** la adjudicación del operador PAE del Magdalena acumuló cuatro aplazamientos. — [Semana](https://www.semana.com/nacion/barranquilla/articulo/cero-y-van-cuatro-los-aplazamientos-para-contratar-al-operador-del-pae-en-magdalena-que-esta-pasando/202340/) (solo buscador).
- **Cauca, agosto de 2023:** más de 30 mil estudiantes se habrían quedado sin PAE. — [Semana](https://www.semana.com/nacion/articulo/mas-de-30-mil-estudiantes-se-habrian-quedado-sin-el-pae-en-el-cauca/202308/) (solo buscador; solo vi el título).
- Retrasos en cuatro departamentos que afectaron a 400 mil estudiantes (año por verificar). — [El Colombiano](https://www.elcolombiano.com/colombia/retrasos-en-pae-cuatro-departamentos-afectan-400-mil-estudiantes-IB25176691) (solo buscador).

### Inferences
- **Pregunta (INFERENCIA):** ¿Una suspensión del PAE de más de 100 días aumenta la deserción y reduce el desempeño en Saber 11 y en Saber 3-5-9 frente a departamentos vecinos con el servicio activo?
- **Variación:** Magdalena-departamento (sus municipios no certificados) frente a ETC certificadas dentro del mismo departamento (Santa Marta, Ciénaga) y frente a departamentos del Caribe, comparando 2022 con 2019 y 2021–2023. Es un DiD o control sintético por municipio. Tiene la ventaja de una comparación **intradepartamental**, porque Santa Marta es ETC aparte (su propio contrato).
- **Datos:** SIMAT (deserción intra-anual por sede, en agregados públicos); Saber 11 de 2022 (público); SECOP II (fechas del contrato); SIVIGILA (desnutrición aguda en menores de 5 años por municipio; solo como proxy del hogar, porque no cubre la edad escolar completa).
- **Por qué no se ha estudiado:** se cubrió como escándalo político (gobernador Caicedo) y no como choque cuasi-experimental. Además, 2022 coincide con el retorno post-COVID, lo que complica la identificación.

### Gaps
- Fechas exactas de inicio y fin de la suspensión en 2022 y 2023 (no pude abrir las notas).
- Bolívar, Chocó y Arauca: no verifiqué episodios específicos por falta de presupuesto de búsqueda.

---

## Caso 3. PAE en recesos escolares: "PAE+" (2023) → canastas de receso (2024) → "PAE en Receso" (2026)

### Takeaway
Desde 2023 el Gobierno extendió el PAE a las vacaciones con canastas alimentarias a domicilio, **focalizadas** en 109 municipios de 17 (o 18) departamentos con alta inseguridad alimentaria. En 2026 escaló a 1,4 millones de canastas (junio y diciembre). La regla de priorización municipal sugiere un diseño de focalización. Hay ciudades excluidas explícitamente (Cali). **Clasificación: No estudiado.** **Promesa: ALTA.** El programa es nuevo, la focalización es explícita y no hay evaluación.

### Cited Findings (Hechos)
- **Lanzamiento en La Guajira (2023):** el PAE+ es una modalidad para recesos con canastas en los hogares de unos 600 mil estudiantes, en 109 municipios de 17 departamentos con alta inseguridad alimentaria. — [MEN](https://www.mineducacion.gov.co/1780/w3-article-415831.html); [Radio Nacional](https://radionacional.co/actualidad/educacion/como-funcionara-el-pae-en-recesos-escolares); [Cambio, jun. 2023](https://cambiocolombia.com/pais/articulo/2023/6/en-que-consiste-el-programa-pae-que-presento-el-gobierno-en-la-guajira) (solo buscador).
- **Receso de 2024:** 577 mil canastas; las notas de fin de 2024 hablan de 109 municipios en **18** departamentos (no coincide con los 17 originales). — [RTVC](https://www.rtvcnoticias.com/canastas-alimentarias-receso-escolar-2024); [Radio Nacional](https://radionacional.co/actualidad/entrega-de-577-mil-canastas-alimentarias-estudiantes-en-receso-escolar) (solo buscador).
- **La Guajira:** 221.966 canastas en Riohacha, Manaure, Maicao y Uribia durante el receso de mitad de año. — [MEN](https://www.mineducacion.gov.co/1780/w3-article-429408.html) (solo buscador; año por verificar).
- **Cúcuta (nov. 2025):** 106.000 canastas, presentadas como el 100 % de los matriculados. — referido en el resumen de búsqueda de [MEN](https://www.mineducacion.gov.co/1780/w3-article-426738.html) (solo buscador; asignación de la URL a la nota de Cúcuta **no verificada**).
- **Exclusión explícita:** la Secretaría de Educación de Cali informó que el MEN no priorizó a Cali para las canastas del receso. — [Alcaldía de Cali](https://www.cali.gov.co/boletines/publicaciones/192984/ministerio-de-educacion-no-priorizo-a-cali-para-la-entrega-de-canastas-alimentarias-del-pae-durante-el-receso-escolar/) (solo buscador).
- **2026:** "PAE en Receso" con 1,4 millones de canastas para junio y diciembre de 2026; 722.000 en junio en municipios con alta inseguridad alimentaria. La UApA rechazó acusaciones de fines electorales (2026 es año electoral). — [Infobae, 18 jun. 2026](https://www.infobae.com/colombia/2026/06/18/la-uapa-rechazo-fines-electorales-en-la-entrega-de-722000-canastas-del-pae-en-municipios-con-alta-inseguridad-alimentaria/) (solo buscador).
- **Antecedente, 2020:** la Circular 1 de 2020 de la UApA dio orientaciones para la continuidad del PAE; La FM reportó que el PAE "seguirá durante las vacaciones" en la cuarentena. — [Circular 0001 2020 (normograma ICFES)](https://normograma.icfes.gov.co/docs/pdf/circular_mineducacion_0001_2020.pdf); [La FM](https://www.lafm.com.co/actualidad/cuarentena-programa-de-alimentacion-escolar-seguira-durante-las-vacaciones-199745) (solo buscador).

### Inferences
- **Pregunta (INFERENCIA):** ¿Las canastas de receso reducen la caída de asistencia y matrícula al reanudar clases (el "summer slide" del retorno) o los indicadores de desnutrición en los municipios priorizados?
- **Variación:** municipios priorizados frente a no priorizados con inseguridad alimentaria similar. Si el MEN usó un índice con umbral (por ejemplo, la prevalencia de inseguridad alimentaria de la ENSIN o el IPM), sería posible un RD. Si no, cabe un DiD con matching. También hay variación en la intensidad (canastas por estudiante) y en el tiempo (2023 → 2024 → 2026, con cambio de 17 a 18 departamentos).
- **Datos:** lista de municipios priorizados (resoluciones de la UApA, por solicitud vía derecho de petición si no está publicada); SIMAT (matrícula de enero frente a noviembre); SIVIGILA (desnutrición aguda en menores de 5 años: evento 113, público por municipio y semana); SECOP II (contratos de canastas).
- **Por qué no se ha estudiado:** el programa es muy reciente (2023+), la regla de focalización no es pública y se percibe como asistencia política o electoral.

### Gaps
- No encontré el acto administrativo ni el criterio exacto de priorización (índice y umbral). Es indispensable para el diseño.
- No verifiqué si la cobertura de 2025 fue nacional o focalizada.

---

## Caso 4. "PAE en casa" durante el COVID (Decreto 470 y Resolución UApA 006 de 25 mar. 2020 → regreso a "PAE en sitio" en 2021)

### Takeaway
La Resolución 006 de 2020 de la UApA creó modalidades transitorias (ración industrializada, ración para preparar en casa y bono alimentario). Las ETC eligieron mezclas distintas (en un corte, 87 % ración para preparar en casa y 6 % industrializada) y transitaron a "PAE en sitio" en fechas distintas en 2021. Solo encontré un estudio de caso descriptivo. **Clasificación: Poco estudiado.** **Promesa: MEDIA.** El choque es universal (afecta a todas las ETC), pero hay variación en modalidad, frecuencia y timing de retorno.

### Cited Findings (Hechos)
- **Resolución 006 del 25 de marzo de 2020 (UApA):** reglamenta el Decreto 470 de 2020 y modifica transitoriamente los lineamientos. El art. 4 crea las modalidades transitorias. El art. 5 fija la distribución: ración industrializada cada 5, 10 o 20 días; ración para preparar en casa y bono, mensual. — [Resolución 0006 de 2020 (escuelasecretarias MEN)](https://escuelasecretarias.mineducacion.gov.co/sites/default/files/2022-10/Resoluci%C3%B3n%20No.%200006%20del%2025%20de%20marzo%20de%202020%20de%20la%20Unidad%20Administrativa%20Especial%20de%20Alimentaci%C3%B3n%20Escolar.pdf); [Anexo 1](https://escuelasecretarias.mineducacion.gov.co:443/sites/default/files/2022-09/Anexo%201%20Resoluci%C3%B3n%20No.%200006%20del%2025%20de%20marzo%20de%202020%20de%20la%20Unidad%20Administrativa%20Especial%20para%20la%20Alimentaci%C3%B3n%20Escolar.pdf) (solo buscador). La Resolución 007 de 2020 la modificó.
- El MEN anunció la normativa de emergencia para el "PAE para consumo en el hogar". — [MEN](https://www.mineducacion.gov.co/portal/salaprensa/Noticias/394531:Gobierno-Nacional-expide-normatividad-en-el-marco-de-la-Emergencia-para-garantizar-la-ejecucion-del-Programa-de-Alimentacion-Escolar-para-consumo-en-el-hogar) (solo buscador).
- Informes semanales de operación del PAE en 2021 (por ETC y modalidad); en un corte, 87 % ración para preparar en casa y 6 % industrializada. — [Informe 14-05-2021](https://escuelasecretarias.mineducacion.gov.co/sites/default/files/2022-10/Informe%20de%20operaci%C3%B3n%20Programa%20de%20Alimentaci%C3%B3n%20Escolar%2014052021.pdf); [Informe 28-05-2021](https://escuelasecretarias.mineducacion.gov.co/sites/default/files/2022-10/17.%20Informe%20de%20operaci%C3%B3n%20PAE%20semanal%2028052021.pdf); [Informe 18-06-2021](https://escuelasecretarias.mineducacion.gov.co:443/sites/default/files/2022-10/20.%20Informe%20de%20operaci%C3%B3n%20PAE%20semanal%2018062021.pdf) (solo buscador; qué corte da el 87 % **no verificado**).
- Según un documento del MEN, las 96 ETC implementaron el PAE en casa, para ~5,6 millones de estudiantes. — [MEN recurso](https://www.mineducacion.gov.co:443/1759/articles-402602_recurso_1.pdf) (solo buscador).
- Ejemplo local: Santa Marta reanudó el PAE con más de 11 mil mercados. — [Alcaldía de Santa Marta](https://santamarta.gov.co/sala-prensa/noticias/con-la-entrega-de-mas-de-11-mil-mercados-se-reanudo-el-pae-en-santa-marta) (solo buscador).
- **Literatura encontrada:** un estudio de caso descriptivo sobre el colegio CEDID Ciudad Bolívar (Bogotá, 2021). — [Revista de Salud Pública UNAL](https://revistas.unal.edu.co/index.php/revsaludpublica/article/view/97562). También una ficha de la CEPAL (observatorio, no evaluación). — [CEPAL](https://observatorioalianzapacifico.cepal.org/en/covid-19/measure/school-feeding-programme-pae-home-programa-de-alimentacion-escolar-pae-en-casa).

### Inferences
- **Pregunta (INFERENCIA):** ¿Las ETC que entregaron ración para preparar en casa mensual (frente a bono o ración industrializada), o que reanudaron el PAE antes, tuvieron menos deserción en 2020–2021?
- **Variación:** modalidad elegida por ETC; fecha de primera entrega tras el cierre de marzo de 2020; fecha de transición a "PAE en sitio" en 2021. Están en los informes semanales de la UApA, que parecen un panel ETC × semana.
- **Datos:** informes semanales UApA 2021 (públicos en PDF); SIMAT (deserción 2020–2021); Saber 11 de 2020–2021; EPF/GEIH para el consumo de los hogares (DANE, públicas).
- **Por qué está poco estudiado:** el choque COVID lo confunde todo (cierres, alternancia) y la elección de modalidad es endógena.

### Gaps
- No verifiqué si existen informes semanales para 2020 (solo vi los de 2021).

---

## Caso 5. Compras públicas locales en el PAE: Resolución 16432 de 2015 (≥20 %) → Ley 2046 de 2020 (≥30 %) + Decreto 248 de 2021

### Takeaway
Hay dos reglas fechadas que obligan a comprar a productores locales y de la agricultura campesina, familiar y comunitaria. La de 2015 era del MEN y aplicaba a restaurantes escolares (20 %). La Ley 2046 del 6 de agosto de 2020 (reglamentada en 2021) eleva el mínimo al 30 % para todas las entidades estatales que compran alimentos. Solo encontré ensayos críticos, una tesis de barreras y autoevaluaciones del ICBF. **Clasificación: Poco estudiado.** **Promesa: MEDIA.** Es una regla limpia y fechada, pero el cumplimiento cuesta medirlo y la regla es nacional (sin grupo de control obvio).

### Cited Findings (Hechos)
- **Ley 2046 de 2020:** obliga a las entidades del Estado a adquirir al menos 30 % de sus alimentos a pequeños productores locales y a la agricultura campesina, familiar y comunitaria. El Decreto 248 de 2021 reglamenta el mínimo. — [Colombia Compra, Boletín de Relatoría VI](https://colombiacompra.gov.co/wp-content/uploads/2024/09/boletin_de_relatoria_-_edicion_vi.pdf); [texto de la ley (normograma INVIMA)](https://normograma.invima.gov.co/normograma/docs/pdf/ley_2046_2020.pdf); [FAOLEX](https://faolex.fao.org/docs/pdf/col199145.pdf) (solo buscador).
- Cuando la oferta local es insuficiente, la Mesa Técnica Nacional de Compras Públicas certifica la insuficiencia. — [Concepto C-1274 de 2026, ANCP-CCE](https://relatoria.colombiacompra.gov.co/conceptos/c-1274-de-2026/) (solo buscador).
- **Antecedente:** la Resolución 16432 de 2015 del MEN exigía que los restaurantes escolares compraran al menos 20 % a agricultores campesinos. — [Acevedo (Semillas/UNAL), "La ley 2046 de compras públicas: ¿espejismo o alternativa…?"](https://semillas.org.co/apc-aa-files/353467686e6667686b6c676668f16c6c/14-la-ley-2046-de-compras-publicas.pdf) (solo buscador).
- Directiva 9 de 2024 sobre la participación de pequeños productores. — [DIR-9-2024 (Ámbito Jurídico)](https://ambitojuridico.com/sites/default/files/2024-10/DIR-9-2024.pdf) (solo buscador; emisor no verificado).
- El MEN (jul. 2025) anunció una estrategia para articular el PAE con las compras locales. — [MEN](https://www.mineducacion.gov.co/1780/w3-article-424994.html) (solo buscador).
- Ejemplo local: Cali integra pequeños productores al PAE. — [Alcaldía de Cali](https://www.cali.gov.co/educacion/publicaciones/163196/pequenos-productores-agropecuarios-se-integran-al-programa-de-alimentacion-escolar-de-cali/) (solo buscador).
- **Literatura:** el ensayo crítico de Acevedo (arriba); la tesis UniMinuto (2025) "Barreras de la Ley 2046 y Decreto 248…" ([UniMinuto](https://repository.uniminuto.edu/bitstreams/d213db7d-eb7f-40f4-ae48-60dcb359e185/download)); y un reporte del ICBF con $342.759 millones en compras locales en 2024–2025 ([ICBF](https://www.icbf.gov.co/system/files/30.%20VF_compras%20locales.pdf.pdf)). Ninguno es causal.

### Inferences
- **Pregunta (INFERENCIA):** ¿El mínimo de compras locales en el PAE aumentó los ingresos y las ventas de los productores campesinos del municipio, o encareció y retrasó la contratación del PAE (con más días sin servicio)?
- **Variación:** intensidad previa (municipios donde el PAE era una fracción grande de la demanda local de alimentos, o con mayor oferta campesina según el Censo Nacional Agropecuario 2014) × fecha de la regla (2015 y 2020–2021). También proponentes locales frente a no locales en SECOP II, antes y después.
- **Datos:** SECOP II (proponentes, precios unitarios; público); Censo Nacional Agropecuario 2014 y EVA (públicos); registros de productores locales (ADR/MinAgricultura, acceso incierto).
- **Por qué está poco estudiado:** el cumplimiento no se reporta de forma sistemática y la regla es nacional.

### Gaps
- No encontré informes de la Contraloría ni de la Procuraduría que midan el cumplimiento del 30 % en el PAE específicamente.

---

## Caso 6. Cambio de lineamientos técnicos: Resolución 29452 de 29 dic. 2017 (con régimen de transición, Res. 1750 de 2018) → Resolución 335 de 2021

### Takeaway
La Resolución 29452 de 2017 reemplazó los lineamientos técnico-administrativos del PAE (estándares, minutas, comités). La Resolución 1750 de 2018 creó un régimen de transición para las ETC con proyectos presentados antes de un corte en febrero de 2018. En 2021 la Resolución 335 la reemplazó. No encontré ningún estudio. **Clasificación: No estudiado.** **Promesa: BAJA–MEDIA.** La regla es fechada, pero es nacional y difusa; el corte de transición de 2018 es lo más aprovechable.

### Cited Findings (Hechos)
- Resolución 29452 de 2017, MEN, Diario Oficial 50.461 del 29 dic. 2017: expide lineamientos, estándares y condiciones mínimas, y deroga las normas anteriores. — [ICBF compilación](https://www.icbf.gov.co/cargues/avance/compilacion/docs/resolucion_mineducacion_29452_2017.htm) (solo buscador).
- La Resolución 1750 de 2018 crea un régimen de transición para las ETC que habían presentado proyectos antes de un corte en febrero de 2018; los procesos nuevos debían seguir la 29452. — [Res. 1750 de 2018 (ICBF)](https://www.icbf.gov.co/cargues/avance/compilacion/docs/resolucion_mineducacion_1750_2018.htm); [Ámbito Jurídico PDF](https://ambitojuridico.com/sites/default/files/BancoMedios/Archivos/res-1750-18%28mineducacion%29.pdf) (solo buscador).
- La 29452 fue reemplazada por la Resolución 335 de 2021. Itagüí, por ejemplo, operó con la 29452 y luego cambió a la 335. — [Informe de seguimiento PAE 2023, Itagüí](https://www.itagui.gov.co/uploads/entidad/control/cd94e-informe-seguimiento-al-pae-2023.pdf) (solo buscador).
- Ejemplo de implementación: Antioquia creó un comité departamental de seguimiento según la 29452. — [Gobernación de Antioquia](https://www.antioquia.gov.co/index.php/resoluciones-2012-2019/resolución-n°-2018060227647-por-la-cual-se-crea-el-comité-de-seguimiento-operativo-departamental-del-programa-de-alimentación-escolar-pae-en-la-gerencia-de-seguridad-alimentaria-y-nutricional-de-antioquia-maná-según-resolución-no-29452-del-29-de-diciembre) (solo buscador).

### Inferences
- **Pregunta (INFERENCIA):** ¿Los estándares más exigentes de la 29452 cambiaron los costos por ración, la competencia en las licitaciones (número de oferentes) o la frecuencia de interrupciones?
- **Variación:** ETC dentro frente a fuera del régimen de transición de la Res. 1750 de 2018 (según la fecha de presentación del proyecto), en una ventana 2017–2019.
- **Datos:** SECOP I/II (oferentes, valor por ración; público).
- **Por qué no se ha estudiado:** es un cambio técnico-administrativo de baja visibilidad y sus resultados (calidad de la ración) no se miden de forma sistemática.

### Gaps
- No verifiqué el contenido sustantivo de la Resolución 335 de 2021 (cambios de minuta o de ración) ni su fecha exacta.
- **Temas pedidos y no cubiertos por falta de presupuesto de búsqueda:** la creación de la UApA (Ley 1955 de 2019, operativa en 2020) como evento institucional; la decisión de universalización (2023–2024); los recortes presupuestales de mitad de año (hay un titular de Consultorsalud: "Contraloría advierte que 1,6 millones de estudiantes podrían quedar sin alimentación escolar en 2026" por desfinanciación, [Consultorsalud](https://consultorsalud.com/contraloria-alerta-desfinanciacion-pae-2026/), solo buscador, no verificado); y suspensiones en Chocó (Quibdó, alimentos en mal estado en 2023, [ColombiaSupport](https://colombiasupport.net/?p=6251), fuente activista), Bolívar y Arauca.
