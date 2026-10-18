# Registro de IA y prompts (punto 5 del enunciado)

El enunciado pide citar la IA consultada y utilizada, con la lista de prompts. Este archivo es ese registro para la parte de animación; completar con el resto del grupo lo que se haya usado para el texto.

## IA utilizada

| Herramienta | Para qué | Prompt |
|---|---|---|
| Claude Code (Sonnet 5.5) | Armar este repositorio, convertir los documentos a Markdown, investigar cómo promptear animación vectorial y redactar el prompt 1 | Pedido en lenguaje natural: preparar el entorno para trabajar con Claude Design desde el repo y redactar un prompt de animación vectorial de las 7 iglesias, tomando como referencia un ejemplo de evolución de la ciencia en Europa |
| Claude Design | Generar la animación vectorial | [`01-claude-design-animacion.md`](01-claude-design-animacion.md) |
| _completar_ | _otras IA que haya usado el grupo para el texto_ | _completar_ |

## Fuentes consultadas para redactar el prompt

Todas son de terceros salvo la primera; se usaron solo para la forma de promptear (estructura, proceso, iteración), no para el contenido bíblico.

- Anthropic, [Introducing Claude Design by Anthropic Labs](https://www.anthropic.com/news/claude-design-anthropic-labs): qué es Claude Design, entradas aceptadas, refinado por chat/comentarios y exportación.
- Why Try AI, [I Tried Claude Design's Animations. They Just Work.](https://www.whytryai.com/p/claude-design-animations): flujo Animation → entrevista → mejora por capítulos.
- XRAY, [Build fluid on-brand animations with Claude Design](https://www.xray.tech/post/build-fluid-on-brand-animations-with-claude-design): resolución y duración en el primer prompt, describir cómo entran, se mueven y se asientan los elementos, exportación a MP4.
- rar.design, [Claude Opus 5.5 animation guide](https://rar.design/posts/claude-opus-5-5-animation-guide): restricciones de renderizado, animación determinista por tiempo, bucle de control de calidad.
- AI IDE List, [Opus 5.5 Motion Design: 20+ prompts](https://aiidelist.com/blog/opus-5-5-motion-design): plantilla de nueve capas (rol, objetivo, formato, historia, dirección de arte, lenguaje de movimiento, negativos, técnica, QA) y prompts de mapas y documentales.
- Grow With AI, [Claude makes the best motion graphics I've ever seen](https://growwithaiguide.substack.com/p/claude-makes-the-best-motion-graphics): puertas de proceso (storyboard y un fotograma por escena antes de construir) y pasada de autocrítica.

## Limitaciones declaradas

- No se encontró el ejemplo de «evolución de la ciencia en Europa» que se quería usar como referencia. El prompt adopta de ese tipo de piezas el recurso de una línea de tiempo continua con transformaciones entre épocas, pero no se basa en ese ejemplo concreto.
- Las guías consultadas son de terceros y no oficiales de Anthropic.
