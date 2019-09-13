# daw2

## Clase 1 
- Crear una cuenta en github
- Crear un nuevo repositorio: daw2
- instalar git  
- Si aparece un error "no se pudo bloquear /var/lib/dpkg/lock"... introuducir la siguiente instrucción: 
```
sudo fuser -vki /var/lib/dpkg/lock
```   
y volver a instalar git

```
sudo apt get install git
``` 
Instrucciones básicas git

-Clonar el repositorio remoto:
```
git clone url
```

-Ver estado del repositorio local:
```
git status
```
-Hacer un "commit" (comprometer) los cambios al repostiorio local:
```
git commit -am "comentario a la hora de subir el reopositorio"
```
-Subir (push) los cambios del repositorio local al repositorio remoto:
```
git push origin master
```
-Actualizar (pull) el repositorio local con los cambios desde el repositorio remoto:
```
git pull origin master
```

