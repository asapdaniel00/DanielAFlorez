# E5 · Conflicto de merge

**Fecha:** 13 sep 2026
**Grabación:** ejercicios/grabaciones/e5-merge.mp4

## Qué provoqué
Hicé un cambio en la misma linea de un mismo archivo pero desde dos ramas diferentes por lo que resultó en un conflicto.
## Qué me mostró Git
$ git merge rama-b
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.

$ cat README.md
<<<<<<.< HEAD
Segundo README
===.====
Tercer README
>>>>>.>> rama-b
 los puntos son añadidos para el ejemplo 

## Cómo lo resolví
Al notar el conflicto en el archivo opte por el cambio que queria adecuar en el README asi que aceptes los cambios entrantes y realicé un commit.
## Historia final


$ git log --oneline --graph
*   91826bf (HEAD -> main) Resolver conflicto de merge en el tirulo del README
|\
| * 067feda (rama-b) Cambio titulo del README desde rama-b
* | 17e991f (rama-a) Cambiar titulo del README desde rama-a
|/
* 2160895 (origin/main) Se envia primer prueba README
* 0389cf4 Bitacora al dia
* 8d12e43 Se realiza ejercicio E3 http
* 0a7ba6a Se realiza ejercicio E2 dns
* f152997 Se sube Bitacora actualizada
* c5c80a3 Se agrega evidencia del ejercicio E1
* b2af8f8 Creación repositorio con README inicial del portafolio

## Qué aprendí
Visualización de un conflict merge.