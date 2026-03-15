# Protocolo de Review para resultados generados con IA

## 1. Verificación de fuentes o dependencias

### Pregunta clave

¿Las herramientas, librerías, APIs o referencias mencionadas realmente existen?

La IA puede inventar:

- librerías
- funciones
- endpoints
- métodos
- documentación

**Verificar:**

- documentación oficial
- existencia real de la herramienta o API
- compatibilidad con la versión utilizada

### Checklist

- [ ] Las herramientas o librerías mencionadas existen
- [ ] Las funciones o métodos utilizados son reales
- [ ] Las APIs o endpoints corresponden a la documentación oficial actual

## 2. Corrección lógica

### Pregunta clave

¿La solución o explicación es realmente correcta?

**Errores comunes generados por IA:**

- tipos de datos/fechas incorrectos o incompatibles
- conclusiones apresuradas
- cálculos incorrectos
- supuestos no justificados

### Checklist

- [ ] La lógica del análisis o solución es correcta
- [ ] No hay conclusiones sin evidencia
- [ ] Los cálculos o razonamientos son correctos
- [ ] Se contemplan casos límite o escenarios alternativos

## 3. Riesgos y Seguridad

### Pregunta clave

¿La solución introduce riesgos técnicos o de seguridad?

La IA puede generar soluciones funcionales pero inseguras.

**Revisar:**

- validación de inputs
- exposición de secretos o datos sensibles
- manejo de credenciales
- riesgos de inyección (SQL, comandos, etc.)

### Checklist

- [ ] Los inputs están correctamente validados
- [ ] No se exponen credenciales o secretos
- [ ] No se filtran datos sensibles
- [ ] No se introducen riesgos de seguridad evidentes

## 4. Consistencia con el Brief (Context Window)

### Pregunta clave

¿La respuesta realmente cumple con el Brief original?

Cuando el contexto es largo la IA puede ignorar:

- objetivos
- constraints
- decisiones arquitectónicas
- requisitos técnicos
- Definition of Done

### Checklist

- [ ] La solución respeta el Brief original
- [ ] Se cumplen los constraints definidos
- [ ] Se respetan los inputs y outputs esperados
- [ ] Se cumple la Definition of Done

## 5. Criterios específicos del proyecto

Este punto depende del tipo de tarea o del stack utilizado.

**Ejemplos comunes:**

- compatibilidad con arquitectura o sistema existente
- cobertura de tests
- logging
- performance
- métricas y observabilidad
- calidad de la documentación
- claridad de la explicación

### Checklist

- [ ] Tests cubren el código nuevo
- [ ] Logs no exponen datos sensibles
- [ ] Performance es aceptable y mejora la experiencia anterior
- [ ] Las métricas son reales y funcionan correctamente
- [ ] La solución es mantenible o escalable
- [ ] El tamaño de la solución es razonable para el contexto del proyecto

## Resultado del Review

- [ ] El resultado pasa todos los puntos del protocolo de revisión
- [ ] Se realizaron las correcciones necesarias
- [ ] El resultado está listo para integración o uso

**Reviewer:** ____________________  
**Fecha:** ____________________
