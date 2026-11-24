# Investigación académica bilingüe (ES / EN)

Skill para Claude que acompaña todo el ciclo de un trabajo académico en **español** (idioma principal) e **inglés**: investigar, planificar, redactar, humanizar, revisar y entregar.

> Copiloto, no piloto: el autor toma las decisiones.

## Modos

| Modo | Para qué sirve |
|---|---|
| Investigación | Buscar y sintetizar fuentes con palabras clave en ES y EN; versión rápida y verificación de datos |
| Revisión de literatura | Narrativa, sistemática (tipo PRISMA) o de alcance |
| Socrático | Afinar la pregunta o la tesis mediante preguntas |
| Planificación | Objetivos, hipótesis y esquema (IMRyD, ensayo, tesis) |
| Redacción | Borradores por secciones con citas marcadas |
| **Humanización** | Calibración de tu estilo + control de patrones típicos de IA |
| Revisión por pares | Comité simulado con abogado del diablo; modos rápida, solo metodología y segunda revisión |
| Citas, APA 7 e integridad | Verificar las citas, revisar el formato APA 7 regla por regla (con las convenciones en español) y aplicar controles de integridad antes de entregar |
| Flujo completo | 10 etapas con confirmación del autor en cada una; se puede empezar con un borrador o con observaciones ya recibidas |
| **Metodología** | Enfoques o rutas (cuanti, cuali, mixta), planteamiento, preguntas, objetivos, alcance, hipótesis, variables y su operacionalización, diseños, población y muestra (con cálculo), instrumentos, análisis estadístico y cualitativo, y matriz de consistencia |
| **Respuesta a revisores** | Plan de revisión, matriz de trazabilidad y carta de respuesta punto por punto para revistas o para el jurado de tesis |

## Humanización

- **Calibración de estilo:** comparte textos tuyos y la skill aprende tu voz (ritmo, persona gramatical, conectores, nivel de cautela).
- **Método de 8 pasadas:** estructura de plantilla, lenguaje inflado, vocabulario típico de IA, patrones gramaticales, ritmo y puntuación, relleno y artefactos de chatbot, conectores repetidos y textura humana. Con ejemplos en español e inglés.

El objetivo es la calidad y la voz propia, no ocultar el uso de IA.

## Instalación

### Claude (claude.ai / app)
1. Comprime la carpeta `investigacion-academica-bilingue` en un `.zip`.
2. Ve a **Configuración → Capacidades → Skills** y sube el `.zip`.

### Claude Code
Copia la carpeta en `~/.claude/skills/` (o en `.claude/skills/` de tu proyecto):

```bash
git clone https://github.com/dalgenisdalgenis-hue/Skills.git
cp -r Skills/investigacion-academica-bilingue ~/.claude/skills/
```

## Uso

Pídelo con naturalidad:
- "Investiga el estado del arte sobre…"
- "Humaniza este párrafo, aquí tienes dos textos míos para que copies mi estilo"
- "Revisa mi artículo como si fueras evaluador de una revista"
- "Verifica las citas de este capítulo"

## Fuentes de la sección de metodología

Síntesis original basada en Hernández-Sampieri y Mendoza (2018), *Metodología de la investigación: Las rutas cuantitativa, cualitativa y mixta*, y en Hernández Sampieri, Fernández y Baptista (1991). No reproduce el texto de las obras.

## Integridad académica

No inventa fuentes, datos ni resultados. Revisa las normas de tu institución o revista sobre el uso de IA.

## Créditos

Inspirada en la estructura de [Academic Research Skills](https://github.com/imbad0202/academic-research-skills) (imbad0202). El método de humanización está adaptado de [humanize-writing](https://github.com/jpeggdev/humanize-writing) (jpeggdev, MIT). El resto del texto es original.
