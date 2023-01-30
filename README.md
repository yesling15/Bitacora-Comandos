# Bitácora de Comandos
Bitácora de Comandos - Sistemas Operativos
| Comando | Descripción | Ejemplo de uso |
| --- | --- | --- |
| `clear` | Limpia la ventana de la consola. | `clear` para eliminar todas las líneas de los comandos que se corrieron anteriormente y tener más espacio para los nuevos. |
| `sudo apt update` | Busca actualizaciones pendientes en internet de los paquetes instalados en la máquina. | `sudo apt update` para verificar si una aplicación está desactualizada. |
| `sudo apt upgrade` | Actualiza los paquetes instalados en la máquina. | `sudo apt upgrade` para actualizar los paquetes que el comando `sudo apt update` encontró desactualizados.  |
| `sudo apt install` | Instala paquetes en la máquina, por ejemplo, aplicaciones. | `sudo apt install obs-studio` para instalar la aplicación llamada OBS Studio. |
| `sudo apt search` | Busca un paquete dentro del repositorio de Ubuntu. | `sudo apt search neofetch` para buscar el paquete llamado Neofetch. |
| `ls <directorio>` | Muestra los archivos del directorio indicado, si no se establece el directorio muestra los de la carpeta actual. | `ls ~/Personal` para mostrar todos los archivos dentro de la carpeta Personal. |
| `sl` | Muestra una animación de un tren. | Usualmente es el resultado de escribir el comando `ls` erróneamente. |
| `sudo rm -RF` | Elimina archivos vacíos sin consultar, por lo que se debe usar muy cuidadosamente para evitar pérdidas de información o daños en la máquina. | `sudo rm -RF` para liberar espacio. |
| `ps -aux` | Muestra la lista de procesos que están ejecutándose. | `ps -aux` para saber cuáles aplicaciones se están ejecutando de fondo. |
| `sudo kill -9 ID` | Termina un proceso que se esté ejecutando, indicando su ID. | `sudo kill -9 54178` para cerrar Firefox.|
| `top` | Muestra los procesos que se estén ejecutando en tiempo real y su consumo de recursos. | `top` para saber si un proceso está corriendo en ese momento. |
| `htop` | Misma funcionalidad que `top`, solo que incluye una interfaz más agradable al usuario. | `htop` para saber la cantidad de CPU que consume cada proceso. |
| `pstree` | Permite visualizar el árbol de procesos que se estén ejecutando. | `pstree` para saber cuáles procesos están enlazados entre sí.  |
