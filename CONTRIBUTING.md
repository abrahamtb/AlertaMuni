# Guía de contribución — AlertaMuni

## Ramas
- `main`: versión estable.
- `develop`: integración del equipo.
- `feature/<componente>-<codigo>-<descripcion>`: nueva funcionalidad.
- `fix/<componente>-<codigo>-<descripcion>`: corrección.
- `docs/<codigo>-<descripcion>`: documentación.

Ejemplos:
- `feature/backend-RF010-registrar-incidencia`
- `feature/mobile-RF010-registrar-incidencia`
- `feature/web-RF020-listar-incidencias`
- `fix/backend-CP012-validacion-estado`
- `docs/SRS-002-requisitos-funcionales`

## Flujo
1. Actualizar `develop`.
2. Crear una rama desde `develop`.
3. Trabajar únicamente la tarea asignada.
4. Realizar commits pequeños y descriptivos.
5. Hacer push de la rama.
6. Abrir Pull Request hacia `develop`.
7. Esperar revisión e integración.
8. No hacer push directo a `main` ni a `develop`.

## Commits
Formato recomendado:
`tipo(componente): descripción breve`

Tipos sugeridos:
- `feat`
- `fix`
- `docs`
- `test`
- `refactor`
- `chore`

Ejemplos:
- `feat(backend): registrar incidencia`
- `feat(mobile): consumir categorias`
- `fix(web): validar sesion expirada`

## Definición de terminado
Una tarea se considera terminada cuando:
- cumple los criterios de aceptación;
- fue probada;
- cuenta con Pull Request revisado;
- está integrada en `develop`;
- no presenta observaciones críticas abiertas;
- la documentación relacionada fue actualizada cuando corresponde.
