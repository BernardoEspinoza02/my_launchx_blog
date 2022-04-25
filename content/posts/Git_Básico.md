---
title: "Git Básico"
date: 2022-04-25
description: 'Comandos básicos de Git aprendidos en LaunhX'
---

## ¿Que es Git? 🤖

Git es un sistema de control de versiones, sus siglas en ingles (VCS)

## ¿Ques es un Control de Versiones?

Un control de versiones es un sistema que va registrando los cambios realizados ya sea en un archivo o un conjunto de archivos a lo largo del tiempo de tal manera que se puedan recuperar las versiones especificas más delante de ser necesario. 

> Nota: Git y GitHub no es lo mismo. 👀
> 
> Nota: GitHub es una plataforma donde puedes alojar proyectos utilizando un VCS. 👀

## ✔ Beneficios al usar un sistema de control de versiones 🏆
 - Regresar a versiones anteriores de tus archivos.
 - Regresar a versiones de un proyecto completo.
 - Comparar cambios en el tiempo
 - Ver quien modifico los archivos y en que tiempo
 - Corregir problemas pudiendo regresar en algun punto en el tiempo cuando se modifico
 - Si llegas a arruinar o perder un archivo sera posible recuperarlo facilmente. 

**Git** tiene 3 estados principales:
 - Confirmado: Significa que los datos están almacenados de manera segura en tu base de datos local.
 - Modificado: Significa que has modificado el archivo pero todavía no lo has confirmado a tu base de datos.
 - Preparado: Significa que has marcado un archivo modificado en su versión actual para que vayya en tu próxima confirmacíon.{

> git esta para SO. linux, mac y windows
> Nota: Puedes descargarlo desde la siguiente liga [Git Descarga]( https://git-scm.com/downloads)

## Comandos basicos de git

- Revisar que esta instalado git y que version tines instalado 
> $git --version

- Enlasar nuestro git con GitHub
> $git config --global user.name "Nombre de perfil de github"
> 
> $git cinfig --global user.email "e-mail de perfil"
> 
> nota: Los datos ingresados van sin comillas. 

- Como cualquier programa git tambien tiene la seccion de ayuda, puedes ingresar el codigo de tres formas, posterior a eso se abrira una pagina web con la documentacion solicitada:

> $git help "comando"
>
> $ git "comando" --help
>
> $ man git-"comando"

### Crear un nuevo Repositorio

- Crear una carpeta donde se guardara el repositorio, e inicializar git con el siguiente comando. En la carpeta de tu proyecto si tienes activo cisualizar archivos ocultos podras ver una carpeta de .git oculta 
> $ git init

- Para revisar si tienes archivos no registrados 
> $git status

- Para agregar cambios de los archivos puede ser todos los cambios juntos o por archivo por archivo.
> $git add .   // Esto es para todos los archivos
> 
> $git add "nombre del archivo" // Esto es para un archivoi en especifico

- Para agregar comentarios a cada cambio que se va realizando 
> $git commit -m "Comentario" // El comentario si va entre "".'

- Para visualizar los comentarios que se han realizado, va del mas reciente al mas antiguo as como el numero de registro de cada commit.
> $git log 

### Para clonar un reporsitorio desde GitHub
- Para esto necesitamos el URL del repositorio o la llave de SSH 
> $git clone "Url o SSH " 


### Otros comandos
- Para visualizar cambios que se han realizado en el archivo 
> $git show 

- Para visualizar diferencias entre archivos locales y en linea
> $git diff 




