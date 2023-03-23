# Como abrir tu rama:
Paso 1:
Podrás visualizar en la esquina superior derecha dice "Code", lo seleccionas y copias el link del repositorio

Paso 2:
Clona el repositorio en tu computadora local (si aún no lo has hecho) usando el comando git clone. Reemplaza <repository_url> con la URL del repositorio en GitHub. 
Por ejemplo:

git clone https://github.com/usuario/proyecto.git

Paso 3:
Cambia al directorio del repositorio clonado:

cd proyecto

Paso 4:
Cambia a la rama existente en la que deseas trabajar. Reemplaza <your_branch> con el nombre de la rama existente:

git checkout <your_branch>

y listo ya puedes porgramar tu rama.

# Como subir tu rama al Github
Paso 1:
en la rama existente y puedes comenzar a realizar cambios en los archivos del proyecto. Después de hacer cambios, agrégales un seguimiento y haz un commit con los siguientes comandos:

git add

git commit -m "Descripción de los cambios realizados"
  
Paso 2:
Una vez que hayas realizado los cambios y commits necesarios, envía tu rama al repositorio remoto:

git push
