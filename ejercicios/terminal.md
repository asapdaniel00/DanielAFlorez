# E1 · Reto de terminal

**Fecha:*11/09/2026* 
**Entorno:** Git Bash en Windows
**Grabación:** ejercicios/grabaciones/e1-terminal.mp4

## Objetivo
Crear un árbol de 3 niveles con 8 archivos, moverlos, renombrarlos y borrar
la mitad, sin explorador de archivos ni mouse.

## Árbol creado
taller:
documentos/  medios/

taller/documentos:
borradores/  informes/

taller/documentos/borradores:

taller/documentos/informes:

taller/medios:
imagenes/

taller/medios/imagenes:

## Comandos usados

| Comando | Qué hace |
|---|---|---|
| `mkdir -p` | Creación de carpeta| 
| `touch` |Creación de archivos |
| `mv` |Mover archivos | 
| `rm` | Eliminar archivos | 
| `find` / `wc -l` |recorre carpeta y todas sus subcarpetas | Cuenta # de lineas recibidas|

## Verificación
Antes de borrar: 8 archivos. Después: 4. Medido con `find taller -type f | wc -l`.

## Qué aprendí
- Mover y renombrar son la misma operación. Por qué.
- Diferencia entre `rm`, `rm -r` y `rm -rf`.

## Qué se me rompió