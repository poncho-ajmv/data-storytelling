# 07 · Descubrimiento de historias y selección de hallazgos

**Fuente:** Brent Dykes, *Effective Data Storytelling* (Wiley, ©2020), cap. 1, PDF pp. 29–37; cap. 4, pp. 107–109, 139–143; cap. 5, pp. 146–183; cap. 6, pp. 196–198. Complementa Knaflic, cap. 1 y 8. Referencias a páginas del PDF de 413 páginas, no de la edición impresa. Traducciones terminológicas propias; procedimientos, fichas y ejemplos son adaptaciones operativas.

## 1. Determinar si hace falta una historia

Dykes diferencia **storyframing** (encuadrar datos para que puedan emerger hallazgos) de **storytelling** (explicar un hallazgo específico mediante narrativa y visualizaciones explicativas). El encuadre es válido en tableros, informes de seguimiento y preguntas exploratorias; no hace falta imponer una conclusión. La transición se produce cuando hay un hallazgo central significativo que merece ser comprendido por alguien.

No confundir dato con hallazgo. Una cifra aislada informa; una observación identifica algo notable; un hallazgo cambia la comprensión de un asunto al situar el dato y su relación en contexto. Puede llevar a una acción, pero esta no debe anticiparse a la evidencia. Dykes describe la cadena de valor analítica: datos → información → hallazgo → decisión → acción (fig. 1.2, p. 33). El valor solo se materializa cuando una decisión y una acción apropiadas producen resultados; la skill no promete que suceda.

### Zona de historia (Story Zone)

Cruza dos dimensiones: valor potencial del hallazgo y dificultad de comprensión o aceptación. La zona en que una historia completa suele aportar más es **valor medio/alto + hallazgo difícil de comprender o aceptar** (fig. 4.17, p. 142). Dificultad aumenta si el resultado es incómodo, inesperado, contraintuitivo, complejo, costoso o arriesgado. Si es simple y fácil de aceptar, una cifra contextualizada o un gráfico pueden bastar aunque su valor sea alto. Si es trivial, no alargues el relato. Si hay duda sobre su validez, investiga primero. Esta regla no autoriza manipular a una audiencia ni ocultar evidencia adversa.

## 2. Marco 4D (Four Dimensions Framework)

Dykes, cap. 5, pp. 152–157, figs. 5.2–5.3. Define las cuatro dimensiones **para una audiencia concreta**:

| Dimensión | Pregunta | Evidencia requerida |
|---|---|---|
| Problema (Problem) | ¿Qué desafío actual quiere resolver? | Estado actual, síntomas y consecuencias verificadas |
| Resultado (Outcome) | ¿Qué estado futuro busca? | Objetivo, referencia, horizonte; si no existe, marcarlo como desconocido |
| Acciones (Actions) | ¿Qué iniciativas o palancas ya está usando? | Programas, decisiones, actividades o cambios confirmados |
| Medidas (Measures) | ¿Cómo sabe si progresa? | Definición, unidad, fuente, periodo, población, denominador y fórmula de indicadores |

El marco ayuda a formular preguntas pertinentes, no es un sistema para forzar un problema en toda solicitud. Ejemplo sintético: equipo de atención, problema = tiempos de espera; resultado = SLA acordado; acciones = nuevo enrutamiento y turnos; medidas = mediana, percentil 90 y porcentaje dentro del SLA. Si el SLA no fue proporcionado, no inventarlo. El marco no demuestra que el enrutamiento causó un cambio.

## 3. Protocolo de descubrimiento (adaptación)

1. Establecer 4D y la tarea de la audiencia. Registrar qué no se sabe.
2. Revisar calidad: periodo, cobertura, granularidad, universo, nulos, duplicados, unidades, cambios de definición, representatividad y procedencia. Si falla algo crítico, limitar la conclusión.
3. Formular hipótesis y preguntas no sesgadas. No buscar solo evidencia favorable a una hipótesis previa.
4. Explorar visualmente con las familias de puntos narrativos de `08-arquitecturas-narrativas.md`: cambio temporal, relación, cruce, proyección, comparación, desglose, ampliación de contexto, agrupación y anomalía. Usar únicamente las compatibles con los datos.
5. Comparar con una referencia válida: periodo comparable, meta real, población o categoría equivalente. Revisar valores absolutos y relativos, bases y excepciones.
6. Investigar qué explica la observación. Una asociación es una hipótesis, no causa. Si la causa es desconocida, declararla y plantear qué comprobar.
7. Evaluar candidatos con los seis atributos de accionabilidad del módulo 13. Elegir uno central; si dos son independientes, separarlos en historias o secciones. No ocultar hallazgos materiales que contradigan el principal.
8. Congelar una ficha de evidencia y pasar a diseño explicativo. Volver a exploración si al diseñar aparece una inconsistencia.

## 4. Tres desviaciones que evitar

Dykes, cap. 5, pp. 161–168, figs. 5.4–5.8:

- **Data cut** (recorte de datos): hubo análisis, pero se entrega una colección de resultados sin formar una historia; volver a seleccionar y organizar.
- **Data cameo** (aparición puntual de datos): se parte de una historia predeterminada y se buscan cifras que la decoren; reiniciar desde la evidencia y considerar resultados contrarios.
- **Data decoration** (decoración con datos): se invierte en visuales sin suficiente análisis o dirección narrativa; verificar el hallazgo y luego decidir qué visual aporta comprensión.

Si el usuario realmente solicita exploración o consulta, no califiques un tablero de búsqueda como recorte defectuoso: responde al objetivo explícito.

## 5. Ficha de hallazgo candidato

- Identificador y pregunta de negocio.
- Dato(s) exacto(s), fórmula, fuente y periodo.
- Patrón observado y referencia de comparación.
- Interpretación sustentada y explicación alternativa.
- ¿Qué cambió en la comprensión? ¿A quién le importa?
- Incertidumbre y evidencia faltante.
- Acción disponible o discusión requerida; impacto conocido o estimado con supuestos explícitos.
- ¿Merece una historia? Decisión: central / soporte / anexo / exploración pendiente.

## 6. Ejemplo de aplicación

Datos ficticios: ventas 120 mil, devoluciones 12 mil y ventas netas 108 mil en junio; en mayo ventas 115 mil, devoluciones 5 mil, netas 110 mil. Una primera observación es que ventas brutas aumentaron 5 mil (+4,35 %). Al comparar netas, aparece el hallazgo: bajaron 2 mil (−1,82 %), pues las devoluciones observadas aumentaron 7 mil. El cambio es una identidad contable, no una prueba de por qué hubo devoluciones. La historia puede concentrarse en el deterioro de ventas netas y el análisis de devoluciones por producto y motivo. No atribuirlo a calidad sin datos de causa. Audiencia comercial versus financiera cambia el detalle del siguiente paso.
