# 15 · Biblioteca de casos y rediseños

**Fundamento:** Dykes cap. 7 (PDF pp. 236–257), cap. 8 (pp. 260–302) y cap. 9 (pp. 304–344); Knaflic caps. 2–9. Los 24 casos de la segunda sección son **sintéticos y originales de esta skill**, no casos ni datos textuales atribuidos a los autores. El libro *Antes y después* de Knaflic, Cisneros y Velez no fue aportado ni consultado íntegramente y no se usa como fuente. Los anclajes identifican los principios de los libros aportados que justifican las decisiones.

## Casos fuente de Dykes (lectura de las lecciones, no reproducción de figuras)

| Anclaje | Decisión que enseña |
|---|---|
| Fig. 1.1, p. 30 | Un histograma con dos picos invita a investigar segmentos en vez de asumir una distribución esperada. |
| Fig. 7.9–7.11, pp. 238–240 | Ejes dobles pueden esconder el significado; índices comparables o ingresos por cliente pueden contestar preguntas más precisas. |
| Fig. 7.12–7.14, pp. 241–243 | Contexto de años anteriores o diferencias calculadas puede transformar la lectura. |
| Fig. 7.21, p. 250 | Dumbbell permite comparar dos posiciones y sus diferencias por categoría. |
| Fig. 7.23–7.27, pp. 255–257 | Agrupación, base común y consistencia de paneles determinan facilidad de comparación. |
| Fig. 8.3–8.5, pp. 264–265 | Reducir, agrupar o separar series y categorías mejora lectura si preserva información material. |
| Fig. 8.12–8.15, pp. 276–280 | Títulos explicativos, anotaciones vinculadas, tipografía selectiva y capas orientan la lectura. |
| Cap. 9, figs. 9.1–9.7 | Rosling orienta al público al gráfico, utiliza referencias, hace pausas y desglosa puntos para mostrar contexto. |
| Cap. 9, figs. 9.9–9.18 | Secuencia de escenas y evidencia encadenada permiten desarrollar una historia compleja; no reproducir sus conclusiones en otros datos. |
| Cap. 9, fig. 9.19–9.21 | Un avance de datos o unas pocas comparaciones pueden orientar una decisión sin requerir una presentación extensa. |

Las descripciones en español de las figuras del TXT fueron añadidas editorialmente por quien preparó la transcripción; se usan junto con texto y pies originales, no como citas literales del autor.

## Casos sintéticos de entrenamiento

Cada caso especifica antes → después → verificación; renderizar únicamente si el usuario pide un gráfico. Todas las cantidades son ficticias. No copiar al informe del usuario.

