# Checklist de evaluación - Hito 2

## Estado comprobado

- [x] Repositorio público en GitHub.
- [x] Nombre y descripción relacionados con el videojuego.
- [x] Rama estable `main`.
- [x] Rama de integración `develop`.
- [x] Rama `feature/escena-inicial`.
- [x] Merge de feature hacia develop.
- [x] Merge de develop hacia main.
- [x] Commits con mensajes descriptivos.
- [x] Proyecto creado con Unity 2D.
- [x] Carpetas `Assets/`, `Packages/` y `ProjectSettings/` versionadas.
- [x] `.gitignore` adecuado para Unity.
- [x] `Library/`, `Temp/`, `Logs/` y `UserSettings/` excluidos.
- [x] Archivos `.meta` incluidos.
- [x] Escena guardada en `Assets/Scenes/Nivel01.unity`.
- [x] Cámara ortográfica configurada.
- [x] Fondo visual relacionado con la temática.
- [x] Área inicial del campus.
- [x] Grid y Tilemaps presentes.
- [x] Suelo, senderos y edificio construidos con tiles.
- [x] Elementos decorativos y personaje provisional.
- [x] Assets organizados por tipo.
- [x] Assets originales documentados.
- [x] `README.md` creado con las secciones exigidas.
- [x] `BITACORA.md` creada.
- [x] Guía de defensa oral preparada.
- [x] Proyecto abierto y escena generada sin errores de compilación.

## Pendientes obligatorios

- [ ] Los tres colaboradores deben aceptar sus invitaciones de GitHub.
- [ ] Cada uno de los cuatro integrantes debe aparecer como colaborador.
- [ ] Cada integrante debe realizar al menos un commit real desde su propia cuenta.
- [ ] Las ramas de los compañeros deben integrarse en `develop`.
- [ ] Tras integrar los aportes, comprobar nuevamente la escena en Unity.
- [ ] Actualizar la bitácora para que coincida con el historial final de commits.
- [ ] Integrar la versión final de `develop` en `main`.
- [ ] Cada integrante debe practicar la defensa oral.
- [ ] Entregar la URL pública del repositorio.

## Orden recomendado para los aportes restantes

Para reducir conflictos, trabajar de uno en uno y crear cada rama desde la versión más reciente de `develop`.

### Aporte 1: fondo y decoración

1. Aceptar la invitación.
2. Clonar el repositorio.
3. Cambiar a `develop` y actualizarlo.
4. Crear `feature/fondo-campus`.
5. Agregar o modificar un elemento decorativo visible.
6. Guardar la escena.
7. Crear el commit `Agregar decoración al campus`.
8. Subir la rama y abrir un Pull Request hacia `develop`.
9. Integrar el Pull Request antes de iniciar el siguiente aporte visual.

### Aporte 2: tiles y escenario

1. Actualizar `develop` después del aporte anterior.
2. Crear `feature/tilemap-campus`.
3. Ampliar o modificar una sección del sendero usando Tilemap.
4. Guardar la escena.
5. Crear el commit `Ampliar sendero principal con Tilemap`.
6. Subir la rama y abrir un Pull Request hacia `develop`.
7. Integrar el Pull Request.

### Aporte 3: documentación

1. Actualizar `develop` después de los aportes visuales.
2. Crear `feature/documentacion`.
3. Registrar en `BITACORA.md` los aportes y problemas reales encontrados.
4. Revisar los datos de integrantes y el estado del proyecto en `README.md`.
5. Crear el commit `Actualizar README y bitácora del equipo`.
6. Subir la rama y abrir un Pull Request hacia `develop`.
7. Integrar el Pull Request.

## Revisión final del responsable del repositorio

1. Abrir GitHub y comprobar colaboradores, ramas, Pull Requests y autores de commits.
2. Descargar o clonar una copia limpia del repositorio.
3. Abrir la copia en Unity.
4. Abrir `Assets/Scenes/Nivel01.unity`.
5. Confirmar que el fondo y los Tilemaps sean visibles y que Console no tenga errores rojos.
6. Fusionar `develop` en `main`.
7. Confirmar que la URL pública abre el README sin iniciar sesión.

