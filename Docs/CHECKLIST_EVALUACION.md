# Checklist de evaluación - Hito 2

## Estado comprobado

- [x] Repositorio público en GitHub.
- [x] Nombre y descripción relacionados con el videojuego.
- [x] Rama estable `main`.
- [x] Rama de integración `develop`.
- [x] Rama `feature/escena-inicial`.
- [x] Rama `feature/fondo-campus` preparada para Cristopher.
- [x] Rama `feature/tilemap-campus` preparada para Galilea.
- [x] Rama `feature/documentacion` preparada para Alex Joel.
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
- [x] Los tres colaboradores aceptaron sus invitaciones de GitHub.
- [x] Los cuatro integrantes aparecen como colaboradores.

## Pendientes obligatorios

- [ ] Cada integrante debe realizar al menos un commit real desde su propia cuenta.
- [ ] Las ramas de los compañeros deben integrarse en `develop`.
- [ ] Tras integrar los aportes, comprobar nuevamente la escena en Unity.
- [ ] Actualizar la bitácora para que coincida con el historial final de commits.
- [ ] Integrar la versión final de `develop` en `main`.
- [ ] Cada integrante debe practicar la defensa oral.
- [ ] Entregar la URL pública del repositorio.

## Orden recomendado para los aportes restantes

Las ramas ya están preparadas desde la versión más reciente de `develop`. Para reducir conflictos en la escena de Unity, trabajar de uno en uno y fusionar cada aporte antes de iniciar el siguiente cambio visual.

### Aporte 1: fondo y decoración

1. Clonar el repositorio.
2. Cambiar a `feature/fondo-campus` y actualizar la rama.
3. Agregar o modificar un elemento decorativo visible.
4. Guardar la escena.
5. Crear el commit `Agregar decoración al campus`.
6. Subir la rama y abrir un Pull Request hacia `develop`.
7. Integrar el Pull Request antes de iniciar el siguiente aporte visual.

### Aporte 2: tiles y escenario

1. Esperar a que el aporte anterior esté integrado en `develop`.
2. Actualizar `feature/tilemap-campus` con la versión nueva de `develop`.
3. Ampliar o modificar una sección del sendero usando Tilemap.
4. Guardar la escena.
5. Crear el commit `Ampliar sendero principal con Tilemap`.
6. Subir la rama y abrir un Pull Request hacia `develop`.
7. Integrar el Pull Request.

### Aporte 3: documentación

1. Esperar a que los aportes visuales estén integrados en `develop`.
2. Actualizar `feature/documentacion` con la versión nueva de `develop`.
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
