# Fronteras y responsabilidades

Estado: orientación arquitectónica declarada; no inventario verificado de capacidades ejecutables. Fecha: 2026-10-02.

## Repositorios y decisiones independientes

ARIA coordina preguntas y relaciones entre proyectos. No sustituye el gobierno de cada componente. Integrar exige identificar consumidor, contrato, propietario, evidencia de necesidad, límites de confianza y posibilidad de funcionar por separado.

| Ámbito | Responsabilidad declarada | No se deduce de ella |
|---|---|---|
| ARIA Ecosystem | Orientación pública y decisiones transversales identificables | Control operativo o autorización universal |
| Pinax | Catálogo, schema, validación formal y compilación del mapa declarado | Veracidad de capacidades, estado dinámico o inclusión automática |
| Skopos | Captura y conservación de fuentes | Fidelidad semántica de toda interpretación derivada |
| Ágora | Transformación y representaciones estructuradas con procedencia | Verdad por publicación, memoria completa implementada o admisión automática |
| EKTEL | Contrato neutral de ejecución con garantías y límites explícitos | Aislamiento general o autorización de cualquier ejecución |
| AN-KLA | Conservación selectiva y transiciones gobernadas de continuidad | Autoridad concedida por el contenido recuperado |
| SKEVI y CAGF | Metodología, axiomas, observables y falsación según sus ámbitos | Autoridad superior sobre todos los proyectos |
| Basanos | Función de auditoría según el alcance de su proyecto | Auditor universal de ARIA o independencia demostrada por su nombre |
| Kratos | Orquestador final previsto | Propiedad del estándar o auditoría por ahora |

La tabla no es un catálogo exhaustivo ni una prueba de implementación. Las identidades y capacidades concretas se verifican en las fuentes de cada proyecto y mediante Pinax cuando corresponda; no se resuelven por similitud entre nombres de carpetas.

## Tres separaciones necesarias

1. **Declarar y comprobar:** un manifiesto válido puede estar desactualizado.
2. **Revisar y adjudicar:** un dictamen del revisor no sustituye la decisión humana.
3. **Cerrar y aceptar:** terminar un ensayo puede producir un resultado desfavorable válido; no obliga a iterar hasta obtener aprobación.

## Contratos de integración

Una integración futura debe especificar qué datos intercambia, quién conserva su identidad, cómo se verifica su procedencia, qué autoridad necesita y cómo falla o se retira sin absorber al otro componente. La base de datos, el framework y el proveedor no son requisitos arquitectónicos por defecto.

Este repositorio no activa ninguna integración ni establece que todos los componentes deban ejecutarse juntos.
