# TP Interpretación Bíblica de la Historia — Las 7 Iglesias (Apocalipsis 2 y 3)

Trabajo práctico grupal del **Grupo 1**. Exposición: **19 de octubre**. Este repositorio sirve de insumo para generar con **Claude Design** una animación vectorial de las siete iglesias, que acompaña la exposición.

> **Si sos Claude Design:** este archivo es tu brief. Leelo completo, después `datos/iglesias.json` (contenido) y por último `prompts/01-claude-design-animacion.md` (el pedido). No necesitás nada más.

## 1. Qué hay que producir

Una pieza animada de **3:00**, **16:9 (1920×1080)**, **100 % vectorial (SVG)**, como un **único archivo HTML autocontenido**, exportable a **MP4**.

Tiene que cubrir, para cada iglesia, los tres primeros puntos del enunciado (los que lleva el PPT):

1. De qué habla la carta.
2. Sus símbolos y su interpretación.
3. La lección espiritual.

## 2. Fuentes de verdad (reglas de contenido)

| Archivo | Uso |
|---|---|
| `datos/iglesias.json` | **Única fuente de contenido de la animación.** Todo texto visible sale de acá. |
| `contenido/tp-completo.md` | El TP completo (Éfeso a Laodicea). Si hay conflicto con el JSON, **prevalece este archivo**. |
| `contenido/tp-parte-sardis-laodicea.md` | Borrador de otra parte del grupo (Sardis, Filadelfia, Laodicea). Está duplicado dentro de `tp-completo.md`; solo sirve de referencia. |
| `contenido/enunciado.md` | Consigna del TP. |
| `materiales/` | Originales (`.docx` y `.pdf`). No usar para extraer contenido: usar los `.md`. |

Reglas:

- **No inventes** fechas, nombres, versículos ni interpretaciones. Si falta algo, preguntá.
- Las citas bíblicas y de Ellen G. White van **literales**, tal como están en el JSON.
- Las fechas de cada período son aproximadas, y así se tienen que mostrar (por ejemplo «c. 30 d.C.»).
- Hay tres puntos que el equipo debe confirmar. Si no están confirmados, usá lo que dice el JSON y dejalo señalado:
  - Sardis: el TP dice 1517/1565 a 1740/1798; el JSON usa 1517-1798.
  - Filadelfia: el TP no escribe el rango de versículos; el JSON usa 3:7-13.
  - Laodicea: la fecha de inicio (1844) se deduce del fin de Filadelfia.

## 3. Hilo visual

Una sola idea sostiene toda la pieza: **un edificio vectorial que muta de una iglesia a la siguiente** (morphing de paths, sin cortes), sobre un **eje de tiempo** que va de 30 d.C. al tiempo del fin. Abajo, un **riel con siete candeleros** (los «siete candeleros de oro» de Éfeso, que simbolizan las iglesias como luz en el mundo): cada llama se enciende en su capítulo y queda con un estado que refleja la condición de la iglesia (firme, mínima, casi apagada, brillante, tibia).

Cada capítulo tiene un nombre fijo para poder pedir cambios por capítulo.

## 4. Storyboard (3:00)

| Tiempo | Capítulo | Escena sugerida (usar los símbolos del JSON) |
|---|---|---|
| 0:00-0:12 | **Apertura** | Noche. Aparecen siete llamas pequeñas en fila. Título «Las siete iglesias · Apocalipsis 2 y 3». Se dibuja el eje de tiempo. El número siete: plenitud. |
| 0:12-0:32 | **Éfeso** | Fachada con columnas (ciudad de Artemisa). Una mano abstracta sostiene siete estrellas. La llama arde fuerte y se achica: «abandonaste tu primer amor». Cierre: árbol de la vida. |
| 0:32-0:52 | **Esmirna** | El edificio se vuelve humilde. Llama pequeña pero constante. Diez marcas (303-313) se apagan una por una. Aparece la corona de la vida. Sin reprensión. |
| 0:52-1:12 | **Pérgamo** | Trono/altar de piedra. Una espada de dos filos atraviesa la escena. Maná escondido y piedra blanca con un nombre nuevo. Doctrinas falsas como formas que se infiltran. |
| 1:12-1:32 | **Tiatira** | Taller de gremios y fragua. Ojos como llama de fuego, pies de bronce bruñido. «Jezabel» como seducción abstracta (sin figuras). Cierre: estrella de la mañana. |
| 1:32-1:52 | **Sardis** | Acrópolis sobre el acantilado, centinela dormido en la muralla. La llama casi se apaga: «tienes nombre de que vives, y estás muerto». Cinco señales de emergencia. Vestiduras blancas para unos pocos. |
| 1:52-2:17 | **Filadelfia** | Ruinas de terremoto que se reconstruyen. Una puerta abierta que nadie puede cerrar y una llave. Hitos 1798, 1804, 1816. **22 de octubre de 1844**: el Gran Chasco, y la puerta se abre hacia el santuario celestial. Columna en el templo. |
| 2:17-2:42 | **Laodicea** | Acueducto: el agua caliente y el agua fría se encuentran y llegan tibias. Tres objetos: oro refinado, vestiduras blancas, colirio. Una puerta con el picaporte del lado de adentro. «Yo estoy a la puerta y llamo». |
| 2:42-3:00 | **Cierre** | Las siete llamas juntas. «Al que venciere…». Las cartas no son condena: son un llamado de amor y de arrepentimiento. |

