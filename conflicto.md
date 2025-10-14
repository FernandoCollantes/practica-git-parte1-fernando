# Resolución de Conflictos

## ¿Qué pasó?
Intenté fusionar dos ramas que habían modificado la misma línea:
- main: "# Mis Notas y Tareas - Versión Final"
- feature-conflicto: "# Mis Notas y Tareas IMPORTANTE"

## ¿Cómo se resolvió?
1. Git detectó el conflicto automáticamente
2. Abrí el archivo y vi los marcadores <<<<<<<, =======, >>>>>>>
3. Elegí combinar ambas versiones: "# Mis Notas y Tareas - Versión Final IMPORTANTE"
4. Elimité los marcadores de conflicto
5. Hice git add, git commit y git push

## Lecciones aprendidas
- Los conflictos ocurren cuando dos ramas editan la misma línea
- Git no sabe cuál versión es correcta, por eso pide ayuda manual
- Siempre revisar el archivo después de un merge

