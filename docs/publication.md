# Política de publicación de esta base pública

Alcance: ARIA Ecosystem. Fecha: 2026-10-02. No sustituye las políticas de otros proyectos.

## Contenido admisible

- Descripción pública del propósito y límites del ecosistema.
- Decisiones transversales con autoridad identificada y alcance explícito.
- Propuestas de trabajo claramente separadas de autorizaciones.
- Referencias públicas verificadas y fotografías fechadas con procedencia suficiente.

## Contenido excluido por defecto

- Credenciales, tokens, claves, cookies, archivos de entorno y almacenes de memoria.
- Conversaciones, datos personales, datos clínicos, corpus privados o entradas reales no autorizadas para difusión.
- Logs completos de agentes, volcados del entorno, rutas personales e identificadores de sesiones internas.
- Copias de repositorios, directorios `.git`, worktrees, enlaces a archivos locales y submódulos no autorizados.
- Expedientes internos, registros completos de concesiones o artefactos experimentales sin selección y revisión específica.

Un repositorio público puede divulgar información por su historial aunque se retire después de la vista actual. La revisión debe ocurrir antes del primer commit y push del material. Una búsqueda de patrones de secretos ayuda, pero no prueba que el texto sea seguro para publicación.

## Incorporar antecedentes

No mover ni reescribir originales congelados para adaptar sus rutas. Elegir entre una referencia verificable, una copia exacta autorizada o un resumen público derivado. Identificar qué opción se utilizó, sus fuentes y sus límites. Un resumen saneado tiene identidad propia y no debe presentarse con el hash del original.

Si no puede publicarse la fuente, no presentar el resumen como evidencia pública suficiente. Mantener las afirmaciones limitadas, sin fabricar enlaces accesibles ni revelar ubicaciones privadas.

## Verificación antes de publicar

1. Confirmar repositorio, rama, visibilidad, autorización y estado remoto.
2. Revisar la lista exacta de archivos y todo el diff; no usar incorporación indiscriminada del espacio de trabajo.
3. Comprobar enlaces locales, exclusiones y ausencia de repositorios anidados o gitlinks.
4. Revisar texto y archivos contra secretos, datos privados y claims sin respaldo proporcional.
5. Preservar cambios ajenos y licencia; publicar sin sobrescribir historia remota.
6. Verificar la referencia remota resultante y declarar verificaciones pendientes.

La lista permitida de `.gitignore` reduce incorporaciones accidentales; puede eludirse mediante archivos ya rastreados o inclusión forzada. No reemplaza revisión ni constituye enforcement de confidencialidad.

## Licencias

Conservar la licencia existente del repositorio. No importar contenido de terceros ni de otros componentes asumiendo que la licencia de ARIA permite redistribuirlo; revisar su autorización y licencia antes de incorporarlo.
