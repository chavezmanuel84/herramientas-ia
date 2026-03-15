# Technical Brief

## 1. Título de la tarea

Nombre claro y específico de la tarea, funcionalidad o servicio a implementar.

Ejemplos:
 - Servicio de cálculo de gastos personales segmentados
 - Diseño y desarrollo de un sistema de monitoreo de tickets de soporte técnico
 - Interfaz de anonimización dinámica (automatica-manual) de respuestas JSON de APIs.

---

## 2. Contexto

### Objetivo de la tarea

Define claramente qué se espera lograr.

Ejemplos:

- Crear una landing page para un salon de belleza
- Resumir una investigación técnica
- Proponer posibles soluciones a un problema
- Generar documentación estructurada
- Diseñar un proceso o flujo de trabajo

### Problemática actual

Describe el sistema actual y por qué se necesita esta solución.

Incluye:

- Cómo funciona actualmente el sistema o proceso
- Qué problema o necesidad existe (trabajo manual, sincronizacion, escalabilidad, etc.)
- Qué se busca lograr con esta implementación
- (Opcional) Quién será el usuario o usiarios finales de la solución/herramienta y que podrá lograr con ella

Estructura sugerida (adiciona o remueve de ser necesario):

- El sistema actual \***\*\_\_\_\_\*\***.
- Esto genera problemas como \***\*\_\_\_\_\*\***.
- El objetivo es \***\*\_\_\_\_\*\*** para mejorar \***\*\_\_\_\_\*\***.
- (Opcional) El usuario final es \***\*\_\_\_\_\*\*** deberá ser capáz de \***\*\_\_\_\_\*\***.

---

## 3. Requerimientos de la solución

Requisitos que delimitan la solución, haciéndola compatible con tu sistema, tus preferencias y tus posibilidades.

### Lenguaje / Stack (si aplica)

- Lenguaje / Versión mínima
- Framework (si aplica)
- Modelos de IA disponible
- Otras herramientas

---

### Arquitectura (si aplica)

Describe patrones o principios a usar.

Ejemplo:

- Clean Architecture
- Strategy Pattern
- Dependency Injection
- Stateless service

---

### Input esperado

Define o describe los datos que se esperan como entrada.

Ejemplo:

```python
InputObject
- field_1: type
- field_2: type
```

### Output esperado

Define o describe el resultado o modelo de salida esperado.

Ejemplo:

```python
InputObject
- field_1: type
- field_2: type
```

### 4. Constraints (Restricciones)

Reglas que la solución debe respetar.

Ejemplos:

- No usar librerías externas salvo las expresamente autorizadas o aquellas mencionadas en **Requerimientos de la solución**.
- Integrar solo los modelos de IA expresamente autorizados o aquellos mencionados en los **Requerimientos de la solución**.
- Implementar type hints en todo el código.
- Implementar buenas prácticas del lenguaje o tecnología utilizada.
- Mantener una arquitectura clara y modular.

## 5. Plan de implementación esperado

Antes de generar la solución final, describe brevemente el enfoque o plan de implementación propuesto.

Incluye:

- Componentes principales
- Flujo de datos
- Funciones, módulos o credenciales necesarios
- Decisiones y restricciones de diseño relevantes

El objetivo es **validar el enfoque antes de generar la implementación final.**


### 6. Definition of Done (DoD)

Checklist de criterios verificables. 
La tarea o solución se considera terminada cuando, por ejemplo:

 - El formato de salida cumple con el **Output esperado**
 - La solución se ejecuta sin errores
 - Se cumplen las **Restricciones** planteadas
 - Se pasan los tests funcionales establecidos
 - Se realiza una verificación humana
