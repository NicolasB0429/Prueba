# Primeros Pasos con Git

Configuración de los primeros pasos con Git.

## Configuración Inicial

1. **Instalar Git:**
   - Asegúrate de tener Git instalado en tu máquina. Si no lo tienes, descárgalo e instálalo desde [https://git-scm.com/](https://git-scm.com/).

2. **Configurar Usuario y Correo Electrónico:**
   - Configura tu nombre de usuario y dirección de correo electrónico en Git. Esto será utilizado para identificar tus contribuciones.
     ```bash
     git config --global user.name "Tu Nombre"
     git config --global user.email "tu@email.com"
     ```

## Crear un Nuevo Repositorio

3. **Crear un Nuevo Repositorio:**
   - Inicia un nuevo repositorio Git en tu proyecto existente o crea uno desde cero.
     ```bash
     git init
     ```

4. **Agregar Archivos al Repositorio:**
   - Agrega los archivos de tu proyecto al repositorio.
     ```bash
     git add .
     ```

5. **Realizar el Primer Commit:**
   - Realiza el primer commit para guardar los cambios.
     ```bash
     git commit -m "Primer commit"
     ```

## Trabajar con Ramas (Branches)

6. **Crear y Cambiar de Rama:**
   - Crea una nueva rama para trabajar en una nueva funcionalidad.
     ```bash
     git branch nueva-funcionalidad
     git checkout nueva-funcionalidad
     ```

7. **Hacer Cambios y Realizar un Merge:**
   - Realiza cambios en la nueva rama y luego intégralos a la rama principal (master).
     ```bash
     git checkout master
     git merge nueva-funcionalidad
     ```

## Sincronización con Repositorio Remoto

8. **Conectar a Repositorio Remoto:**
   - Conéctate a un repositorio remoto (por ejemplo, en GitHub).
     ```bash
     git remote add origin URL_DEL_REPOSITORIO
     ```

9. **Subir Cambios al Repositorio Remoto:**
   - Sube tus cambios al repositorio remoto.
     ```bash
     git push -u origin master
     ```

## Extras

10. **Obtener Cambios del Repositorio Remoto:**
    - Obtén los cambios realizados por otros colaboradores.
      ```bash
      git pull origin master
      ```

¡Listo! Estos son los primeros pasos que se deben hacer para principiantes.

###NOTA: Despues de que ya se entienden los conceptos de manejo de git, se pueden instalar GUI o clientes, lo cual es una ayuda importante: [[https://git-scm.com/](https://git-scm.com/downloads/guis/)]([https://git-scm.com/](https://git-scm.com/downloads/guis/)https://git-scm.com/downloads/guis/).
