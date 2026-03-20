# SDM Lab Talk — Speaker Script
**Work in Progress · March 2026**

---

## SLIDE 1 — Título

Gracias por estar aquí. Hoy les voy a contar sobre un paper en progreso — estamos construyendo un instrumento para medir Scientific Decision-Making en managers, lo validamos, y lo desplegamos a escala en empresas reales. Tienen tres cosas que llevarse: el instrumento, lo que aprendimos validándolo, y cuatro patrones que emergieron cuando lo usamos en campo.

---

## SLIDE 2 — Motivación

El punto de partida es simple. Sabemos que el SDM — razonar causalmente, evaluar evidencia, actualizar creencias — mejora la calidad de decisiones y el aprendizaje organizacional. Camuffo y colegas lo han demostrado experimentalmente. Pero todo eso se hace en laboratorio, con tratamientos puntuales. No existe un instrumento para medirlo fuera de esos experimentos — para decir: este manager tiene más SDM que aquel. Eso es lo que construimos.

---

## SLIDE 3 — Preview de resultados

Antes de entrar en los detalles, les digo adónde vamos. Tenemos dos contribuciones. C1: el instrumento — 24 ítems, 3 dimensiones, validado con 5 criterios complementarios, desplegado en 61 empresas. C2: lo que descubrimos al desplegarlo — cuatro patrones sobre cómo varía el SDM entre personas, dentro de jerarquías, y qué predice. Los voy a llevar por cada uno.

---

## SLIDE 4 — Constructo: 3 dimensiones

El SDM tiene seis pasos teóricos que agrupamos en tres dimensiones. Causal Reasoning — diagnosticar el problema, construir modelos causales, formular hipótesis. Evidence Evaluation — diseñar tests, recolectar evidencia, buscar señales disconfirmatorias. Y Adaptive Learning — actualizar creencias en proporción a la evidencia. Cada dimensión es necesaria y ninguna sustituye a la otra — un manager puede ser muy bueno en razonamiento causal y pésimo actualizando sus creencias cuando la evidencia lo contradice. Esta es una escala formativa: las dimensiones definen el SDM, no lo reflejan.

---

## SLIDE 5 — Desarrollo del instrumento

¿Cómo llegamos a los 24 ítems? Partimos de 40 candidatos. Cuatro etapas de refinamiento. S1: usamos ChatGPT para verificar que cada ítem identificara correctamente el polo científico. S2: 16 investigadores de SDM, asignados aleatoriamente a evaluar los ítems desde el polo científico o el opuesto — eliminamos 8 y redujimos la escala de 7 a 5 puntos para reducir carga cognitiva. S3: un experimento de nudge con 462 managers — eliminamos los ítems que no detectaban el cambio. Resultado: 24 ítems, menos de 10 minutos, desplegable a escala.

---

## SLIDE 6 — Estructura del survey

El survey tiene tres bloques. Bloque 1: los 24 ítems de SDM — formato bipolar, ambos polos son comportamientos plausibles de un manager, lo que reduce el sesgo de deseabilidad social. Bloque 2: 6 vignettes — escenarios de negocio con respuesta objetivamente correcta, completamente independientes de la escala. Bloque 3: demografía — tenure, educación, nivel jerárquico. Quiero que noten la separación: el SDM se mide por auto-reporte, las vignettes lo validan desde afuera.

---

## SLIDE 7 — Validación: los 5 criterios

Para una escala formativa no basta con un solo test. Usamos 5 criterios complementarios. Uno: validez de contenido — panel de expertos. Dos: no-redundancia — VIF para cada ítem. Tres: sensibilidad experimental — ¿detecta cambio causal? Cuatro: distinguibilidad estructural — ¿las 3 dimensiones son estadísticamente distintas? Cinco: predicción comportamental — ¿predice desempeño en una tarea objetiva? Cada criterio tiene su backup slide si lo necesitan.

---

## SLIDE 8 — Criterio 3: El experimento

El criterio más fuerte es el experimento. 462 managers asignados aleatoriamente a tres condiciones: científica, intuitiva, control. Primero les muestro el balance — los grupos son comparables en edad, género, educación, tenure. Todo bien. *[click]* Ahora los resultados. La condición científica supera al control por d = 1.40 — un efecto enorme, más de una desviación estándar. Contra la condición intuitiva, d = 2.09. Esto me dice que el instrumento detecta algo real: es sensible a cambios causales en el tipo de razonamiento.

---

## SLIDE 9 — Field sample

