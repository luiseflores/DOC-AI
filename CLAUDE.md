# CLAUDE.md: Memoria Persistente de Claude

> Este archivo es lo que Claude Code lee automáticamente al arrancar para entender este
> repositorio. Se va actualizando a medida que el curso agrega skills y flujos de trabajo.

## Por qué existe

Claude no recuerda nada entre sesiones: cada vez que lo abres, empieza de cero. `CLAUDE.md`
resuelve eso: es el primer archivo que Claude lee al arrancar y le da el contexto del proyecto
sin que tengas que repetirlo cada vez.

## Qué es este repositorio

Repo de trabajo del curso **DOC-AI**: IA aplicada a las tareas administrativas de un médico.
Se construye por temas y solo contiene lo que el alumno ya vio en clase.
Temas dictados hasta ahora: ninguno.

## Estructura

- `README.md`: descripción del repo y estado actual.
- `CLAUDE.md`: este archivo.
- `.gitignore`: excluye `.env`, `node_modules/` y carpetas de datos reales.
- `temario/<tema>/`: material de cada clase dictada.
- `temario/apuntes/<tema>.md`: apuntes de cada clase.

## Reglas

- **Datos de pacientes:** nunca leer, generar ni versionar datos reales de pacientes. Los
  ejemplos usan siempre datos ficticios y se marcan como tales.
- **La IA asiste, el médico decide:** el contenido producido con IA (informes, cartas,
  resúmenes) es un borrador que el médico revisa y firma. No dar diagnósticos ni indicaciones
  clínicas como definitivos.
- **Audiencia:** médicos sin perfil técnico. Explicar en lenguaje simple, con ejemplos de la
  consulta diaria, y sin dar por sabido ningún concepto de programación.
- **Asistente de IA:** el curso trabaja únicamente con Claude (Claude Code).
- **Idioma:** español.

## Reglas de trabajo con Git

- Flujo diario: `git fetch` → `git status` → `git pull` al empezar; `git add .` →
  `git commit -m "mensaje"` → `git push` al terminar.
- Nunca versiones `.env`, credenciales ni datos de pacientes.

## Qué va a tener más adelante

Todavía no hay skills ni flujos de trabajo definidos en este repo: llegan en los próximos
temas del curso.
