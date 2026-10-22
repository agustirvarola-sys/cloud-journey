# Apuntes de Linux

## Bandit (OverTheWire)
Juego para practicar Linux: en cada nivel hay que encontrar con comandos la contraseña del nivel siguiente.
- Conexión: `ssh banditN@bandit.labs.overthewire.org -p 2220`
- La contraseña que encontrás en el nivel N sirve para entrar al nivel N+1.

## Comandos
| Comando | Qué hace |
| --- | --- |
| `ls` | Lista los archivos de la carpeta |
| `ls -a` | Lista todos los archivos, incluidos los ocultos |
| `cd carpeta` | Entra a una carpeta |
| `cat archivo` | Muestra el contenido de un archivo |
| `file archivo` | Dice qué tipo de contenido tiene un archivo (texto o binario) |
| `mv origen destino` | Mueve un archivo |
| `exit` | Cierra la conexión |
| `reset` | Arregla la terminal si se llena de símbolos raros |

## Nombres de archivo difíciles
- Empieza con guion: `cat ./-` (`./` = "en esta carpeta")
- Tiene espacios: entre comillas, `cat "nombre con espacios"`
- `--` suelto significa "fin de las opciones": `cat -- "--nombre raro--"`

## Conceptos
- Archivo oculto: su nombre empieza con punto. `ls` no lo muestra, `ls -a` sí.
- `.` = carpeta actual · `..` = carpeta de arriba · `~` = mi carpeta personal
- `*` = todos los archivos (ejemplo: `file ./*`)
- Tab autocompleta nombres de archivos y comandos.

## Terminal
- Copiar: Ctrl+Shift+C (Ctrl+C solo corta el programa que está corriendo)
- Pegar: Ctrl+V o clic derecho