# Prompt 1 — Animación vectorial de las 7 iglesias (Claude Design)

- **Herramienta:** Claude Design (plantilla *Animation*)
- **Redactado con:** Claude Code, a partir de la investigación listada en [`00-registro.md`](00-registro.md)
- **Modelo / esfuerzo elegido en Claude Design:** _completar al ejecutarlo_
- **Fecha de uso:** _completar_

## Prompt (pegar tal cual en Claude Design)

```text
Sos director de motion design y animador vectorial. Quiero la pieza animada principal para la exposición del TP «Interpretación Bíblica de la Historia», Apocalipsis 2 y 3: Las 7 Iglesias.

Leé primero este repositorio de GitHub, rama master: https://github.com/osorio-cristian-wt/tp-interpetacion-biblica
- README.md: dirección de arte, storyboard y reglas. Es tu brief.
- datos/iglesias.json: única fuente de contenido. Si algo no está ahí, no lo inventes, preguntame.
- contenido/tp-completo.md: el texto completo del TP; prevalece si hay conflicto con el JSON.

QUÉ CONSTRUIR
- Animación de 3:00, 16:9, 1920×1080, 100 % vectorial (SVG), en un único HTML autocontenido, exportable a MP4.
- Un solo hilo visual: un edificio vectorial que muta por morphing de una iglesia a la siguiente (Éfeso, Esmirna, Pérgamo, Tiatira, Sardis, Filadelfia, Laodicea) sobre un eje de tiempo (30 d.C. al tiempo del fin) y un riel inferior con siete candeleros que se van encendiendo.
- Capítulos con nombre (Apertura, Éfeso, Esmirna, Pérgamo, Tiatira, Sardis, Filadelfia, Laodicea, Cierre) para poder pedirte cambios por capítulo.
- Cada capítulo cubre los tres puntos del enunciado: de qué habla la carta, sus símbolos con su interpretación y la lección espiritual.

MOVIMIENTO
- Continuidad ante todo: nada corta; todo se transforma en lo siguiente.
- Easing con intención (entradas con resorte suave, salidas rápidas) y ritmo según el mensaje: en Éfeso la llama se achica, en Sardis casi se apaga, en Filadelfia una puerta se abre, en Laodicea todo se entibia.
- Máximo 12 palabras en pantalla, salvo citas bíblicas. Primero mostrá la idea, después nombrala.

EVITÁ
Texto centrado con degradé y fade-in genérico, fotos o imágenes raster, emojis, rostros (a Cristo representalo solo con símbolos: luz, mano, estrellas, puerta), brillos de stock, palomas y cruces con resplandor, textos pegados a las esquinas.

TÉCNICA
- Animación gobernada por un reloj t (mismo t, mismo cuadro).
- Controles: play/pausa, barra de tiempo y salto por capítulo con ← y →.
- Respetá prefers-reduced-motion, contraste AA y tipografías con soporte completo de español.

PROCESO
1. Hacé como máximo 3 preguntas, o decidí vos.
2. Mostrame el storyboard por capítulo y un fotograma por capítulo antes de construir.
3. Construí.
4. Revisá tu resultado como un director de motion exigente: puntuá de 1 a 10 legibilidad, ritmo, fidelidad al texto y coherencia visual, y corregí todo lo que quede por debajo de 8.
```

## Prompts de seguimiento previstos

Se registran acá a medida que se usen (el enunciado pide la lista completa de prompts).

1. _(pendiente)_
