---
workflow: product-launch-video
flow: autonomous
storyboard: skip
subject: Plataforma digital de gestión de panelistas para Sensolab
audience: Equipo directivo y de operaciones de Sensolab (decisores de compra)
goal: Vender la propuesta — mostrar el prototipo funcionando y traducirlo en beneficio operativo
length: 55s
format: 1920x1080
language: es
style_preset: none (bloques de color plenos, tipografía display, cortes duros — registro de anuncio)
narration: none
music: none
source: prototipos HTML móviles locales (home.html, catalogo.html, acreditaciones.html, user.html)
deliverable: renders/sensolab_pitch.mp4
---

# Brief — Video de pitch Sensolab

## Qué se vende

Una plataforma que digitaliza y optimiza la experiencia del panelista de Sensolab:

1. Registro y gestión del perfil de panelista.
2. Exploración y agendamiento de próximas pruebas sensoriales.
3. Consulta de certificaciones obtenidas.
4. Historial y estado de los paneles a los que se registró.

## Estructura fijada por el cliente

| Tramo    | Acto                  | Contenido                                                            |
| -------- | --------------------- | -------------------------------------------------------------------- |
| 0–8.6s   | Gancho                | La necesidad de modernizar la gestión de evaluaciones sensoriales.   |
| 8–38.6s  | Demo del prototipo    | Recorrido animado: Registro, Pruebas, Certificaciones, Paneles.      |
| 38–48.6s | Propuesta de valor    | Eficiencia operativa · Fidelización de evaluadores · Control de datos |
| 48–55s   | Cierre                | Branding Sensolab + llamada a la acción.                             |

Los actos se solapan ~0.6s: el campo de color del acto entrante barre por encima
del saliente, así que el corte es un wipe duro y no un fundido.

## Reglas de composición

- **Regla de tres** (dispositivo de persuasión): el acto 3 entrega exactamente tres
  ganancias, entregadas de una en una, y se cierra con una síntesis de tres adjetivos
  ("más grande, mejor calificado, mejor documentado"). El acto 1 usa la misma cadencia
  en su titular de tres líneas.
- Tipografía cinética (revelado palabra a palabra) como lenguaje visual principal —
  el video es silente, así que el texto carga la narrativa.
- Los prototipos se muestran **tal cual**, capturados a 2x, dentro de un mockup de
  smartphone animado que hace scroll real sobre cada pantalla.

## Estado de audio

`hyperframes auth status`: **no autenticado**, y los motores locales (Kokoro, MusicGen)
no tienen dependencias instaladas. Proyecto marcado como silente (`music: none`,
sin `SCRIPT.md`). El video se entrega sin locución ni música; queda listo para añadir
una pista después.

## Paleta — un color por pantalla

La dirección de arte no usa degradados ni texturas de fondo: cada escena es un
campo de color pleno que **entra con un wipe diagonal**, de modo que el cambio de
pantalla se ve. Los tonos son versiones saturadas del sistema Material 3 de los
prototipos (teal `#00666d` + naranja `#924c00`).

| Escena              | Campo base | Cuña viva | Acento tipográfico |
| ------------------- | ---------- | --------- | ------------------ |
| Gancho              | `#0b1416`  | `#ff5a1f` | `#ff5a1f`          |
| Demo 01 Registro    | `#00343b`  | `#00e0c8` | `#00e0c8`          |
| Demo 02 Pruebas     | `#331500`  | `#ff6b00` | `#ffae6b`          |
| Demo 03 Certific.   | `#00243d`  | `#00a8ff` | `#6fd0ff`          |
| Demo 04 Paneles     | `#0b1416`  | `#ff5a1f` | `#ff8a3d`          |
| Valor               | `#00343b`  | tarjetas `#00e0c8` / `#ff6b00` / `#00a8ff` | `#00e0c8` |
| Cierre              | `#0b1416`  | `#ff5a1f` + `#00e0c8` | blanco  |

Tipografía: Inter 900, versales, tracking −0.042em. Todas las entradas usan
`expo.out` en 0.32–0.52s: no hay un solo fundido lento en el corte.
