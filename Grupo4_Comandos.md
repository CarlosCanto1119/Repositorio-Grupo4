# Grupo 4 – Comandos: [git Branch, git checkout]

## Integrantes
- Carlos Canto
- Sebastian Marín
- Roberto Quintero

## Explicación breve
### Comando 1: `git branch`
- ¿Qué hace?
El comando git branch se utiliza para crear, listar o eliminar ramas dentro de un repositorio. Con él puedes ver en qué rama te encuentras actualmente (marcada con un asterisco), así como crear nuevas ramas que sirven para trabajar en cambios de manera independiente sin afectar la rama principal.
- Ejemplo de uso:
git branch Grupo4

### Comando 2: `git checkout`
- ¿Qué hace?
El comando git checkout se utiliza principalmente para cambiar entre ramas dentro de un repositorio. Al hacerlo, Git actualiza el área de trabajo con el contenido de la rama seleccionada, lo que permite trabajar en diferentes versiones del proyecto sin afectar otras ramas. También puede usarse para restaurar archivos a un estado previo, pero su uso más común es navegar entre ramas.

- Ejemplo de uso:
git checkout Grupo4

## Actividad práctica guiada
1. Paso 1: Crear la carpeta para el repositorio (usar mkdir y cd)
2. git init
Resultado esperado: carpeta con repositorio inicializado.
3. Paso 2: crear un archivo inicial y hacer commit 

echo "Hola mundo" > archivo.txt
git add archivo.txt
git commit -m "Primer commit"

4. Paso 3: crear rama y cambiarse a ella
git branch "Nombre de la rama"
git checkout "Nombre de la rama"

## Mini Quiz
1. Cual paso es necesario para crear una rama sin errores (hacer commit)
2. Como cambiamos de rama (git checkout y el nombre de la rama)
3. Con que comando verificamos en que rama estamos (git branch)
