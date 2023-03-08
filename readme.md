Abrir la consola e imprimir la ubicación actual.
pwd


Crear una carpeta llamada ejercicios desde la consola.
PS C:\Users\Cristian\desktop\mkreal> mkdir ejercicios

Cambiar la ubicación a la nueva carpeta que crearon. 
PS C:\Users\Cristian\desktop\mkreal> move ejercicios ..

Abrir la carpeta con VSCode.
PS C:\Users\Cristian\desktop\ejercicios> code .
En VSCode crear una carpeta ejercicio1.
PS C:\Users\Cristian\desktop\ejercicios> mkdir ejercicios1 

Crear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1.

PS C:\Users\Cristian\desktop\ejercicios> cd ejercicios1
PS C:\Users\Cristian\desktop\ejercicios\ejercicios1> mkdir README.MD

Configurar nombre e email globalmente en git.
git config --global user.name Cristian Oviedo
git config --global user.mail camilooviedo1026@gmail.com

Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios.

PS C:\Users\Cristian\Desktop\mkreal\ejercicios1> git init
