# mi-primer-repositorio-
Git es un sistema de control de versiones distribuido que permite a los desarrolladores gestionar y registrar cambios en proyectos de software. Facilita la colaboración, el seguimiento de cambios y la gestión de ramas, asegurando un desarrollo más organizado y eficiente.
A diferencia de los sistemas centralizados (como SVN), Git permite trabajar sin conexión
Las ramas permiten desarrollar nuevas funcionalidades o corregir errores sin afectar la rama principal.
Que Git es la herramienta de control de versiones, mientras que GitHub es una plataforma que aloja repositorios Git en la nube
Comandos básicos de Git: Incluyen git init, git clone, git add, git commit, git push, git pull, git branch, git checkout y git merge, fundamentales para trabajar con repositorios.
Los repositorios pueden ser locales (almacenados en la máquina del usuario) o remotos (hospedados en GitHub u otras plataformas), permitiendo sincronizar cambios entre múltiples desarrolladores.
Issues en GitHub sirven para reportar errores, proponer mejoras y gestionar tareas dentro de un proyecto. Son esenciales para la organización y el seguimiento del progreso.
Claves SSH en GitHub se utiliza para autenticarse de forma segura y sin necesidad de ingresar credenciales manualmente, facilitando el uso de Git con repositorios remotos.

Configuración Inicial
git config --global user.name "Tu Nombre" → Configura el nombre del usuario.
git config --global user.email "tu@email.com" → Configura el correo del usuario.
git config --list → Muestra la configuración actual de Git.
Inicialización y Clonación
git init → Inicializa un nuevo repositorio en el directorio actual.
git clone <URL> → Clona un repositorio remoto en tu máquina local.
Seguimiento y Estado
git status → Muestra el estado actual del repositorio (archivos modificados, en staging, etc.).
git log → Muestra el historial de commits del repositorio.
git diff → Muestra las diferencias entre archivos modificados y el último commit.
Añadir y Confirmar Cambios
git add <archivo> → Añade un archivo específico al área de staging.
git add . → Añade todos los archivos modificados al área de staging.
git commit -m "Mensaje" → Guarda los cambios en el historial con un mensaje descriptivo.
git commit --amend -m "Nuevo mensaje" → Modifica el último commit.
Trabajo con Ramas
git branch → Lista todas las ramas del repositorio.
git branch <nombre_rama> → Crea una nueva rama.
git checkout <nombre_rama> → Cambia a otra rama.
git checkout -b <nombre_rama> → Crea y cambia a una nueva rama.
git merge <rama> → Fusiona la rama especificada con la actual.
git branch -d <nombre_rama> → Elimina una rama local.
Sincronización con Repositorios Remotos
git remote add origin <URL> → Asocia un repositorio local con un remoto.
git remote -v → Lista los repositorios remotos asociados.
git push -u origin <rama> → Envía los commits al repositorio remoto.
git pull origin <rama> → Descarga y fusiona los cambios del repositorio remoto.
git fetch → Descarga cambios del repositorio remoto sin fusionarlos automáticamente.
Deshacer Cambios y Restaurar Versiones
git reset --soft <commit_id> → Deshace commits manteniendo los cambios en staging.
git reset --hard <commit_id> → Revierte el repositorio a un estado anterior, eliminando cambios.
git revert <commit_id> → Crea un commit que revierte los cambios de otro commit.
git checkout -- <archivo> → Revierte los cambios de un archivo al último commit guardado.
Etiquetas (Tags)
git tag <nombre_tag> → Crea una etiqueta en el commit actual.
git tag -a <nombre_tag> -m "Mensaje" → Crea una etiqueta anotada con un mensaje.
git push origin <nombre_tag> → Sube una etiqueta al repositorio remoto.
Otros Comandos Útiles
git stash → Guarda temporalmente cambios sin comprometerlos.
git stash pop → Restaura los cambios guardados con git stash.
git show <commit_id> → Muestra información detallada de un commit.
