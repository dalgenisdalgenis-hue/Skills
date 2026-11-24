# Investigación académica bilingüe (ES / EN)

Skill para Claude que acompaña todo el ciclo de un trabajo académico en **español** (idioma principal) e **inglés**: investigar, planificar, redactar, humanizar, revisar y entregar.

> Copiloto, no piloto: el autor toma las decisiones.

## Modos

| Modo | Para qué sirve |
|---|---|
| Investigación | Buscar y sintetizar fuentes con palabras clave en ES y EN |
| Revisión de literatura | Narrativa, sistemática (tipo PRISMA) o de alcance |
| Socrático | Afinar la pregunta o la tesis mediante preguntas |
| Planificación | Objetivos, hipótesis y esquema (IMRyD, ensayo, tesis) |
| Redacción | Borradores por secciones con citas marcadas |
| **Humanización** | Calibración de tu estilo + control de patrones típicos de IA |
| Revisión por pares | Comité simulado con abogado del diablo |
| Citas | Verificar existencia y correspondencia; APA, MLA, Chicago, IEEE, Vancouver |
| Flujo completo | 10 etapas con confirmación del autor en cada una |

## Humanización

- **Calibración de estilo:** comparte textos tuyos y la skill aprende tu voz (ritmo, persona gramatical, conectores, nivel de cautela).
- **Control de calidad de escritura:** elimina muletillas en español ("cabe destacar que", "juega un papel crucial"…) y en inglés ("delve into", "it is important to note"…), además de patrones estructurales repetitivos.

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

## Integridad académica

No inventa fuentes, datos ni resultados. Revisa las normas de tu institución o revista sobre el uso de IA.

## Créditos

Inspirada en la estructura de [Academic Research Skills](https://github.com/imbad0202/academic-research-skills) (imbad0202). El texto de esta skill es original.
