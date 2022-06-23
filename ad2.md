# Actividad dirigida 2

En esta actividad dirigida 2 convertimos nuestro repositorio en una web servida desde **Github**. Para conseguirlo usamos la funcionalidad de Github para funcionar como servidor de **git** y como servidor **web**.

## Pasos realizados

- Antes de iniciar esta parte cree esta ad2.md directamente en añadir archivo en Github.
- El siguiente paso que hice fue activar la configuración de mi repositorio en la opción ***"Pages"*** con la siguiente URL que cambié usando mi repositorio de Nebrija <https://github.com/nebrijas/Alejorego-web/settings/pages>.
- En branch elegí **Main** y en folder **root**.
- Al activar esa opción obtuve una web con un archivo index.html cuyo contenido es el del **README** <https://nebrijas.github.io/Alejorego-web/>.
- Realizada esta tarea pasé a la segunda parte para usar **git bash**.
- En git bash escribí **pwd** y le dí enter. Seguidamente escribí **git clone** <https://github.com/nebrijas/Alejorego-web> para modificar el repositorio y clonar la carpeta.
- Escribí Alejorego-web/, enter, para cambiar por el de mi fichero.
- El siguiente paso fue escribir **ls** para visualizar los archivos de la carpeta.
- Puse **git config** user.name, el usuario de Github y enter. Me dirigí a través del navegador a <https://github.com/settings/tokens> para generar el token, puse por nombre ped2, 60 días, generar token, copié el token y regresé al Git bash.
- Una vez allí escribí echo y entre comillas el token, para crear el archivo oculto.
- Escribí el README.md ad1.md.
- Luego escribí nano README para modificar ese archivo poniendo un título.
- Para salir le di a CTRL + X, guardé y al salir escribí git status y al dar enter apareció la carpeta modificada.
- Procedí a escribir git add ad1.md y dar enter. Seguido de git commit-m "añado ad1.md" y enter.
- Finalmente escribí **git push** para comprobar que la ad1.md aparecía en la nueva carpeta y en el repositorio.