## 5. Dirección de arte

- **Estilo:** vectorial limpio, formas geométricas simples con líneas de grosor consistente. Sin fotos, sin imágenes raster, sin emojis, sin texturas de stock.
- **Paleta:** un fondo oscuro común y **un color de acento por iglesia**, todos de la misma familia de saturación para que se lean como un solo sistema. Sugerencia: Éfeso ámbar, Esmirna carmesí, Pérgamo piedra y bronce, Tiatira naranja de fragua, Sardis ceniza, Filadelfia azul abierto, Laodicea verdeazulado tibio.
- **Tipografía:** dos familias como máximo (una serif para títulos y citas, una sans para etiquetas), con soporte completo de español.
- **Texto:** máximo 12 palabras en pantalla, salvo citas bíblicas. Primero se muestra la idea y después se nombra.
- **Representación de Cristo:** solo con símbolos (luz, mano, estrellas, puerta, llave). **Nunca con rostro ni figura humana.** Tampoco personas sufriendo en Esmirna: usar las marcas, la corona y la llama.

## 6. Lenguaje de movimiento

- **Continuidad:** nada corta. Todo se transforma en lo siguiente (morphing, desplazamiento de cámara, escala).
- **Easing con intención:** entradas con resorte suave, salidas rápidas, asentamientos sin rebote excesivo.
- **El ritmo acompaña el mensaje:** Éfeso se enfría, Esmirna sostiene, Sardis se detiene, Filadelfia se abre, Laodicea se entibia.
- **Una idea por escena.** Cada escena responde una sola pregunta.

## 7. Evitar

Texto centrado con degradé y fade-in genérico, brillos de stock, palomas y cruces con resplandor, textos pegados a las esquinas, transiciones de cortina, decoración sin significado bíblico.

## 8. Requisitos técnicos

- SVG inline y JavaScript; sin imágenes externas ni dependencias que requieran red al presentar.
- Animación gobernada por un **reloj `t`**: el mismo `t` produce siempre el mismo cuadro (necesario para exportar a MP4 sin diferencias). Si hace falta azar, usar semilla fija.
- Controles: play/pausa, barra de tiempo y salto por capítulo con ← y →, para usarla en vivo frente a la clase.
- Respetar `prefers-reduced-motion`, contraste AA y que todo sea legible proyectado.

## 9. Proceso de trabajo

1. **Entrevista breve:** como máximo 3 preguntas, o decidir.
2. **Storyboard** por capítulo y **un fotograma por capítulo** para aprobar antes de construir.
3. **Construcción.**
4. **Autocrítica:** puntuar de 1 a 10 legibilidad, ritmo, fidelidad al texto y coherencia visual, y corregir lo que quede por debajo de 8. Repetir una vez.
5. **Exportación:** HTML autocontenido y MP4.

## 10. Checklist de calidad

- [ ] Los siete capítulos cubren de qué habla, símbolos y lección.
- [ ] Ningún texto, fecha ni cita difiere de `datos/iglesias.json`.
- [ ] El edificio muta sin cortes de una iglesia a la siguiente.
- [ ] Los siete candeleros se encienden en orden y su estado refleja a cada iglesia.
- [ ] Sin rostros, sin imágenes raster, sin emojis.
- [ ] Legible proyectado y con `prefers-reduced-motion` respetado.
- [ ] Dura 3:00 (±10 s) y exporta a MP4.

## 11. Entrega del TP (recordatorio)

El Campus pide el trabajo redactado en **PDF** y el **PPT en PDF**, hasta el **domingo 18 de octubre a las 23:00**. La animación es un complemento para la exposición; no reemplaza esos dos archivos. Según el punto 5 del enunciado, hay que citar la IA usada y la lista de prompts: ver [`prompts/00-registro.md`](prompts/00-registro.md).

## 12. Estructura del repositorio

```
README.md                      Brief para Claude Design (este archivo)
datos/iglesias.json            Contenido estructurado de las 7 iglesias
contenido/                     Textos convertidos a Markdown
  enunciado.md
  tp-completo.md
  tp-parte-sardis-laodicea.md
materiales/                    Originales (.docx, .pdf)
prompts/
  00-registro.md               IA usada, fuentes y limitaciones (punto 5 del enunciado)
  01-claude-design-animacion.md  Prompt para Claude Design
```
