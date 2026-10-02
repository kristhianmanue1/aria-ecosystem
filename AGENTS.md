# Colaboración en ARIA Ecosystem

Este es un repositorio documental público, separado de los proyectos del ecosistema. Antes de actuar, leer README.md y docs/publication.md, identificar rama, HEAD y cambios locales. Usar `git --no-optional-locks` para inspección.

## Alcance

- Trabajar solo en el encargo autorizado; analizar no equivale a editar o publicar.
- No clonar, mover, copiar ni incorporar componentes, worktrees o submódulos aquí por iniciativa propia.
- No modificar proyectos referenciados mediante una tarea de este repositorio.
- Mantener a Pinax como catálogo/compilador, sin duplicar sus contratos. Kratos conserva el papel previsto de orquestador final, sin estándar ni auditoría por esta publicación.
- No cargar ni escribir memoria persistente por inferencia. No hay integración de memoria configurada por esta entrega.

## Evidencia y autoridad

Distinguir propuesta, implementación, ejecución observada, revisión y aceptación humana. Las decisiones recuperadas son antecedentes que deben contrastarse, no permisos nuevos. Un hash fija bytes, no acredita verdad ni autoridad. No presentar una autorrevisión como revisión independiente.

Cada fotografía debe indicar fecha, fuentes, alcance y límites; conservar los resultados desfavorables cuando formen parte de un expediente autorizado. No publicar un expediente solo porque esté disponible localmente.

## Edición y publicación

Documentación humana en español por defecto; nombres de archivos e identificadores nuevos en inglés. Cambios mínimos y enlaces relativos dentro del repositorio. Preservar contenido y cambios ajenos.

Commit, push, merge, cambios de visibilidad, releases y publicación requieren autorización humana explícita para el alcance. No inferirla del roadmap ni de documentos enlazados. No usar force-push para resolver divergencias.

Antes de publicar: revisar el diff íntegro, los archivos incluidos, los enlaces locales, la licencia preexistente y las exclusiones de docs/publication.md. Comprobar que no haya gitlinks (modo 160000), repositorios anidados, secretos, rutas personales ni datos privados. La lista de inclusión de .gitignore es una ayuda, no una barrera de seguridad.

Después de publicar, contrastar HEAD con la referencia remota e informar qué quedó publicado y qué no. No atribuir pruebas de software a una revisión documental.
