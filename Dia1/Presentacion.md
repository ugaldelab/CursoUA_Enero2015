# Introducción al Shell
## 19/1/15

---

![fit](figuras/geekplot.jpg)


---

# Ejemplo
(De http://software-carpentry.org/v5/novice/shell/00-intro.html)

Nelle Nemo, a marine biologist, has just returned from a six-month survey of the North Pacific Gyre, where she has been sampling gelatinous marine life in the Great Pacific Garbage Patch. She has 300 samples in all, and now needs to:

___

- Run each sample through an assay machine that will measure the relative abundance of 300 different proteins. The machine's output for a single sample is a file with one line for each protein.
- Calculate statistics for each of the proteins separately using a program her supervisor wrote called goostat.

---
- Compare the statistics for each protein with corresponding statistics for each other protein using a program one of the other graduate students wrote called goodiff.
- Write up. Her supervisor would really like her to do this by the end of the month so that her paper can appear in an upcoming special issue of Aquatic Goo Letters.

---
Suponiendo que "solo" tomó dos semanas obtener los datos, Nelle ya esta lista para trabajar!

##PREGUNTA: ¿Que harían ustedes?

___
Si hay que correr `goostat` y `goodiff` a mano, esto implica:
- Escribir los nombres de los archivos y apretar ok 45.150 veces (300 `goostat`, mas 300x299/2 de `gooddif`).
- Si solo toma 30 segundos hacer esto, es más de dos semanas! Y es muy probable que cometa algún error al escribir los nombres de los archivos.

___
##Estructura de directorios
![inline](figuras/filesystem.pdf)

---
##Estructura de directorios
![inline](figuras/home-directories.pdf)

---
###Volviendo a Nelle, ella organiza sus directorios de esta forma:
![inline](figuras/homedir.pdf)

___


