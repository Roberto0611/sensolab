---
title: Sensolab — Plataforma de Panelistas
format: 1920x1080
fps: 30
duration: 55
music: none
language: es
status: animated
---

# Storyboard

**Dirección de arte:** sin degradados ni texturas. Cada escena es un **campo de color
pleno** que entra con un wipe diagonal de 0.45s (`expo.out`), de modo que el cambio de
pantalla se ve. Sobre el campo va una cuña de color saturado que deriva durante toda
la escena, así que ningún fotograma queda quieto. Tipografía Inter 900 en versales,
tracking −0.042em, revelada con máscara (`yPercent 105 → 0`). Ninguna entrada dura más
de 0.52s y no hay un solo fundido lento en el corte.

Los actos se **solapan ~0.6s**: el campo del acto entrante barre por encima del
saliente y este se limpia bajo la cobertura, así que el corte es un wipe duro.

Rail de marca persistente arriba a la izquierda y barra de progreso blanca abajo;
ambos se retiran a los 47.4s para dejar limpio el cierre.

---

## Frame 01 — Gancho · 0–8.6s

- **archivo:** `compositions/01-gancho.html`
- **color:** campo `#0b1416`, cuña `#ff5a1f`
- **rol:** hook — agitar el problema antes de nombrar la solución
- **persuasión:** Pain agitation → Negative contrast
- **estado:** animated

| t     | Beat                                                                     |
| ----- | ------------------------------------------------------------------------ |
| 0.00  | El campo tinta barre desde la izquierda; la cuña naranja entra desde la derecha |
| 0.30  | Chip "PROPUESTA PARA SENSOLAB"                                           |
| 0.55  | "Convocar por WhatsApp" entra y se tacha                                 |
| 1.00  | "Agendar en Excel" entra y se tacha                                      |
| 1.45  | "Certificar en papel" entra y se tacha                                   |
| 2.45  | Los tres problemas salen hacia arriba de golpe                           |
| 2.95  | Titular en tres líneas: "LA EVALUACIÓN / SENSORIAL ES CIENCIA. / **SU GESTIÓN TAMBIÉN.**" |
| 3.55  | Barra naranja bajo el titular                                            |
| 3.95  | Promesa: "que el panelista se registre, se agende y se certifique solo"  |
| 8.20  | El acto se limpia bajo el wipe del acto 2                                |

---

## Frame 02 — Demo del prototipo · 8–38.6s

- **archivo:** `compositions/02-demo.html`
- **rol:** show-don't-tell — el prototipo real
- **persuasión:** Show-don't-tell proof → Friction reduction
- **estado:** animated
- **assets:** `screen-user.png`, `screen-catalogo.png`, `screen-acreditaciones.png`, `screen-home.png`

**El mecanismo central:** el teléfono **no se mueve entre segmentos** — el campo de
color cambia *detrás* de él con un wipe, y la pantalla interior se intercambia con un
empujón lateral más un rebote de escala (1 → 0.968 → 1) que imita un flick real.
Dentro de cada segmento la captura hace **scroll auténtico de 5.2s** sobre la página
completa capturada a 2x. El teléfono respira en `rotationY` entre −6° y +6°.

| Segmento | t local | Campo / cuña | Pantalla | Titular | Callout | Scroll |
| -------- | ------- | ------------ | -------- | ------- | ------- | ------ |
| 01 Registro y perfil | 0–7.5   | `#00343b` / `#00e0c8` | `screen-user.png`           | "SE DA DE ALTA / **SOLO.**"             | Perfil sensorial verificado | −700px  |
| 02 Próximas pruebas  | 7.5–15  | `#331500` / `#ff6b00` | `screen-catalogo.png`       | "SE AGENDA / **EN UN TOQUE.**"          | Cupo reservado al instante  | −740px  |
| 03 Certificaciones   | 15–22.5 | `#00243d` / `#00a8ff` | `screen-acreditaciones.png` | "VE SUS / **ACREDITACIONES.**"          | Protocolo ISO 13299         | −1320px |
| 04 Mis paneles       | 22.5–30 | `#0b1416` / `#ff5a1f` | `screen-home.png`           | "SABE DÓNDE / **ESTÁ PARADO.**"         | 14 paneles realizados       | −680px  |

Cadencia interna (offset local): `+0.00` wipe de color + intercambio de pantalla ·
`+0.15` número de paso · `+0.28` titular en dos líneas enmascaradas · `+0.82` una
sola nota · `+0.95` arranca el scroll · `+2.40` badge blanco junto al teléfono ·
`+5.90` badge sale · `+6.62` la columna de texto sale hacia arriba.

Un numeral gigante (01–04) al 10% de blanco cambia con cada segmento y deriva de fondo.

---

## Frame 03 — Propuesta de valor · 38–48.6s

- **archivo:** `compositions/03-valor.html`
- **color:** campo `#00343b`; una tarjeta por color: `#00e0c8`, `#ff6b00`, `#00a8ff`
- **persuasión:** **Rule of three** → Value stacking
- **estado:** animated

| t     | Beat                                                                |
| ----- | ------------------------------------------------------------------- |
| 0.00  | Campo teal barre el demo; banda oscura entra desde la derecha       |
| 0.25  | "LO QUE GANA SENSOLAB"                                              |
| 0.35  | "TRES GANANCIAS INMEDIATAS."                                        |
| 0.72  | Tarjeta 01 **Eficiencia operativa** sube desde abajo (aqua)         |
| 1.50  | Tarjeta 02 **Fidelización** (naranja)                               |
| 2.28  | Tarjeta 03 **Control de datos** (azul)                              |
| 3.40  | Síntesis: "más grande, mejor calificado y mejor documentado"        |
| 9.65  | Las tres tarjetas caen hacia arriba escalonadas                     |

Cada tarjeta es un bloque de color pleno con su propio numeral gigante detrás: la
regla de tres se *entrega* en tres golpes de 0.78s, no se lista.

---

## Frame 04 — Cierre · 48–55s

- **archivo:** `compositions/04-cierre.html`
- **color:** campo `#0b1416` con cuña `#ff5a1f` a la izquierda y `#00e0c8` a la derecha
- **estado:** animated
- **assets:** `logo-sensolab.png`

| t     | Beat                                                          |
| ----- | ------------------------------------------------------------- |
| 0.00  | Campo tinta + las dos cuñas de marca entran desde ambos bordes |
| 0.35  | Logotipo SensoLab Solutions aterriza                          |
| 0.85  | Regla blanca se dibuja desde el centro                        |
| 1.05  | "PLATAFORMA DE PANELISTAS"                                     |
| 1.45  | CTA blanco: "Agendemos una demo"                              |
| 1.95  | Pie: Registro · Pruebas · Certificaciones · Paneles           |
| 2.20  | Las cuñas siguen cerrándose sobre el centro hasta el final    |

## Video direction

- **Ritmo:** un beat visible cada 0.3–0.8s. Se eliminaron todos los holds largos del
  corte anterior (push-in de 3.8s, asentamiento de 7.6s, respiraciones dobles del CTA).
- **Movimiento:** todo entra desde abajo o desde la derecha y sale hacia arriba.
  `expo.out` en las entradas, `power3.in` en las salidas.
- **Color:** el campo cambia en cada pantalla y **nunca se funde** — siempre wipe.
  El cian/aqua es la plataforma, el naranja es la acción.
- **Lo que no se toca:** el scroll real del prototipo dentro del mockup — es la prueba
  del producto y el beat más largo que conserva el corte.
