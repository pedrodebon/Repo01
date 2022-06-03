# Read me: Creación de repositio

## Indice: 
* Creación del repositorio en local y el readme.md
* Configurar el repositorio
  * Add
  * Commit
  * Push
* Conectar el repositorio a GitHub
  * GitHub
  * GitBash
* Subir todos los cambios al repositorio remoto
  * Local a Remoto
  * Remoto a Local
  
 ---
  ### Creación del repositorio en local y el readme.md
  El primer paso para crear nuestro repositorio sera crear una carpeta haciendo click secundario>Nuevo>Carpeta o podemos 
  hacerlo a traves de GitBash con el comando mkdir "Repo01" en el directorio que queramos. (En GitBash nos moveremos a traves de los directorios con el comando cd)
  
  Captura del comando mkdir:  
  ![No se ha podido cargar la imagen](https://github.com/pedrodebon/Repo01/blob/main/Img/1.%20mkdir.JPG?raw=true "")
  
  En Visual Studio Code creamos un nuevo fichero con extension md (MarkDown) y lo llamaremos Readme.md y lo usaremos para explicar paso a paso la creacion 
  y configuracion de un repertorio a GitHub. 
  
  ### Configurar el repositorio
  Una vez dentro del directorio Repo01, iniciaremos el repositorio con el comando Git Init como muestra la siguiente captura:   
  ![No se ha podido cargar la imagen](https://github.com/pedrodebon/Repo01/blob/main/Img/2.%20init.JPG?raw=true "")
  
  Ahora vamos a subir el Repo01 al repositorio remoto desde el repositorio local con los siguientes pasos: 
  #### Add
  El primer paso para subir todos los cambios sera el comando Git Add, podemos subir un archivo concreto especificando el archivo ("ejemplo.txt") o un general de 
  todo con un "." como muestra la siguiente captura:  
  ![No se ha podido cargar la imagen](https://github.com/pedrodebon/Repo01/blob/main/Img/3.%20add.JPG?raw=true "")
  
  Todos los archivos del directorio Repo01 pasaran a la Staging Area a la espera de hacer el commit. 
  
  #### Commit
  El comando Git Commit es una confirmación de lo que queremos subir al repositorio remoto a la falta del ultimo "empujon". En este comando, aconsejo fervientemente 
  detallar una descripcion del commit para todos las personas que trabajen con el mismo repositorio o uno mismo sepan los cambios que se han realizado.  
  ![No se ha podido cargar la imagen](https://github.com/pedrodebon/Repo01/blob/main/Img/5.%20commit.JPG?raw=true "")
  
  #### Push
  El comando Git Push es el ultimo paso para subir todos los archivos, comiteados anteriormente,  al repositorio remoto. En nuestro caso como aun no hemos configurado 
  el repositorio remoto, tendremos que configurarlo antes de volver a hacer un nuevo push sin que nos de el siguiente error:  
  ![No se ha podido cargar la imagen](https://github.com/pedrodebon/Repo01/blob/main/Img/6.%20push.JPG?raw=true "")
  
  ### Conectar el repositorio a GitHub
  En este punto, tendremos que trabajar con neustro repositorio remoto en GitHub y Git Bash para conectar la parte remota con la local. 
  #### GitHub
  Crearemos una cuenta en GitHub siguiendo este [enlace](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home). Una 
  vez creada la cuenta, crearemos un nuevo repositorio llamado Repo01 como muestra la siguietne captura:  
  ![No se ha podido cargar la imagen](https://github.com/pedrodebon/Repo01/blob/main/Img/10.%20new%20repo.JPG?raw=true "")
  
  Una vez creado el repositorio, tenemos variedad de eleccion para conectar local y remoto como muestra la captura:  
  ![No se ha podido cargar la imagen](https://github.com/pedrodebon/Repo01/blob/main/Img/11.%20conexion.JPG?raw=true "")
  
  En nuestor caso, haremos un Push de un repositorio ya existente. 
  
  #### GitBash
  Como marca el paso anterior, seguiremos una serie de comandos para conectar ambos repositorios. Estos comandos la propia pagina de GitHub nos los facilita
  pero tendremos que usarlos a traves de Git Bash. Adjunto una serie de capturas para mostrar los resultados.  
  ![No se ha podido cargar la imagen](https://github.com/pedrodebon/Repo01/blob/main/Img/7.%20remote.JPG?raw=true "")  
  ![No se ha podido cargar la imagen](https://github.com/pedrodebon/Repo01/blob/main/Img/8.%20branch.JPG?raw=true "")  
  ![No se ha podido cargar la imagen](https://github.com/pedrodebon/Repo01/blob/main/Img/9.%20push%20main.JPG?raw=true "")
  
  Ahora ya tendremos nuestro repositorio local y remoto conectados y actualizados. 
  
  ### Subir todos los cambios al repositorio remoto
  El ultimo paso es mostrar los resultados de los cambios que hemos ido haciendo desde el repositorio local al remoto y viceversa. 
  
  #### Local a Remoto
  
  
  #### Remoto a Local
  GitHub te permite modificar ciertos archivos desde su pagina como los .txt o .md. En la siguiente captura, he hecho una serie de modificaciones al 
  archivo readme.md y con el comando Git Pull traere todos los cambios que he hecho en remoto hasta el local. 
  
  Ejemplo de modificacion desde GitHub:  
  ![No se ha podido cargar la imagen](https://github.com/pedrodebon/Repo01/blob/main/Img/11.%20conexion.JPG?raw=true "")
  
  El resultado que muestra Git Bash tras el pull con los nuevos cambios.  
  ![No se ha podido cargar la imagen](https://github.com/pedrodebon/Repo01/blob/main/Img/12.%20remoto%20a%20local.JPG?raw=true "")
  
