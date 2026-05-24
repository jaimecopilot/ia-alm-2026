# Módulo 2: IA en la Fase de Análisis de Requisitos

## Información general
- **Teoría:** 3 puntos
- **Práctica:** 6 ejercicios

## Objetivos de aprendizaje
- Generar especificaciones ejecutables que cualquier IA de codificación pueda implementar
- Transformar ideas de negocio en backlogs estructurados con criterios Gherkin
- Refinar requisitos iterativamente hasta alcanzar el nivel de detalle que una IA necesita
- Identificar requisitos no funcionales y conectarlos con decisiones de arquitectura
- Generar documentación de arquitectura directamente desde los requisitos
- Crear issues trazables que conecten requisitos con generación automática de código

## Estructura del módulo
```
modulo-2-analisis-requisitos/
├── README.md
├── teoria/
│   ├── t2.1-ia-elicitacion-requisitos.md
│   ├── t2.2-prompting-historias-usuario.md
│   └── t2.3-ecosistema-herramientas-analisis.md
└── meta-prompts/
    ├── p2.1-idea-a-especificacion-ejecutable.md
    ├── p2.2-especificacion-a-backlog.md
    ├── p2.3-refinamiento-iterativo.md
    ├── p2.4-requisitos-no-funcionales-arquitectura.md
    ├── p2.5-documentacion-arquitectura-desde-requisitos.md
    └── p2.6-requisito-a-issue-trazabilidad.md
```

## Cómo usar este módulo
### Paso 1: Preparación
Revisa los archivos de teoría para familiarizarte con los conceptos que vas a explicar.

### Paso 2: Explicar la teoría
Cada archivo en `teoria/` contiene el contenido numerado (1, 2, 3...) para que puedas seguirlo secuencialmente. No es un guion literal: adáptalo a tu estilo y experiencia personal.

### Paso 3: Generar los ejercicios
Para cada ejercicio práctico:
- Abre ChatGPT, Claude o Gemini
- Copia todo el contenido del archivo `meta-prompts/p2.X.md`
- Pégalo en la IA
- La IA generará un ejercicio práctico completo y listo para usar
- Revisa el ejercicio generado antes de entregarlo a los alumnos
- Ajusta si es necesario

### Paso 4: Entregar a los alumnos
Entrega el ejercicio generado a los alumnos. Ellos ejecutarán los prompts del ejercicio en las IAs que prefieran (ChatGPT, Claude, Gemini, Copilot Chat).

### Paso 5: Puesta en común
Después de cada ejercicio, dedica unos minutos a que los alumnos compartan sus resultados y reflexiones.

## Resumen de contenidos
### Teoría
| #   | Tema                                                           |
|-----|----------------------------------------------------------------|
| T2.1| Cómo los LLM asisten en la elicitación de requisitos           |
| T2.2| Técnicas de prompting para historias de usuario y backlog      |
| T2.3| Ecosistema de herramientas para análisis de requisitos         |

### Práctica
| #    | Tema                                                           |
|------|----------------------------------------------------------------|
| P2.1 | De idea de negocio a especificación ejecutable                |
| P2.2 | De especificación a historias de usuario y backlog            |
| P2.3 | Refinamiento iterativo: del requisito al código generable     |
| P2.4 | Identificación de requisitos no funcionales y su impacto en la arquitectura |
| P2.5 | Generación de documentación de arquitectura desde requisitos  |
| P2.6 | Del requisito a la issue: trazabilidad completa               |

## Herramientas utilizadas en las prácticas
Los alumnos pueden usar cualquiera de estas IAs generativas:
- ChatGPT (chat.openai.com)
- Claude (claude.ai)
- Gemini (gemini.google.com)
- GitHub Copilot Chat (en VS Code)

## Conceptos clave del módulo
**Especificación ejecutable:**
Una especificación ejecutable es un documento de requisitos que contiene suficiente contexto técnico, criterios de aceptación Gherkin y restricciones explícitas como para que una IA de codificación pueda generar una implementación funcional sin ambigüedades. Es el puente entre el análisis y la generación automática de código.

**Generabilidad:**
Un requisito es "generable" cuando una IA puede leerlo y producir código funcional sin necesidad de hacer preguntas adicionales. El objetivo del refinamiento iterativo es alcanzar este nivel de detalle.

**Trazabilidad:**
Cada requisito debe poder rastrearse desde su origen (idea de negocio) hasta su implementación (código, tests, despliegue). La IA puede ayudar a mantener esta trazabilidad generando issues vinculadas, matrices de trazabilidad y documentación de auditoría.

## Licencia
Este material es parte del curso "IA Aplicada al Ciclo de Vida del Software".
