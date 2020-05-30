 clase_cero_GitHub
====================

Este es un ejemplo de Github para la comunidad de #mejorandola

Una vez instalas GIT, debes configurarlo:

git config --global user.name "nombre de usuario"
git config --global user.email "user@dominio.com"

Generando tu public key:
$ssh-keygen
Leyendo tu llave para copiarla a GitHub:
catr ~/.ssh/id_rsa.pub

Arrancando tu proyecto:
git init
touch README.md
git add README.md
git commit -m "algun comentario de lo que se esta haciendo"
git push origin master

