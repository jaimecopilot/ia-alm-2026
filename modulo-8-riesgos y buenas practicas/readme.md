# Módulo 8: Riesgos y Buenas Prácticas + Proyecto Integrador

## Información general

Teoría: 4 puntos

Práctica: 10 ejercicios

## Objetivos de aprendizaje

- Identificar errores comunes al usar IA: código incorrecto, dependencias falsas, alucinaciones
- Aplicar protocolos de seguridad y manejo de datos sensibles
- Validar y supervisar rigurosamente el output generado por IA
- Implementar defensas contra prompt injection
- Integrar todos los módulos en un proyecto práctico completo de ALM generativo

## Estructura del módulo

```text
modulo-8-riesgos-proyecto-integrador/
├── README.md
├── teoria/
│   ├── t8.1-catalogo-fallos-tipicos.md
│   ├── t8.2-seguridad-manejo-datos-sensibles.md
│   ├── t8.3-validacion-supervision-output-ia.md
│   └── t8.4-gobierno-ia-trazabilidad.md
└── meta-prompts/
    ├── p8.1-detectar-alucinaciones.md
    ├── p8.2-configurar-seguridad.md
    ├── p8.3-prompt-injection-hardening.md
    ├── p8.4-protocolo-validacion.md
    ├── p8.5-proyecto-analisis-diseno.md
    ├── p8.6-proyecto-implementacion.md
    ├── p8.7-proyecto-testing-seguridad.md
    ├── p8.8-proyecto-documentacion.md
    ├── p8.9-proyecto-devops-despliegue.md
    └── p8.10-proyecto-reflexion-final.md
```
# Cómo usar este módulo

## Paso 1: Preparación

Revisa los archivos de teoría para familiarizarte con los conceptos que vas a explicar.

## Paso 2: Explicar la teoría

Cada archivo en teoria/ contiene el contenido numerado (1, 2, 3...) para que puedas seguirlo secuencialmente. No es un guion literal: adáptalo a tu estilo y experiencia personal.

## Paso 3: Generar los ejercicios

Para cada ejercicio práctico:

- Abre ChatGPT, Claude o Gemini
- Copia todo el contenido del archivo meta-prompts/p8.X.md
- Pégalo en la IA
- La IA generará un ejercicio práctico completo listo para usar
- Revisa el ejercicio generado antes de entregarlo a los alumnos
- Ajusta si es necesario

## Paso 4: Entregar a los alumnos

Entrega el ejercicio generado a los alumnos. Ellos ejecutarán los prompts del ejercicio en las IAs que prefieran.

## Paso 5: Puesta en común

Después de cada ejercicio, dedica unos minutos a que los alumnos compartan sus resultados y reflexiones.

## Resumen de contenidos

### Teoría

| # | Tema |
|---|---|
| T8.1 | Catálogo de fallos típicos: alucinaciones, dependencias falsas y código incorrecto |
| T8.2 | Seguridad y manejo de datos sensibles con IA |
| T8.3 | Cómo validar y supervisar el output generado por la IA |
| T8.4 | Gobierno de la IA: auditoría, trazabilidad y cumplimiento normativo |

### Práctica

| # | Tema |
|---|---|
| P8.1 | Detectar y corregir alucinaciones en código generado por IA |
| P8.2 | Configurar la seguridad: prevención de fugas de datos y manejo de secretos |
| P8.3 | Simulación de prompt injection y hardening de instrucciones |
| P8.4 | Implementar un protocolo de validación de código generado por IA |
| P8.5 | Proyecto integrador: análisis y diseño con IA |
| P8.6 | Proyecto integrador: implementación con IA |
| P8.7 | Proyecto integrador: testing, revisión de seguridad y CI/CD |
| P8.8 | Proyecto integrador: documentación, diagramas y ADRs |
| P8.9 | Proyecto integrador: DevOps y despliegue |
| P8.10 | Cierre: retrospectiva, dashboard de calidad y reflexión final |

## Herramientas utilizadas en las prácticas

Los alumnos pueden usar cualquiera de estas IAs generativas:

- ChatGPT (chat.openai.com)
- Claude (claude.ai)
- Gemini (gemini.google.com)
- GitHub Copilot Chat (en VS Code)

## Conceptos clave del módulo

### Validación sistemática

Todo output generado por IA debe pasar por un protocolo de validación estructurado: verificación visual, verificación de dependencias, ejecución de tests, validación contra requisitos, revisión de seguridad, revisión de calidad y validación de documentación. Este protocolo es universal y aplicable a cualquier IA generativa.

### Defensa en profundidad contra prompt injection

La protección contra ataques de prompt injection requiere múltiples capas: instrucciones blindadas en el prompt de sistema, reglas de seguridad inmutables, verificación humana para contenido sospechoso y detección automatizada de patrones de ataque.

### Gobernanza de la IA

El uso de IA en el desarrollo de software requiere políticas claras de gobernanza: qué herramientas están autorizadas, cómo se audita el código generado, cómo se mantiene la trazabilidad desde el requisito hasta el despliegue y cómo se asegura el cumplimiento normativo.

### Proyecto integrador de ALM generativo

El proyecto final aplica todas las habilidades aprendidas en los módulos anteriores en un flujo completo: análisis → diseño → implementación → testing → DevOps → mantenimiento → riesgos. Los alumnos eligen la mejor IA para cada fase y justifican sus decisiones.

## Licencia

Este material es parte del curso "IA Aplicada al Ciclo de Vida del Software".
