# Módulo 3: IA en Diseño de Software

## Información general
- **Teoría:** 3 puntos
- **Práctica:** 6 ejercicios

## Objetivos de aprendizaje
- Usar IAs como sparring arquitectónico para explorar y comparar arquitecturas
- Generar diagramas UML, C4 y de arquitectura desde especificaciones ejecutables
- Evaluar decisiones técnicas mediante diálogo con múltiples IAs
- Conectar el diseño con la generación automática de código
- Generar ADRs y documentación de arquitectura desde los requisitos

## Estructura del módulo
```
modulo-3-diseno-software/
├── README.md
├── teoria/
│   ├── t3.1-ia-como-sparring-arquitectonico.md
│   ├── t3.2-diagramas-uml-c4-con-ia.md
│   └── t3.3-evaluacion-decisiones-arquitectura.md
└── meta-prompts/
    ├── p3.1-explorar-arquitecturas.md
    ├── p3.2-generar-diagramas-c4-uml.md
    ├── p3.3-evaluar-decisiones-tecnicas.md
    ├── p3.4-del-requisito-al-diseno.md
    ├── p3.5-documentar-decisiones-adr.md
    └── p3.6-ciclo-completo-diseno.md
```

## Cómo usar este módulo
### Paso 1: Preparación
Revisa los archivos de teoría para familiarizarte con los conceptos que vas a explicar.

### Paso 2: Explicar la teoría
Cada archivo en `teoria/` contiene el contenido numerado (1, 2, 3...) para que puedas seguirlo secuencialmente. No es un guion literal: adáptalo a tu estilo y experiencia personal.

### Paso 3: Generar los ejercicios
Para cada ejercicio práctico:
- Abre ChatGPT, Claude o Gemini
- Copia todo el contenido del archivo `meta-prompts/p3.X.md`
- Pégalo en la IA
- La IA generará un ejercicio práctico completo listo para usar
- Revisa el ejercicio generado antes de entregarlo a los alumnos
- Ajusta si es necesario

### Paso 4: Entregar a los alumnos
Entrega el ejercicio generado a los alumnos. Ellos ejecutarán los prompts del ejercicio en las IAs que prefieran (ChatGPT, Claude, Gemini, Copilot Chat).

### Paso 5: Puesta en común
Después de cada ejercicio, dedica unos minutos a que los alumnos compartan sus resultados y reflexiones.

## Resumen de contenidos
### Teoría
| #   | Tema                                   |
|-----|----------------------------------------|
| T3.1| La IA como sparring arquitectónico     |
| T3.2| Generación de diagramas UML y C4 con IA|
| T3.3| Evaluación de decisiones técnicas con IA|

### Práctica
| #    | Tema                                                 |
|------|------------------------------------------------------|
| P3.1 | Explorar y comparar arquitecturas con IA              |
| P3.2 | Generar diagramas C4 y UML desde especificaciones     |
| P3.3 | Evaluar decisiones técnicas con múltiples IAs         |
| P3.4 | Del requisito al diseño: conectar análisis con arquitectura |
| P3.5 | Documentar decisiones con ADRs generados por IA       |
| P3.6 | Ciclo completo de diseño: de la especificación al diagrama |

## Herramientas utilizadas en las prácticas
Los alumnos pueden usar cualquiera de estas IAs generativas:
- ChatGPT (chat.openai.com)
- Claude (claude.ai)
- Gemini (gemini.google.com)
- GitHub Copilot Chat (en VS Code)

## Conceptos clave del módulo
**Sparring arquitectónico**
La IA actúa como un compañero de diseño que nunca se cansa de explorar alternativas. No toma decisiones por ti, pero te ayuda a evaluar trade-offs, identificar riesgos y documentar el razonamiento detrás de cada elección.

**Diagramas como código**
Los diagramas generados por IA en formato Mermaid o PlantUML no son imágenes estáticas: son texto versionable que evoluciona con el código. Pueden regenerarse cuando los requisitos cambian y revisarse en Pull Requests como cualquier otro artefacto.

**Del requisito al diseño**
Una especificación ejecutable bien redactada contiene suficiente información para que una IA genere automáticamente diagramas de arquitectura, diagramas de secuencia y ADRs. El diseño no es una fase separada, sino una continuación natural del análisis.

**Trazabilidad del diseño**
Cada decisión arquitectónica debe poder rastrearse hasta el requisito que la motivó. Los ADRs generados por IA mantienen esta conexión, documentando no solo qué se decidió sino por qué.

## Licencia
Este material es parte del curso "IA Aplicada al Ciclo de Vida del Software".
