# **Manual de GIT**

## Agregar usuario
Configuración a  nivel global como me llamo

```shell
git config --global user.name "su_nombre"
```
Para verificar configuración (`git config --global user.name`)

Configuración a  nivel global mi correo en github
```shell
git config --global user.email "su_email"
```
Para verificar configuración (`git config --global user.email`)
## Almacenar credenciales GIT en caché

Puede habilitar la caché auxiliar de credenciales para los usuarios que deseen 
almacenar detalles de autorización mediante lo siguiente.

````shell
git config --global credential.helper cache
````

Si debe utilizar el asistente de credenciales, se recomienda almacenar en caché solo durante un tiempo
limitado para mayor seguridad. Por ejemplo, si va a trabajar hoy usando GIT durante 1 a 4 horas pero 
no lo tocará durante unas semanas, establezca la caducidad en 5 horas.
````shell
git config --global credential.helper "cache --timeout=18000"
````
Después de 5 horas, las credenciales se eliminarán, lo que protegerá su GIT.

## Imprimir detalles de configuración de GIT

Para confirmar los usuarios y detalles de la configuración de GIT, use el comando config –list
````shell
git config --list
````
A menos que se especifique, Git almacena detalles en el archivo `.gitconfig`


## Iniciar GIT
Inicia git en el directorio de trabajo.
````shell
git init
````
![git_init.png](..%2Fassets%2Fgit_init.png)
## Ver Status de GIT
````shell
git status
````
![git_status_1.png](..%2Fassets%2Fgit_status_1.png)
## Agregar un archivo al index área (stage) 
````shell
git add documento1
````
![git_add_document1.png](..%2Fassets%2Fgit_add_document1.png)
## Agregar todos los archivos al index área (stage) 
````shell
git add -A
````
ó
````shell
git add .
````
![git_add_A.png](..%2Fassets%2Fgit_add_A.png)
## Quitar archivos del index área (stage)   
````shell
git rm --cached documento2
````
![git_rm.png](..%2Fassets%2Fgit_rm.png)

## Revisar cambios 
````shell
git log
````
![git_log.png](..%2Fassets%2Fgit_log.png)
## Crear commit
````shell
git commit -m "segundo cambios en documento1"
````
![git_commit.png](..%2Fassets%2Fgit_commit.png)

## Regresar a un commit anterior 

![git_checkout_1.png](..%2Fassets%2Fgit_checkout_1.png)
````shell
git checkout d208f120a586e44f30d5834785b2d43929eb3db1
````
![git_checkout_2.png](..%2Fassets%2Fgit_checkout_2.png)
## Regresar al último commit
Cambiar nuevamente al último commit o cambiar al head, al master ó main(master es el último commit que se hizo)
````shell
git checkout master
````
![git_checkout_master.png](..%2Fassets%2Fgit_checkout_master.png)

## Resetear suave el commit
Se va a borra por ejemplo el tercer commit pero sin tocar los cambios ya realizados en los archivos.
````shell
git reset --soft d208f120a586e44f30d5834785b2d43929eb3db1
````
![git_reset_soft.png](..%2Fassets%2Fgit_reset_soft.png)

## Resetear duro el commit
Se va a borra el segundo commit y también borra todos los cambios realizados en los archivos.
````shell
git reset --hard 6a83bc637d9b14cb790fddf09ed65fdb212a9ea1
````
![git_hard.png](..%2Fassets%2Fgit_hard.png)
## Ver Ramas
````shell
git branch pruebas
````
![git_branch.png](..%2Fassets%2Fgit_branch.png)
## Crear ramas
````
git branch pruebas
````
![git_branch_pruebas.png](..%2Fassets%2Fgit_branch_pruebas.png)
## Funcionar ramas
````shell
git merge pruebas
````
![git_merge.png](..%2Fassets%2Fgit_merge.png)
## Borrar ramas
````shell
git branch pruebas -d
````
![git_borrar.png](..%2Fassets%2Fgit_borrar.png)
## Conectar Repo local a GITHUB
````
git remote add origin https://github.com/TU_REPO
````
![git_remote_add.png](..%2Fassets%2Fgit_remote_add.png)
## Subir las ramas a GITHUB
````
git push origin master
````
![git_push_1.png](..%2Fassets%2Fgit_push_1.png)
![git_push_2.png](..%2Fassets%2Fgit_push_2.png)
## Descargar cambios de GITHUB
````shell
git pull 
````
![git_pull.png](..%2Fassets%2Fgit_pull.png)

ó
````shell
 git pull <remote> <branch>
````
## Clonar un Repo de GITHUB
````shell
git clone https://github.com/jorgelgpz/alpha.git
````
![git_clone.png](..%2Fassets%2Fgit_clone.png)