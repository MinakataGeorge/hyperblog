#This is hyperblog
Hola
>You are now on my blog

> *1. git log --oneline - Te muestra el id commit y el título del commit.
2. git log --decorate- Te muestra donde se encuentra el head point en el log.
3. git log --stat - Explica el número de líneas que se cambiaron brevemente.
4. git log -p- Explica el número de líneas que se cambiaron y te muestra que se cambió en el contenido.
5. git shortlog - Indica que commits ha realizado un usuario, mostrando el usuario y el titulo de sus commits.
6. git log --graph --oneline --decorate y
7. git log --pretty=format:"%cn hizo un commit %h el dia %cd" - Muestra mensajes personalizados de los commits.
8. git log -3 - Limitamos el número de commits.
9. git log --after=“2018-1-2” ,
10. git log --after=“today” y
11. git log --after=“2018-1-2” --before=“today” - Commits para localizar por fechas.
12. git log --author=“Name Author” - Commits realizados por autor que cumplan exactamente con el nombre.
13. git log --grep=“INVIE” - Busca los commits que cumplan tal cual está escrito entre las comillas.
14. git log --grep=“INVIE” –i- Busca los commits que cumplan sin importar mayúsculas o minúsculas.
15. git log – index.html- Busca los commits en un archivo en específico.
16. git log -S “Por contenido”- Buscar los commits con el contenido dentro del archivo.
17. git log > log.txt - guardar los logs en un archivo txt.*