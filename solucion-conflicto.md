# Parte 3-Solución de conflicto

Se generó un conflicto en el archivo "src/controllers/user.controller.js" al intentar fusionar la rama "conflicto" con "main".

- En la rama `conflicto` se agregó la línea: `Cambio en la rama conflicto`
- En la rama `main` se agregó la línea: `Cambio hecho en main`

Al hacer `git merge conflicto`, Git detectó conflicto porque el mismo archivo fue modificado en ambas ramas.

# solucion
Se editó el archivo manualmente combinando ambas líneas, quedando así:

// Cambio hecho en main
// Cambio en la rama conflicto
