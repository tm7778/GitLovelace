# Comando para conectar mi git local con git en la nube

git remote add nombre_conexion url_conexion

# Comando para clonar o traer un repositorio de git remoto

git clone url_conexion

# Comando para listar las conexiones remotas

git remote -v

# Comando para eliminar una conexión remota 

git remote remove nombre_conexion

# Comando para enviar información al git remoto
<!-- Este comando es para subirlo a la rama main del repositorio, sin especificar -->
git push
<!-- Este comando es para subirlo dependiendo de la conexión que necesitas y especificar a que rama se dirige -->
git push nombre_conexion nombre_rama

git -u nombre_conexion nombre_rama

git push --all

# Comando para obtener cambios o la información que hay en el git remoto

git pull
git pull nombre_conexion nombre_rama

