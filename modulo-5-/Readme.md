# Módulo 5: IA en Testing y Aseguramiento de Calidad

## Información general
Teoría: 3 puntos

Práctica: 6 ejercicios

## Objetivos de aprendizaje
Generar tests unitarios y de integración automáticamente con IAs

Utilizar IA para detección de errores y sugerencias de corrección

Mejorar cobertura y calidad del código mediante herramientas de IA

Entender el bucle de auto-reparación en el ALM generativo

Aplicar validación de seguridad en el código generado por IA

## Estructura del módulo

text
modulo-5-testing-calidad/
├── README.md
├── teoria/
│   ├── t5.1-testing-inteligente-con-ia.md
│   ├── t5.2-estrategias-cobertura-validacion.md
│   └── t5.3-seguridad-testing-codigo-generado.md
└── meta-prompts/
    ├── p5.1-generar-tests-unitarios.md
    ├── p5.2-depuracion-reparacion-tests.md
    ├── p5.3-mejora-cobertura-tests.md
    ├── p5.4-deteccion-vulnerabilidades.md
    ├── p5.5-tests-integracion-api.md
    └── p5.6-ciclo-completo-testing.md

## Cómo usar este módulo

Paso 1: Preparación  
Revisa los archivos de teoría para familiarizarte con los conceptos que vas a explicar.

Paso 2: Explicar la teoría  
Cada archivo en teoria/ contiene el contenido numerado (1, 2, 3...) para que puedas seguirlo secuencialmente. No es un guion literal: adáptalo a tu estilo y experiencia personal.

Paso 3: Generar los ejercicios  
Para cada ejercicio práctico:

Abre ChatGPT, Claude o Gemini

Copia todo el contenido del archivo meta-prompts/p5.X.md

Pégalo en la IA

La IA generará un ejercicio práctico completo listo para usar

Revisa el ejercicio generado antes de entregarlo a los alumnos

Ajusta si es necesario

Paso 4: Entregar a los alumnos  
Entrega el ejercicio generado a los alumnos. Ellos ejecutarán los prompts del ejercicio en las IAs que prefieran.

Paso 5: Puesta en común  
Después de cada ejercicio, dedica unos minutos a que los alumnos compartan sus resultados y reflexiones.

## Resumen de contenidos

### Teoría

#	Tema
T5.1	Testing inteligente con IA: del prompt al test ejecutable
T5.2	Estrategias de cobertura y validación en el ALM generativo
T5.3	Seguridad en testing: detección de vulnerabilidades en código generado por IA

### Práctica

#	Tema
P5.1	Generar tests unitarios desde especificaciones y código existente
P5.2	Depuración y reparación de tests fallidos con IA
P5.3	Mejora de cobertura: identificar brechas y generar tests
P5.4	Detección de vulnerabilidades de seguridad en código generado
P5.5	Generar tests de integración y pruebas de API
P5.6	Ciclo completo: del requisito al código testeado y validado

## Herramientas utilizadas en las prácticas

Los alumnos pueden usar cualquiera de estas IAs generativas:

ChatGPT (chat.openai.com)  
Claude (claude.ai)  
Gemini (gemini.google.com)  
GitHub Copilot Chat (en VS Code)

## Conceptos clave del módulo

### Bucle de auto-reparación

En el ALM generativo, los agentes de IA no solo generan tests: los ejecutan, detectan fallos, diagnostican la causa raíz y corrigen el código automáticamente. Este ciclo (generar → testear → fallar → diagnosticar → corregir → repetir) continúa hasta que todos los tests pasan. El desarrollador supervisa el proceso y valida el resultado final.

### Cobertura como conversación

La mejora de cobertura con IA no es un proceso automático ciego. Es una conversación: visualizas las líneas no cubiertas, pides a la IA que genere tests específicos para esas líneas, ejecutas los tests, y repites. La IA te ayuda a identificar qué tests faltan y a generarlos, pero tú decides qué nivel de cobertura es adecuado.

### Seguridad en el código generado

El código generado por IA puede contener vulnerabilidades. La validación de seguridad debe ser parte del ciclo de testing: revisar dependencias, buscar secretos hardcodeados, verificar validación de entradas y analizar la superficie de ataque. La IA puede ayudar a detectar estos problemas, pero la revisión humana sigue siendo esencial.

### Del test al requisito (trazabilidad inversa)

En el ALM generativo, los tests no solo verifican el código: confirman que el código cumple los requisitos. Cada test debe poder trazarse hasta un criterio de aceptación Gherkin de la especificación original. La IA puede ayudar a mantener esta trazabilidad generando tests que se corresponden explícitamente con cada criterio.

## Licencia

Este material es parte del curso "IA Aplicada al Ciclo de Vida del Software".
