Reporte paso 1 
dasav@LAPTOP-FP5B2HHG MINGW64 ~
$ pwd
/c/Users/dasav

*****************************************************************
Reporte paso 2
dasav@LAPTOP-FP5B2HHG MINGW64 ~
$ mkdir "Ejercicios"

*****************************************************************
Reporte paso 3
dasav@LAPTOP-FP5B2HHG MINGW64 ~
$ cd Ejercicios/

dasav@LAPTOP-FP5B2HHG MINGW64 ~/Ejercicios
*****************************************************************
Reporte paso 4
dasav@LAPTOP-FP5B2HHG MINGW64 ~/Ejercicios
$ code .

*****************************************************************
Reporte paso 5
dasav@LAPTOP-FP5B2HHG MINGW64 ~/Ejercicios
$ mkdir ejercicio1

Nota: Le paso indica crearla desde VScode, pero para dejar evidencia la cree desde la consola.

*****************************************************************
Reporte paso 6
dasav@LAPTOP-FP5B2HHG MINGW64 ~/Ejercicios
$ cd ejercicio1/

dasav@LAPTOP-FP5B2HHG MINGW64 ~/Ejercicios/ejercicio1
$ touch README.md

*****************************************************************
Reporte paso 7
dasav@LAPTOP-FP5B2HHG MINGW64 ~/Ejercicios/ejercicio1
$ git config --global user.name "David Sarria"

dasav@LAPTOP-FP5B2HHG MINGW64 ~/Ejercicios/ejercicio1
$ git config --global user.email "david.sarriav@gmail.com"

dasav@LAPTOP-FP5B2HHG MINGW64 ~/Ejercicios/ejercicio1
$ git config -l
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.email=david.sarriav@gmail.com
user.name=David Sarria

*****************************************************************
Reporte paso 8
dasav@LAPTOP-FP5B2HHG MINGW64 ~/Ejercicios/ejercicio1
$ cd ..

dasav@LAPTOP-FP5B2HHG MINGW64 ~/Ejercicios
$ git init
Initialized empty Git repository in C:/Users/dasav/Ejercicios/.git/

dasav@LAPTOP-FP5B2HHG MINGW64 ~/Ejercicios (master)
$ ls -a
./  ../  .git/  ejercicio1/

*****************************************************************
Reporte paso 9
dasav@LAPTOP-FP5B2HHG MINGW64 ~/Ejercicios (master)
$ git add .

dasav@LAPTOP-FP5B2HHG MINGW64 ~/Ejercicios (master)
$ git commit -m 'Version Inicial'
[master (root-commit) 2594a25] Version Inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ejercicio1/README.md