Con el instrumento validado, lo desplegamos. 9,458 managers, 61 empresas, 5 niveles jerárquicos. Principalmente italianas, tamaño medio-grande. Distribución jerárquica normal — el tier más numeroso es frontline con 4,254 personas, el más pequeño es top management con 554.

---

## SLIDE 10 — Pattern 1: ICC

Primer hallazgo. El 99% de la varianza en SDM está entre personas — no entre empresas. Los ICC son todos menores al 1.1%. Trabajes en Bayer o en una PYME, da casi igual. El SDM es un constructo individual, no organizacional.

> **Si preguntan:** el tier de Upper Management llega al 5.01% — justo en el umbral, pero el 95% de la varianza en ese tier sigue siendo individual. El overall de 1.1% refleja todos los tiers combinados.

---

## SLIDE 11 — Pattern 2: Gradiente jerárquico

Segundo hallazgo. Los managers de nivel más alto tienen, en promedio, mayor SDM. El gradiente es monotónico y sobrevive fixed effects de firma y controles. La variable que mejor captura el efecto es la distancia estructural al CEO — r = −.072 — más que el tier categórico. Lo que importa es la proximidad a la cima, no el nivel nominal.

> **Si preguntan:** cuando tiers y layers2ceo entran juntos al modelo, tiers se vuelve marginal. layers2ceo está conduciendo el resultado.

---

## SLIDE 12 — Pattern 2 (cont.): Asimetría dimensional

Pero el gradiente no es uniforme entre dimensiones. Adaptive Learning es la que más sube con la jerarquía — Δ = .19. Evidence Evaluation es plana — Δ = .02, no significativa. Y el tenure muestra el patrón espejo: CR y EE bajan con la antigüedad — entrenchment — pero AL no (r = −.008, n.s.). AL es la dimensión que responde a la exposición jerárquica y se mantiene estable con la experiencia. Eso dice algo sobre qué forma cada dimensión.

---

## SLIDE 13 — Pattern 2: No es selección

La pregunta obvia: ¿no será que las empresas simplemente promueven a los más científicos? El 2×2 lo descarta. El 47% de los top managers está por debajo de la mediana de SDM. El 49% de frontline está por encima. Chi² = 2.70, p = .10 — no significativo.

Lo corremos con tres operacionalizaciones — T1 vs T5, T1+T2 vs T4+T5, y CEO vs 5+ capas — todos dan lo mismo. El gradiente existe, pero no porque solo asciendan los mejores. La exposición sostenida a decisiones complejas parece ser el mecanismo.

---

## SLIDE 14 — Pattern 3: Vignettes

Tercer hallazgo. El SDM predice calidad de decisión en una tarea independiente. Y digo independiente con propósito: el SDM es auto-reporte, la crítica obvia es social desirability. Las vignettes son la respuesta — 6 escenarios de negocio con respuesta correcta objetiva, no gameable. El quintil más alto acierta el 55%. El más bajo, el 44%. Beta = .12, estable en 4 especificaciones.

**Lo que esto prueba:** el instrumento mide algo real con consecuencias comportamentales — no solo autopercepción.

**Lo que no prueba:** que un training en SDM causalmente mejore las decisiones. Eso requeriría un experimento pre/post. Y sabemos del lab que los efectos de training se van olvidando — no es algo que coges una vez y ya.

---

## SLIDE 15 — Pattern 4: Firma

Cuarto hallazgo, exploratorio. ¿El SDM individual agrega a nivel de firma? Hay una señal. Empresas con mayor SDM promedio tienen mayor precisión colectiva — b = .277, p = .013, R² = .107. La dispersión no importa — lo que importa es el nivel, no cuán desigual está distribuido. Pero esto es N = 57 empresas — es exploratorio.

---

## SLIDE 16 — Limitaciones

Cuatro limitaciones que nombro yo antes de que las nombren ustedes. Uno: cross-seccional — no puedo establecer causalidad en los patrones de campo. Dos: instrumento y vignettes los diseñó el mismo equipo — hay circularidad parcial. Tres: no administramos AOT ni NFC — faltan las correlaciones con los constructos más cercanos. Cuatro: las empresas se auto-seleccionaron — probablemente comprimen la cola baja.

---

## SLIDE 17 — Contribuciones

Para cerrar. SDM pasa de ser un tratamiento experimental a ser una característica observable. C1: primer instrumento validado para medirlo a escala. C2: cuatro patrones tempranos sobre cómo varía y qué predice. La pregunta que queda: ¿qué diseños organizacionales forman el SDM? Los patrones sugieren que la exposición sostenida importa más que el entrenamiento puntual. Eso lo estamos empezando a explorar.

Gracias — tengo backup slides para todo.

---

*Última actualización: marzo 2026*
