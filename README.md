# Archivo .gitignore
### El archivo .gitignore es un archivo de texto que le dice a Git cuales archivos o carpetas ignorar en un determinado proyecto.
- Es conveniente incluir el archivo .gitignore en todo repositorio para así tener la posibilidad de ignorar todo aquel archivo o carpeta que no sea necesario incluir.
- Un archivo .gitignore puede ser local (que pueda ignorar a elementos de un solo repositorio) o global (capaz de ignorar elementos de todos los repositorios). Para crear un archivo .gitignore local, se debe crear un archivo de texto llamado .gitignore (incluyendo el .), y a partir de ahí se modifica el archivo como sea necesario; cada linea debe listar un archivo o carpeta adicional que se quiera ignorar por Git.

A la hora de utilizar el archivo para ignorar un elemento, se emplean ciertos símbolos:
	* "*" se utiliza para ignorar a todos los elementos de una extensión en específico.
	* "/" se utiliza para ignorar el camino relativo al archivo .gitignore.
	* "#" se utiliza para añadir comentarios en el archivo .gitignore.

