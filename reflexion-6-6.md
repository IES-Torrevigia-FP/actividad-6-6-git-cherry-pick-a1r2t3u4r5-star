git cherry-pick sirve para copiar un commit concreto de una rama a otra, creando un nuevo commit con los mismos cambios.

La diferencia es que merge une ramas completas con todos sus commits, y rebase reorganiza los commits cambiando su historial. En cambio, cherry-pick solo trae lo que tú eliges.

Tres situaciones donde usarlo:
- Aplicar un hotfix en producción sin traer todo el desarrollo.
- Corregir un commit que hiciste en la rama equivocada.
- Reutilizar un cambio pequeño en varias ramas.

Se recomienda usarlo con moderación porque puede duplicar commits y hacer el historial más confuso si se usa mucho.
