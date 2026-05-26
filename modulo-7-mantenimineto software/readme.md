# Módulo 7: IA en Mantenimiento y Evolución del Software

## Información general

- Teoría: 3 puntos
- Práctica: 6 ejercicios

## Objetivos de aprendizaje

- Analizar código legado y generar documentación automática con IAs
- Detectar deuda técnica y planificar refactorizaciones con IA
- Actualizar dependencias y modernizar código con asistencia de IA
- Migrar entre frameworks y lenguajes manteniendo la funcionalidad
- Entender el mantenimiento como parte del ciclo continuo del ALM generativo

## Estructura del módulo

```text
modulo-7-mantenimiento-evolucion/
├── README.md
├── teoria/
│   ├── t7.1-analisis-codigo-legado.md
│   ├── t7.2-documentacion-automatica-deuda-tecnica.md
│   └── t7.3-actualizacion-modernizacion-codigo.md
└── meta-prompts/
    ├── p7.1-explicar-codigo-legado.md
    ├── p7.2-generar-documentacion-codigo.md
    ├── p7.3-detectar-deuda-tecnica.md
    ├── p7.4-planificar-refactorizacion.md
    ├── p7.5-actualizar-dependencias.md
    └── p7.6-modernizar-codigo.md
```
## Cómo usar este módulo

### Paso 1: Preparación

Revisa los archivos de teoría para familiarizarte con los conceptos que vas a explicar.

### Paso 2: Explicar la teoría

Cada archivo en `teoria/` contiene el contenido numerado (1, 2, 3...) para que puedas seguirlo secuencialmente. No es un guion literal: adáptalo a tu estilo y experiencia personal.

### Paso 3: Generar los ejercicios

Para cada ejercicio práctico:

- Abre ChatGPT, Claude o Gemini
- Copia todo el contenido del archivo `meta-prompts/p7.X.md`
- Pégalo en la IA
- La IA generará un ejercicio práctico completo listo para usar
- Revisa el ejercicio generado antes de entregarlo a los alumnos
- Ajusta si es necesario

### Paso 4: Entregar a los alumnos

Entrega el ejercicio generado a los alumnos. Ellos ejecutarán los prompts del ejercicio en las IAs que prefieran.

### Paso 5: Puesta en común

Después de cada ejercicio, dedica unos minutos a que los alumnos compartan sus resultados y reflexiones.

## Resumen de contenidos

### Teoría

| # | Tema |
|---|---|
| T7.1 | Análisis de código legado con IA: explicación y comprensión |
| T7.2 | Documentación automática y detección de deuda técnica |
| T7.3 | Actualización de dependencias y modernización de código |

### Práctica

| # | Tema |
|---|---|
| P7.1 | Explicar código legado y generar diagramas desde él |
| P7.2 | Generar documentación automática: docstrings, README y ADRs |
| P7.3 | Detectar deuda técnica y code smells con IA |
| P7.4 | Planificar y ejecutar refactorizaciones con IA |
| P7.5 | Actualizar dependencias y detectar vulnerabilidades |
| P7.6 | Modernizar código: migración de frameworks y lenguajes |

## Herramientas utilizadas en las prácticas

Los alumnos pueden usar cualquiera de estas IAs generativas:

- ChatGPT (chat.openai.com)
- Claude (claude.ai)
- Gemini (gemini.google.com)
- GitHub Copilot Chat (en VS Code)

## Conceptos clave del módulo

### Mantenimiento como parte del ALM generativo

El mantenimiento no es una fase separada al final del ciclo de vida. En el ALM generativo, la IA asiste continuamente: documenta el código mientras se genera, detecta deuda técnica en cada PR, sugiere refactorizaciones y actualiza dependencias automáticamente. El mantenimiento es un flujo continuo, no un evento puntual.

### Ingeniería inversa con IA

La IA puede analizar código legacy —incluso en lenguajes antiguos o sin documentación— y explicar su funcionamiento, generar diagramas de su estructura y proponer equivalentes modernos. Esto acelera drásticamente la incorporación a proyectos heredados.

### Documentación viva

La documentación generada por IA no es estática: puede regenerarse cuando el código cambia, asegurando que siempre refleja la implementación real. Los diagramas, docstrings y READMEs se convierten en artefactos vivos que evolucionan con el código.

### Modernización asistida

Migrar entre frameworks, lenguajes o estilos de programación es una de las tareas más arriesgadas del mantenimiento. La IA puede acelerar la traducción mecánica mientras los tests de caracterización actúan como red de seguridad, verificando que el comportamiento no cambia.

## Licencia

Este material es parte del curso "IA Aplicada al Ciclo de Vida del Software".
