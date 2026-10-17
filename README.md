# DOC-AI

Repositorio de trabajo del curso **DOC-AI**: inteligencia artificial aplicada a las tareas
administrativas del médico (documentación clínica, informes, cartas, agenda, correos,
organización de la consulta). Se construye de forma incremental, tema a tema: **solo contiene
lo que ya viste en clase**. Después de cada clase se agregan las piezas correspondientes a ese
tema.

## Estado actual

Temas dictados: **ninguno todavía**.

## Estructura

```
DOC-AI/
├── README.md, CLAUDE.md              # este archivo y la memoria de Claude
├── .gitignore                        # qué NO versiona Git
└── temario/                          # material de cada clase ya dictada
    └── apuntes/                      # apuntes tomados durante las clases, un .md por tema
```

## Privacidad

Este repositorio **nunca** debe contener datos reales de pacientes (nombres, documentos,
historias clínicas, resultados, imágenes). Todos los ejemplos del curso usan datos ficticios.

## Cómo se actualiza

Cada vez que se dicta una clase se agrega al repo la carpeta de ese tema en `temario/`, sus
apuntes en `temario/apuntes/` y las herramientas o archivos que esa clase habilita. Haz
`git pull` al empezar cada día para traer lo nuevo.
