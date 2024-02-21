# Comando para listar las ramas de mi repositorio

git branch 
git branch -v

# Comando para crear una rama
<!-- para crear una rama no se puede utilizar caracteres especiales ni espacios -->
git branch nombre_rama

# Comando para cambiar de ramas

git checkout nombre_rama

<!-- otra opción con switch -->
git switch nombre_rama

<!-- Crea la rama y hace el cambio -->
git checkout -v nombre_rama

# Comando para eliminar una rama

git branch -D nombre_rama

# Comando para cambiar el nombre de una rama

git branch -M nuevo_nombre
