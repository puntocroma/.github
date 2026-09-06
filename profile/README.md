# PuntoCroma

## Guidelines para crear issues y sub-issues

Los issues del equipo se organizan en dos niveles:

### 1. Épicas
Una **épica** engloba una tarea compleja, divisible en varias sub-tareas (equivalente a una historia de usuario). Se usa para features o iniciativas grandes que requieren más de una PR para completarse. Una épica lista sus sub-tareas como checklist y/o issues enlazados.

### 2. Sub-tareas
Una **sub-tarea** es una parte concreta y acotada de una épica: una unidad de trabajo que se puede resolver en **una PR**.

### Todo issue (épica o sub-tarea) debe incluir

- **Descripción detallada**: qué se necesita, el contexto/motivación, y cualquier detalle relevante para implementarlo sin ambigüedad.
- **Acceptance Criteria (AC) completo**: condiciones verificables que definen cuándo el issue se considera terminado. Deben ser concretas (comportamiento esperado, casos borde), no un resumen genérico.
- **Tags**: labels que definan el tipo de issue (ej. `epic`, `bug`, `enhancement`, `documentation`, etc.), para poder filtrar y priorizar el trabajo.

Un issue sin descripción, sin AC, o sin tags no está listo para tomarse.

## Guidelines para crear una Pull Request

### Épica y sub-tarea relacionadas

- Épica: #
- Sub-tarea: #

### Descripción

<!-- Qué resuelve esta PR y por qué. -->

### Tipo de PR

- [ ] Feature
- [ ] Bugfix
- [ ] Refactor
- [ ] Documentación
- [ ] Security
- [ ] Techdebt

### Cambios realizados

<!-- Lista concreta de los cambios incluidos en esta PR. -->

-
-

### Tests

**Toda PR debe tener tests asociados.** Sin tests, la PR no se mergea.

- [ ] Se agregaron y/o actualizaron tests que cubren este cambio

<!-- Qué cubren los tests agregados/actualizados: -->

### Validación

- [ ] Pipeline de CI pasó (confirmar antes de mergear)
- [ ] Probado manualmente (detallar pasos si aplica)
