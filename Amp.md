# Cómo instalar la pila Linux, Apache, MySQL y PHP (LAMP) en Ubuntu
### Introducción
Una pila “LAMP” es un conjunto de aplicaciones de software de código abierto que se suelen instalar juntas para que un servidor pueda alojar aplicaciones y sitios web dinámicos escritos en PHP. Este término es en realidad un acrónimo que representa al sistema operativo Linux, con el servidor web Apache. Los datos del sitio se almacenan en una base de datos MySQL y el contenido dinámico se procesa mediante PHP.

En esta guía, instalaremos una pila LAMP en un servidor Ubuntu 20.04 o superior.

## Paso 1: Instalar Apache y actualizar el firewall

El servidor web Apache está entre los más populares del mundo. Está bien documentado, tiene una comunidad de usuarios activa y ha sido muy utilizado durante gran parte de la historia de la web, por lo que es una excelente opción predeterminada para alojar sitios web.

Instale Apache usando el administrador de paquetes de Ubuntu, apt:

`$ sudo apt update`
`$ sudo apt install apache2`
