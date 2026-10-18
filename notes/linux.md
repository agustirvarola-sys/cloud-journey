# Apuntes de Linux

## Bandit (OverTheWire)
Juego para practicar Linux: en cada nivel hay que encontrar con comandos la contraseña del nivel siguiente.
- Conexión: `ssh banditN@bandit.labs.overthewire.org -p 2220`
- La contraseña que encontrás en el nivel N sirve para entrar al nivel N+1.

## Comandos
| Comando | Qué hace |
| --- | --- |
| `ls` | Lista los archivos de la carpeta |
| `cat archivo` | Muestra el contenido de un archivo |
| `cat ./-` | Lee un archivo llamado `-`. Con `-` solo, Linux entiende "leé del teclado"; `./` indica "el archivo de esta carpeta" |
| `exit` | Cierra la conexión |
| `mv` | mueve archivos |

## Terminal
- Copiar: Ctrl+Shift+C (Ctrl+C solo corta el programa que está corriendo)
- Pegar: Ctrl+V o clic derecho