# Chiapas: law history in git

The law of the State of Chiapas (Estado Libre y Soberano de Chiapas, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-chp/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

86 ordenamientos with 650 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO DE CHIAPAS | 186 | as first published, then each reform: 6 February 1921 to 10 September 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE CHIAPAS | 64 | as first published, then each reform: 5 February 1938 to 29 July 2026 |
| `codigo-de-atencion-a-la-familia-y-grupos-vulnerables/` | CODIGO DE ATENCION A LA FAMILIA Y GRUPOS VULNERABLES PARA EL ESTADO LIBRE Y SOBERANO DE CHIAPAS | 7 | as first published, then each reform: 3 May 2006 to 1 January 2016 |
| `codigo-de-ejecucion-de-sanciones-penales-y-medidas-de-libert/` | CODIGO DE EJECUCION DE SANCIONES PENALES Y MEDIDAS DE LIBERTAD ANTICIPADA PARA EL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 28 November 2014 to 15 May 2025 |
| `codigo-de-organizacion-del-poder-judicial/` | CODIGO DE ORGANIZACION DEL PODER JUDICIAL DEL ESTADO DE CHIAPAS | 4 | as first published, then each reform: 20 August 2020 to 29 July 2026 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES | 34 | as first published, then each reform: 5 February 1938 to 24 January 2019 |
| `codigo-de-procedimientos-de-actuacion-en-la-fiscalizacion-mu/` | CODIGO DE PROCEDIMIENTOS DE ACTUACION EN LA FISCALIZACION MUNICIPAL DE CINTALAPA DE FIGUEROA, CHIAPAS | 1 | as first published: 5 February 2026 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE CHIAPAS -- ANTES CODIGO DE LA HACIENDA PUBLICA PARA EL ESTADO DE CHIAPAS -- | 26 | as first published, then each reform: 18 May 2016 to 1 January 2026 |
| `codigo-fiscal-municipal/` | CODIGO FISCAL MUNICIPAL | 2 | as first published, then each reform: 9 July 1998 to 27 May 2010 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE CHIAPAS | 67 | as first published, then each reform: 13 May 2007 to 30 April 2026 |
| `ley-ambiental/` | LEY AMBIENTAL PARA EL ESTADO DE CHIAPAS | 6 | as first published, then each reform: 19 November 2015 to 7 August 2025 |
| `ley-de-adopcion/` | LEY DE ADOPCION PARA EL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 16 April 2020 to 27 November 2025 |
| `ley-de-adquisiciones-arrendamiento-de-bienes-muebles-y-contr/` | LEY DE ADQUISICIONES, ARRENDAMIENTO DE BIENES MUEBLES Y CONTRATACION DE SERVICIOS PARA EL ESTADO DE CHIAPAS | 3 | as first published, then each reform: 16 May 2019 to 31 December 2025 |
| `ley-de-aguas/` | LEY DE AGUAS PARA EL ESTADO DE CHIAPAS | 9 | as first published, then each reform: 23 December 2000 to 12 December 2013 |
| `ley-de-amnistia/` | LEY DE AMNISTIA | 3 | as first published, then each reform: 26 January 1994 to 4 February 1994 |
| `ley-de-archivos/` | LEY DE ARCHIVOS DEL ESTADO DE CHIAPAS | 1 | as first published: 6 August 2020 |
| `ley-de-asentamientos-humanos-ordenamiento-territorial-y-desa/` | LEY DE ASENTAMIENTOS HUMANOS, ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO DEL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 28 December 2017 to 19 March 2026 |
| `ley-de-asistencia-e-integracion-de-las-personas-adultas-mayo/` | LEY DE ASISTENCIA E INTEGRACION DE LAS PERSONAS ADULTAS MAYORES DEL ESTADO DE CHIAPAS | 1 | as first published: 1 January 2016 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS PARA EL ESTADO DE CHIAPAS | 1 | as first published: 1 January 2017 |
| `ley-de-bibliotecas/` | LEY DE BIBLIOTECAS PARA EL ESTADO DE CHIAPAS | 1 | as first published: 8 June 2017 |
| `ley-de-bienes-asegurados-abandonados-y-decomisados/` | LEY DE BIENES ASEGURADOS ABANDONADOS Y DECOMISADOS PARA EL ESTADO DE CHIAPAS | 7 | as first published, then each reform: 25 February 2004 to 14 February 2025 |
| `ley-de-catastro/` | LEY DE CATASTRO PARA EL ESTADO DE CHIAPAS | 9 | as first published, then each reform: 24 December 2002 to 10 December 2020 |
| `ley-de-categorizacion-politico-administrativa-de-los-nucleos/` | LEY DE CATEGORIZACION POLITICO-ADMINISTRATIVA DE LOS NUCLEOS DE POBLACION DEL ESTADO DE CHIAPAS | 3 | as first published, then each reform: 13 August 1998 to 22 October 2009 |
| `ley-de-centros-ecoturisticos-de-autogestion-comunitaria/` | LEY DE CENTROS ECOTURISTICOS DE AUTOGESTION COMUNITARIA PARA EL ESTADO DE CHIAPAS | 1 | as first published: 30 June 2011 |
| `ley-de-ciencia-tecnologia-e-innovacion/` | LEY DE CIENCIA, TECNOLOGIA E INNOVACION DEL ESTADO DE CHIAPAS | 1 | as first published: 30 September 2021 |
| `ley-de-ciudades-rurales-sustentables/` | LEY DE CIUDADES RURALES SUSTENTABLES PARA EL ESTADO DE CHIAPAS | 3 | as first published, then each reform: 8 January 2009 to 6 November 2010 |
| `ley-de-concesiones-de-servicios-e-infraestructura-publica/` | LEY DE CONCESIONES DE SERVICIOS E INFRAESTRUCTURA PUBLICA PARA EL ESTADO DE CHIAPAS | 5 | as first published, then each reform: 17 May 2007 to 24 May 2018 |
| `ley-de-control-constitucional/` | LEY DE CONTROL CONSTITUCIONAL PARA EL ESTADO DE CHIAPAS | 1 | as first published: 30 November 2002 |
| `ley-de-coordinacion-para-el-establecimiento-y-desarrollo-de/` | LEY DE COORDINACION PARA EL ESTABLECIMIENTO Y DESARROLLO DE LAS ZONAS ECONOMICAS ESPECIALES EN EL ESTADO DE CHIAPAS | 1 | as first published: 10 November 2016 |
| `ley-de-derechos/` | LEY DE DERECHOS DEL ESTADO DE CHIAPAS | 5 | as first published, then each reform: 3 January 2025 to 20 August 2026 |
| `ley-de-derechos-para-el-ejercicio-del-periodismo-en-el-estad/` | LEY DE DERECHOS PARA EL EJERCICIO DEL PERIODISMO EN EL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 13 September 2007 to 28 November 2014 |
| `ley-de-derechos-y-cultura-indigenas/` | LEY DE DERECHOS Y CULTURA INDIGENAS DEL ESTADO DE CHIAPAS | 4 | as first published, then each reform: 29 July 1999 to 18 June 2026 |
| `ley-de-desarrollo-constitucional-del-congreso/` | LEY DE DESARROLLO CONSTITUCIONAL DEL CONGRESO DEL ESTADO DE CHIAPAS | 3 | as first published, then each reform: 1 October 2024 to 7 August 2025 |
| `ley-de-desarrollo-constitucional-en-materia-de-gobierno-y-ad/` | LEY DE DESARROLLO CONSTITUCIONAL EN MATERIA DE GOBIERNO Y ADMINISTRACION MUNICIPAL DEL ESTADO DE CHIAPAS | 15 | as first published, then each reform: 1 February 2018 to 1 January 2027 |
| `ley-de-desarrollo-constitucional-para-la-igualdad-de-genero/` | LEY DE DESARROLLO CONSTITUCIONAL PARA LA IGUALDAD DE GENERO Y ACCESO A UNA VIDA LIBRE DE VIOLENCIA PARA LAS MUJERES DEL ESTADO DE CHIAPAS | 8 | as first published, then each reform: 3 August 2017 to 3 April 2025 |
| `ley-de-desarrollo-economico-y-atraccion-de-inversiones/` | LEY DE DESARROLLO ECONOMICO Y ATRACCION DE INVERSIONES DEL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 6 March 2014 to 5 February 2026 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE PARA EL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 15 December 2022 to 5 February 2026 |
| `ley-de-desarrollo-rural-sustentable/` | LEY DE DESARROLLO RURAL SUSTENTABLE DEL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 31 August 2017 to 16 April 2026 |
| `ley-de-desarrollo-social-y-del-humanismo/` | LEY DE DESARROLLO SOCIAL Y DEL HUMANISMO DEL ESTADO DE CHIAPAS -- ANTES -- LEY DE DESARROLLO SOCIAL DEL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 18 May 2017 to 22 May 2025 |
| `ley-de-desarrollo-y-proteccion-a-la-actividad-artesanal/` | LEY DE DESARROLLO Y PROTECCION A LA ACTIVIDAD ARTESANAL DEL ESTADO DE CHIAPAS | 3 | as first published, then each reform: 26 October 2017 to 21 May 2026 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO LIBRE Y SOBERANO DE CHIAPAS | 7 | as first published, then each reform: 15 October 2020 to 4 June 2026 |
| `ley-de-entidades-paraestatales/` | LEY DE ENTIDADES PARAESTATALES DEL ESTADO DE CHIAPAS | 4 | as first published, then each reform: 16 August 2001 to 1 November 2009 |
| `ley-de-entrega-recepcion-de-los-ayuntamientos/` | LEY DE ENTREGA RECEPCION DE LOS AYUNTAMIENTOS DEL ESTADO DE CHIAPAS | 1 | as first published: 28 May 2020 |
| `ley-de-escalafon-de-los-servidores-del-ramo-de-educacion-al/` | LEY DE ESCALAFON DE LOS SERVIDORES DEL RAMO DE EDUCACION, AL SERVICIO DEL ESTADO | 1 | as first published: 4 March 1942 |
| `ley-de-establecimientos-mutuantes/` | LEY DE ESTABLECIMIENTOS MUTUANTES DEL ESTADO DE CHIAPAS | 3 | as first published, then each reform: 4 May 2016 to 4 January 2025 |
| `ley-de-expropiacion/` | LEY DE EXPROPIACION DEL ESTADO DE CHIAPAS | 3 | as first published, then each reform: 19 June 1999 to 16 April 2020 |
| `ley-de-firma-electronica-avanzada/` | LEY DE FIRMA ELECTRONICA AVANZADA DEL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 22 October 2009 to 29 November 2012 |
| `ley-de-fiscalizacion-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION Y RENDICION DE CUENTAS DEL ESTADO DE CHIAPAS | 7 | as first published, then each reform: 2 February 2017 to 22 November 2024 |
| `ley-de-fomento-a-la-lectura-y-el-libro/` | LEY DE FOMENTO A LA LECTURA Y EL LIBRO DEL ESTADO DE CHIAPAS | 1 | as first published: 8 June 2017 |
| `ley-de-fomento-a-las-actividades-de-las-organizaciones-de-la/` | LEY DE FOMENTO A LAS ACTIVIDADES DE LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL PARA EL ESTADO DE CHIAPAS | 1 | as first published: 13 September 2014 |
| `ley-de-fomento-al-deporte/` | LEY DE FOMENTO AL DEPORTE DEL ESTADO DE CHIAPAS | 1 | as first published: 6 November 2004 |
| `ley-de-fomento-para-el-uso-de-la-bicicleta-y-proteccion-al-c/` | LEY DE FOMENTO PARA EL USO DE LA BICICLETA Y PROTECCION AL CICLISTA DEL ESTADO DE CHIAPAS | 1 | as first published: 5 November 2020 |
| `ley-de-fomento-y-desarrollo-agricola/` | LEY DE FOMENTO Y DESARROLLO AGRICOLA DEL ESTADO DE CHIAPAS | 1 | as first published: 13 August 1998 |
| `ley-de-fomento-y-sanidad-pecuaria/` | LEY DE FOMENTO Y SANIDAD PECUARIA PARA EL ESTADO DE CHIAPAS | 3 | as first published, then each reform: 7 July 2016 to 19 April 2023 |
| `ley-de-fomento-desarrollo-e-innovacion-para-la-estrategia-ma/` | LEY DE FOMENTO, DESARROLLO E INNOVACION PARA LA ESTRATEGIA MARCA CHIAPAS | 2 | as first published, then each reform: 12 June 2014 to 16 April 2020 |
| `ley-de-fraccionamientos-y-conjuntos-habitacionales/` | LEY DE FRACCIONAMIENTOS Y CONJUNTOS HABITACIONALES PARA EL ESTADO Y LOS MUNICIPIOS DE CHIAPAS | 5 | as first published, then each reform: 22 October 2009 to 14 February 2025 |
| `ley-de-gobierno-digital/` | LEY DE GOBIERNO DIGITAL DEL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 20 March 2025 to 20 November 2025 |
| `ley-de-hacienda-municipal/` | LEY DE HACIENDA MUNICIPAL | 5 | as first published, then each reform: 20 December 1997 to 3 January 2010 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE CHIAPAS PARA EL EJERCICIO FISCAL 2026 | 3 | as first published, then each reform: 1 January 2026 to 14 May 2026 |
| `ley-de-instituciones-y-procedimientos-electorales/` | LEY DE INSTITUCIONES Y PROCEDIMIENTOS ELECTORALES DEL ESTADO DE CHIAPAS | 6 | as first published, then each reform: 23 September 2023 to 15 September 2026 |
| `ley-de-la-comision-estatal-de-los-derechos-humanos/` | LEY DE LA COMISION ESTATAL DE LOS DERECHOS HUMANOS DEL ESTADO DE CHIAPAS | 3 | as first published, then each reform: 28 December 2013 to 10 November 2016 |
| `ley-de-la-defensoria-publica/` | LEY DE LA DEFENSORIA PUBLICA DEL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 12 February 2012 to 30 November 2014 |
| `ley-de-la-juventud/` | LEY DE LA JUVENTUD PARA EL ESTADO DE CHIAPAS | 1 | as first published: 18 September 2012 |
| `ley-de-las-culturas-y-las-artes/` | LEY DE LAS CULTURAS Y LAS ARTES DEL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 3 May 2006 to 29 January 2009 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE CHIAPAS | 7 | as first published, then each reform: 18 June 2015 to 27 November 2025 |
| `ley-de-mecanismos-alternativos-de-solucion-de-controversias/` | LEY DE MECANISMOS ALTERNATIVOS DE SOLUCION DE CONTROVERSIAS PARA EL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 28 January 2025 to 7 May 2026 |
| `ley-de-medios-de-impugnacion-en-materia-electoral/` | LEY DE MEDIOS DE IMPUGNACION EN MATERIA ELECTORAL DEL ESTADO DE CHIAPAS | 3 | as first published, then each reform: 30 June 2020 to 20 August 2026 |
| `ley-de-movilidad-y-transporte/` | LEY DE MOVILIDAD Y TRANSPORTE DEL ESTADO DE CHIAPAS | 4 | as first published, then each reform: 29 October 2020 to 6 February 2026 |
| `ley-de-municipalizacion/` | LEY DE MUNICIPALIZACION PARA EL ESTADO DE CHIAPAS | 1 | as first published: 11 May 2017 |
| `ley-de-obra-publica/` | LEY DE OBRA PUBLICA DEL ESTADO DE CHIAPAS | 8 | as first published, then each reform: 1 August 2013 to 30 April 2026 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA DEL ESTADO DE CHIAPAS | 1 | as first published: 23 September 2023 |
| `ley-de-pesca-y-acuacultura-sustentable/` | LEY DE PESCA Y ACUACULTURA SUSTENTABLE PARA EL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 14 May 2009 to 9 October 2025 |
| `ley-de-planeacion/` | LEY DE PLANEACION PARA EL ESTADO DE CHIAPAS | 8 | as first published, then each reform: 18 March 2005 to 6 July 2023 |
| `ley-de-presupuesto-contabilidad-y-gasto-publico-municipal-ch/` | LEY DE PRESUPUESTO, CONTABILIDAD Y GASTO PUBLICO MUNICIPAL, CHIAPAS | 1 | as first published: 5 May 2020 |
| `ley-de-procedimientos-administrativos/` | LEY DE PROCEDIMIENTOS ADMINISTRATIVOS PARA EL ESTADO DE CHIAPAS | 7 | as first published, then each reform: 31 December 2007 to 20 August 2020 |
| `ley-de-propiedad-en-condominio-de-inmuebles/` | LEY DE PROPIEDAD EN CONDOMINIO DE INMUEBLES PARA EL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 29 September 2011 to 1 January 2016 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 19 June 2025 to 18 June 2026 |
| `ley-de-proteccion-de-monumentos-y-sitios/` | LEY DE PROTECCION DE MONUMENTOS Y SITIOS DEL ESTADO DE CHIAPAS | 1 | as first published: 12 October 1972 |
| `ley-de-proteccion-para-la-fauna-en-el-estado-de-chiapas/` | LEY DE PROTECCION PARA LA FAUNA EN EL ESTADO DE CHIAPAS | 2 | as first published, then each reform: 6 July 1995 to 16 May 2014 |
| `ley-de-residuos-solidos/` | LEY DE RESIDUOS SOLIDOS PARA EL ESTADO DE CHIAPAS Y SUS MUNICIPIOS | 1 | as first published: 20 June 2019 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE CHIAPAS Y SUS MUNICIPIOS | 1 | as first published: 1 January 2024 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS PARA EL ESTADO DE CHIAPAS | 5 | as first published, then each reform: 15 July 2017 to 5 February 2026 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE CHIAPAS | 17 | as first published, then each reform: 13 August 1998 to 28 August 2025 |
| `ley-de-seguridad-privada/` | LEY DE SEGURIDAD PRIVADA PARA EL ESTADO DE CHIAPAS | 1 | as first published: 12 December 2013 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE CHIAPAS | 3 | as first published, then each reform: 19 June 2025 to 18 June 2026 |
| `ley-de-turismo/` | LEY DE TURISMO PARA EL ESTADO DE CHIAPAS | 3 | as first published, then each reform: 1 January 2022 to 4 June 2026 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
