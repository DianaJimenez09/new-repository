# PASOS PARA SUBIR UN PROYECTOR A GIT

En primer lugar debemos tener descargado git en la terminal, una vez lo tengamos, empezamos:

1. En primer lugar, ejecutaremos: git init (en la terminal). Esto inicializará el repositorio que tenemos en nuestro pc local.

2. En segundo lugar, ejecutaremos: git add .
   Esto subira los archivos al stage

3. En tercer lugar, para ver en qué estado de modificación han quedado nuestros archivos, es recomendable ejecutar el comando: git status
   Esto nos enseñara nuestras modificaciones realizadas

4. En cuarto lugar, ejecutaremos: git commit -m"insertar mensaje"
   Esto preparará los cambios añadidos en la carpeta de nuestro sistema para cuando lo subamos a GitHub. En insertar mensaje podemos escribir mensaje de confirmación relevante.

5. Es recomendable que antes de subir nuestro repositorio a la nube, que volvamos a hacer un git status para comprobar que lo que tenemos está en orden.

6. Y en último lugar, subiremos nuestro repositorio mediante el comando: git push
