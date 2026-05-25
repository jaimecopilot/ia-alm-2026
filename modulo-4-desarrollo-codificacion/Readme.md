# Módulo 4: IA en Desarrollo y Codificación

## Información general

Teoría: 4 puntos

Práctica: 8 ejercicios

---

## Objetivos de aprendizaje

Dominar el uso de IAs generativas para escribir, refactorizar y traducir código

Aplicar prompting efectivo para generación de funciones, clases y algoritmos

Realizar refactorización asistida aplicando principios de Clean Code

Traducir código entre lenguajes de programación manteniendo la lógica

Integrar IA en el flujo diario de desarrollo siguiendo buenas prácticas profesionales

Entender el flujo completo de ALM generativo: del prompt ejecutable al código funcional

---

## Estructura del módulo

```
modulo-4-desarrollo-codificacion/
├── README.md
├── teoria/
│   ├── t4.1-ia-generacion-codigo.md
│   ├── t4.2-prompting-funciones-clases.md
│   ├── t4.3-refactorizacion-traduccion.md
│   └── t4.4-buenas-practicas-validacion.md
└── meta-prompts/
    ├── p4.1-generacion-codigo-comentarios.md
    ├── p4.2-crud-api-rest.md
    ├── p4.3-refactorizacion-clean-code.md
    ├── p4.4-traduccion-entre-lenguajes.md
    ├── p4.5-explicacion-codigo-complejo.md
    ├── p4.6-deteccion-correccion-bugs.md
    ├── p4.7-generacion-codigo-patrones-diseno.md
    └── p4.8-ciclo-completo-desarrollo.md
```

---

## Cómo usar este módulo

### Paso 1: Preparación

Revisa los archivos de teoría para familiarizarte con los conceptos que vas a explicar.

---

### Paso 2: Explicar la teoría

Cada archivo en teoria/ contiene el contenido numerado (1, 2, 3...) para que puedas seguirlo secuencialmente. No es un guion literal: adáptalo a tu estilo y experiencia personal.

---

### Paso 3: Generar los ejercicios

Para cada ejercicio práctico:

- Abre ChatGPT, Claude o Gemini  
- Copia todo el contenido del archivo meta-prompts/p4.X.md  
- Pégalo en la IA  
- La IA generará un ejercicio práctico completo listo para usar  
- Revisa el ejercicio generado antes de entregarlo a los alumnos  
- Ajusta si es necesario  

---

### Paso 4: Entregar a los alumnos

Entrega el ejercicio generado a los alumnos. Ellos ejecutarán los prompts del ejercicio en las IAs que prefieran (ChatGPT, Claude, Gemini, Copilot Chat, Codeium, Amazon Q Developer).

---

### Paso 5: Puesta en común

Después de cada ejercicio, dedica unos minutos a que los alumnos compartan sus resultados y reflexiones.

---

## Resumen de contenidos

### Teoría

| # | Tema |
|---|------|
| T4.1 | IA en generación de código: del prompt al código funcional |
| T4.2 | Técnicas de prompting para funciones, clases y algoritmos |
| T4.3 | Refactorización asistida y traducción entre lenguajes |
| T4.4 | Buenas prácticas y validación en el desarrollo con IA |

---

### Práctica

| # | Tema |
|---|------|
| P4.1 | Generación de código desde comentarios y especificaciones |
| P4.2 | Creación de un CRUD API REST completo desde prompt ejecutable |
| P4.3 | Refactorización aplicando Clean Code con IA |
| P4.4 | Traducción de código entre lenguajes |
| P4.5 | Explicación de código complejo línea por línea |
| P4.6 | Detección y corrección de bugs con IA |
| P4.7 | Generación de código aplicando patrones de diseño |
| P4.8 | Ciclo completo: del prompt ejecutable al código validado |

---

## Herramientas utilizadas en las prácticas

Los alumnos pueden usar cualquiera de estas IAs generativas:

- ChatGPT (chat.openai.com)
- Claude (claude.ai)
- Gemini (gemini.google.com)
- GitHub Copilot Chat (en VS Code)
- Codeium (extensión gratuita para VS Code)
- Amazon Q Developer (extensión para VS Code)

---

## Conceptos clave del módulo

### Prompt ejecutable para código

Un prompt ejecutable para generación de código debe incluir: propósito de la función o clase, parámetros con tipos, lógica esperada, validaciones necesarias, formato de retorno y restricciones explícitas.

Cuanto más detallado sea el prompt, más preciso será el código generado.

---

### Generación multi-archivo

Las IAs modernas pueden generar código que abarca múltiples archivos (modelos, servicios, controladores, tests) a partir de una única especificación.

Esto acelera drásticamente la creación de features completas.

---

### Refactorización como prompt

La refactorización no requiere reescribir código manualmente.

Puedes tomar código existente, describir la transformación deseada ("aplica el patrón Repository", "extrae esta lógica a un método separado") y la IA generará el código refactorizado.

---

### Validación sistemática

Todo código generado por IA debe pasar por un protocolo de validación: revisión visual, verificación de dependencias, ejecución de tests, revisión de seguridad.

La IA acelera la escritura, pero la responsabilidad de la calidad sigue siendo del desarrollador.

---

### Del prompt al código en el ALM generativo

En el contexto del ALM generativo, un prompt de desarrollo no es solo una pregunta: es una instrucción que dispara la generación de código funcional, tests y documentación.

El desarrollador pasa de escribir cada línea a dirigir agentes que implementan features completas.

---

## Licencia

Este material es parte del curso "IA Aplicada al Ciclo de Vida del Software".
