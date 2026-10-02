# Decisión: repositorio documental público separado

Fecha: 2026-10-02. Estado: adoptada para la organización de este repositorio. Autoridad: Operador. Registro: coordinación de la tarea autorizada.

## Decisión

El Operador indicó el repositorio `kristhianmanue1/aria-ecosystem` como destino y eligió mantenerlo público, publicando únicamente una base documental saneada. Se preservan el historial inicial y su licencia Apache-2.0.

ARIA Ecosystem conserva documentación transversal seleccionada. Los componentes continúan en repositorios independientes; no se importan sus historiales, código ni almacenes. La copia local de coordinación se mantiene separada del espacio de trabajo que reúne proyectos y worktrees.

## Razón

La documentación transversal necesita un lugar versionado y recuperable. Mezclarla con todos los checkouts introduce riesgos de incorporación accidental, duplicación de fuentes y confusión de autoridad. Un repositorio pequeño satisface la necesidad sin transformar ARIA en un monorepo.

## Alternativas no adoptadas en esta entrega

- Repositorio padre de todos los checkouts: se evita el riesgo de indexación accidental.
- Submódulos: pueden conservar repositorios separados, pero no son necesarios para este propósito documental ni se ha elegido una distribución conjunta.
- Organización nueva de GitHub: puede evaluarse por colaboración y permisos; no es requisito ni está autorizada por esta decisión.
- Copia completa de expedientes internos: se rechaza como mecanismo de publicación inicial; selección, saneamiento y revisión son previos a cualquier incorporación.

## Consecuencias y límites

Los cambios de visibilidad, traslados de proyectos, publicación de evidencias internas y nuevas integraciones requieren decisiones propias. No se otorgan permisos por silencio ni mediante este documento a futuros agentes.

Pinax conserva su responsabilidad sobre catálogo, schema, validador y generador. Cada proyecto conserva el contenido de sus declaraciones y sus decisiones. La incorporación de esta base pública no ratifica todo documento previo de ARIA ni modifica licencias de otros proyectos.