| Nº | Datos y propósito | Antes: problema | Después: elección y narrativa | Validación y fundamento |
|---:|---|---|---|---|
| 1 | Q100, 105, 110, 94, 96, 98 mil de enero a junio; recuperación | Circular por mes | Línea; resaltar caída y recuperación incompleta, junio −Q12 mil frente a marzo | Periodos iguales; cap. 7, principios 1–2 |
| 2 | Incidencias 42 pagos, 28 acceso, 18 envíos, 12 otros | Anillo con leyenda | Barras ordenadas, pagos en acento, 42/100 | Base cero, suma 100; cap. 7, principio 2 |
| 3 | Opinión positiva 30→55 %, neutra 40→30 %, negativa 30→15 % | Dos circulares | Pendientes si interesa cambio, apiladas 100 % si interesa mezcla; +25 pp positivas | Sumas y base; sin causalidad ni significancia; caps. 5, 7 |
| 4 | Saldo 100 +40 −25 −5 =110 | Columnas sin reconciliación | Cascada de contribuciones y saldo final | Aportes netos +10; Knaflic cap. 2, Dykes cap. 7 |
| 5 | Región A 49 %, B 51 % | Barras desde 48 %, título exagerado | Barras cero o puntos con escala; diferencia 2 pp | No afirmar significancia; tabla 8.6 |
| 6 | 8 series × 12 meses, sin valores disponibles | Espagueti hipotético | Especificar paneles con escala común; pedir datos | No inventar líneas; fig. 8.5 |
| 7 | Ventas brutas 115→120, devoluciones 5→12, netas 110→108 | Solo brutas, aparente mejora | Comparación netas y puente contable; devoluciones +7 | Identidades; no causa de devoluciones; principio 1 |
| 8 | Clientes 100→120, ingresos 1000→1080 | Eje Y doble | Ingresos por cliente 10→9; acompañar niveles y contexto | Dividir unidades compatibles; figs. 7.9–7.11 |
| 9 | A 100/1000, B 20/100 | Barras de conteos para riesgo relativo | Tasas 10 % y 20 % con bases; si interesa carga total, mostrar conteos aparte | Distintas preguntas; principio 1 |
| 10 | Gastos 80 frente a meta documentada 70 | KPI sin referencia | Barra o texto «10 sobre presupuesto» con unidad y periodo | No confundir +10 con +10 %; fig. 7.12 |
| 11 | Tiempo de espera 2, 3, 3, 4, 18 min | Promedio único 6 | Puntos individuales y mediana 3; 18 es atípico descriptivo | n=5; no inferir población; cap. 6 story point outlier |
| 12 | Dos observaciones el 1 y 3 de enero, tercer punto 1 de febrero | Espaciado uniforme | Eje temporal proporcional | Evitar inferencia de ritmo falsa; tabla 8.6 |
| 13 | 4 regiones, cada una con dos productos, interés en producto dentro de región | Agrupado por producto, comparación distante | Agrupado por región; orden repetido de productos | No cambiar valores; fig. 7.23 |
| 14 | 2 series en paneles con rangos 0–100 y 0–10 | Alturas aparentan igualdad | Eje común si importa magnitud; si importa patrón, indicar escalas distintas | Interpretación explícita; fig. 7.27 |
| 15 | Distribución 3 categorías: 70 %, 20 %, 10 % | Colores arcoíris, 3D | Barras o texto «70 % corresponde a X», conservar resto | Sin profundidad ni ángulos; caps. 7–8 |
| 16 | Previsión: histórico 80, 85; futuro estimado 90 | Línea continua sin distinción | Observado sólido, estimación discontinua, etiqueta y supuestos | No prometer 90; cap. 6 project forward |
| 17 | Clientes por tamaño de compra; solo clientes activos | «Todos los clientes prefieren…» | Restringir universo a activos, solicitar abandonos | Sesgo de supervivencia; cap. 5 |
| 18 | Relación entre publicidad y ventas sin experimento | Título «La publicidad causó…» | Dispersión; «se observó asociación» y posibles factores | No inferir causalidad; pp. 172–173 |
| 19 | Producto A 75, B 60, C 20; objetivo comparar A con B | Tabla y leyenda separada | Barras adyacentes, etiqueta de brecha 15 | Base común y proximidad; pp. 253–254 |
| 20 | Norte ventas 20→25 y Sur 15→30 | «Crecieron todas las regiones» | Pendientes o dumbbell; Sur subió 15 frente a 5 de Norte | Magnitudes comparables; fig. 7.21 |
| 21 | Q10 mil de coste mensual, horizonte desconocido | «Ahorraremos Q120 mil» | «Si el gasto persiste 12 meses y se elimina, ahorro bruto potencial Q120 mil», costes pendientes | Condiciones, no garantía; pp. 201, 294–295 |
| 22 | Encuesta 8/10 satisfechos | «El 80 % de los clientes está satisfecho» | «8 de 10 encuestados satisfechos; muestra limitada» | Representatividad desconocida; cap. 5 |
| 23 | Cuatro métricas exploratorias sin objetivo | Narrativa concluyente inventada | Panel de seguimiento con definiciones y filtros; pregunta por decisión si procede | Storyframing válido; cap. 4 |
| 24 | Gráfico complejo de 3 segmentos, presentación oral | Mostrar todo y explicar ejes al final | Orientar a ejes, revelar segmentos pertinentes y cerrar con vista completa | Capas con evidencia intacta; fig. 8.15, cap. 9 |

## Ejercicio de transferencia

Para un caso nuevo: registrar audiencia y pregunta, datos y base, dificultad/valor, hallazgo candidato, alternativa visual, título, diseño antes/después, comprobación de integridad y siguiente paso. No seleccionar automáticamente el mismo gráfico de la biblioteca si el propósito cambió. Los casos son pruebas escritas de comportamiento, no resultados de evaluación de un agente desplegado.
