## Git Practice

Usaremos este repositorio para practicar todo tipo de commandos en git y como usarlos para resolver ciertos errores.
Esperemos que os lo paséis bien!

Fefy

### Comandos
* Clonar Repositorio: ```git clone <repository-url>```
* Crear Rama: ```git checkout -b <branch-name>```
* Moverse a otra Rama: ```git checkout <branch-name> | git switch <branch-name>```
* Añadir Cambios: ```git add <file-name>```
* Commit Cambios: ```git commit -m "commit message"```
* Push Rama: ```git push origin <branch-name>```
* Pull Cambios: ```git pull origin main```
* Resolver Conflictos: Edit manualmente, después ```git add```, ```git commit```
* Hacer Merge, ejemplo merge rama test a main: 
  * Asegúrate de estar en la rama a la que quieras hacer el merge ```git switch main```
  * Pull the los últimos cambios de esa rama ```git pull origin main```
  * Merge ```git merge test```


### Enlaces de interés

* [Juego para aprender Git](https://learngitbranching.js.org/?locale=es_ES)
* [GitHub ‘cheat sheet’](https://github.github.com/training-kit/downloads/es_ES/github-git-cheat-sheet/)
* [Tutorial de Git en terminal](https://tutorials-codebar-io.translate.goog/version-control/command-line/tutorial.html?_x_tr_sch=http&_x_tr_sl=auto&_x_tr_tl=es&_x_tr_hl=en&_x_tr_pto=wapp)
* [Consejos para solucionar errores frecuentes de Git](https://ohshitgit.com/es)
* [Mensajes de commit profesionales](http://tomasdelvechio.github.io/old/440/)
