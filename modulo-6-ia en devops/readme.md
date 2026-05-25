# Módulo 6: IA en DevOps y Despliegue

## Información general

- Teoría: 3 puntos
- Práctica: 6 ejercicios

## Objetivos de aprendizaje

- Crear pipelines CI/CD usando descripciones en lenguaje natural con IAs
- Automatizar la generación de Dockerfiles, docker-compose y manifiestos de Kubernetes
- Diagnosticar errores de despliegue con apoyo de IA
- Entender el concepto de Self-Healing CI en el ALM generativo
- Generar infraestructura como código desde prompts

## Estructura del módulo

```text
modulo-6-devops-despliegue/
├── README.md
├── teoria/
│   ├── t6.1-ia-en-cicd.md
│   ├── t6.2-infraestructura-como-codigo.md
│   └── t6.3-diagnostico-fallos-auto-reparacion.md
└── meta-prompts/
    ├── p6.1-generar-pipeline-cicd.md
    ├── p6.2-generar-dockerfile-manifiestos.md
    ├── p6.3-diagnostico-fallos-ci.md
    ├── p6.4-self-healing-ci.md
    ├── p6.5-infraestructura-como-codigo.md
    └── p6.6-ciclo-completo-devops.md
```
## Cómo usar este módulo

### Paso 1: Preparación

Revisa los archivos de teoría para familiarizarte con los conceptos que vas a explicar.

### Paso 2: Explicar la teoría

Cada archivo en `teoria/` contiene el contenido numerado (1, 2, 3...) para seguirlo secuencialmente. No es un guion literal: adáptalo a tu estilo y experiencia personal.

### Paso 3: Generar los ejercicios

Para cada ejercicio práctico:

- Abre ChatGPT, Claude o Gemini
- Copia todo el contenido del archivo `meta-prompts/p6.X.md`
- Pégalo en la IA
- La IA generará el ejercicio práctico completo listo para usar
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
| T6.1 | IA en CI/CD: del pipeline manual al pipeline generado |
| T6.2 | Infraestructura como código con IA: Docker, Kubernetes y más |
| T6.3 | Diagnóstico de fallos y auto-reparación de pipelines |

### Práctica

| # | Tema |
|---|---|
| P6.1 | Generar pipelines CI/CD desde lenguaje natural |
| P6.2 | Generar Dockerfiles y manifiestos Kubernetes |
| P6.3 | Diagnosticar y reparar fallos de CI/CD |
| P6.4 | Configurar Self-Healing CI con IA |
| P6.5 | Generar infraestructura como código (Terraform, Bicep) |
| P6.6 | Ciclo completo: del commit al despliegue automatizado |

## Herramientas utilizadas en las prácticas

- ChatGPT (chat.openai.com)
- Claude (claude.ai)
- Gemini (gemini.google.com)
- GitHub Copilot Chat (en VS Code)

## Conceptos clave del módulo

### Pipeline como código generado

Los pipelines de CI/CD se describen en lenguaje natural y la IA genera la configuración completa.

### Self-Healing CI

Cuando un pipeline falla, la IA analiza logs, diagnostica la causa raíz y corrige automáticamente.

### Infraestructura como código generada

Docker, Kubernetes, Terraform y Bicep se generan desde prompts.

### Despliegue autónomo

Flujo completo: código → tests → build → deploy → monitorizar → auto-reparar.

## Licencia

Este material es parte del curso "IA Aplicada al Ciclo de Vida del Software".
