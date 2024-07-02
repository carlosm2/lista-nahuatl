# Lista de palabras en Nahuatl para Gestor de Contraseñas

![](<https://cacu.tech/img/Historia_general_de_las_cosas_de_nueva_Espa%C3%B1a_page_406_md.jpg>)

Las *listas de palabras* (wordlist) pueden ser usadas para generar contraseñas aleatorias, el gestor de contraseñas [KeepassXC](https://keepassxc.org/) tiene una lista integrada que aplica para el idioma ingles: https://github.com/keepassxreboot/keepassxc/blob/develop/share/wordlists/eff_large.wordlist pero se pueden agregar *listas de palabras* en otros idiomas para que las contraseñas tengan un poco mas de sentido para personas de otras geografias no angloparlantes.

## Pasos para habilitar el idioma Nahuatl en KeepassXC en sistema Windows, Linux de manera gráfica:

### Descargar la lista 

Accede a esta dirección:

https://raw.githubusercontent.com/carlosm2/lista-nahuatl/main/nahuatl-lista.txt

y desde tu navegador web elige "**Guardar como**" 

en este ejemplo lo pondremos en la carpeta Escritorio:

![](<https://cacu.tech/img/guardalistaesc.png>)

### Agregar lista

En el boton de Generador de Contraseñas selecciona Frase de Contraseña y Lista de Palabras

ahi das click en el signo de + (Añadir lista de palabras personalizada)

En donde dice "**Lista de Palabras**" cambia de `(SISTEMA)eff_large.wordlist` a `(SISTEMA)nahuatl-lista.txt`

y listo:

![](<https://cacu.tech/img/kipaswin.gif>)

---

## Pasos para agregar idioma Nahuatl en macOS

Puedes hacer estos pasos en cualquier versión actualizada de KeepassXC:

### Descargar la lista:

Accede a esta dirección:

https://raw.githubusercontent.com/carlosm2/lista-nahuatl/main/nahuatl-lista.txt

y desde tu navegador web elige "Guardar como" 

### Agregar lista

En el boton de **Generador de Contraseñas** selecciona **Frase de Contraseña** y **Lista de Palabras** 

ahi das click en el signo de **+** (Añadir lista de palabras personalizada)

![](<https://cacu.tech/img/anadelistamac1.png>)

Seleccionas el archivo **nahuatl-lista.txt** que acabamos de descargar:

![](<https://cacu.tech/img/descargalistamac.png>)

### Usar lista-nahuatl

Finalmente seleccionamos la nueva lista para empezar a usar la lista de palabras en nahuatl :)

![](<https://cacu.tech/img/anadelistamac2.png>)


---

## Pasos para habilitar el idioma Nahuatl en KeepassXC en sistema GNU/Linux desde Terminal:

### Descargar Lista

`wget https://raw.githubusercontent.com/carlosm2/lista-nahuatl/main/nahuatl-lista.txt`

### Copiar lista a wordlist de Keepassxc (para versiones menores 2.7.x)

`sudo cp nahuatl-lista.txt /usr/share/keepassxc/wordlists/`

### Seleccionar la lista:

Si keepassXC estaba abierto cierralo y abrelo de nuevo

Selecciona el menú **Lista de Palabras**:

![](<https://cacu.tech/img/kipas1.png>)

en donde se lee: **eff_large.wordlist** al seleccionar el menú desplegable se verá en este caso también: **nahuatl-lista.txt**

y seleccionas esa nueva lista:

![](<https://cacu.tech/img/kipas2.png>)

será la unica vez que realices este cambio, la próxima vez que quieras crear una contraseña con frases estará seleccionado el idioma nahuatl.

---
## Descargar fuera de Github

* Opcion 1 . Desde repositorio externo:

`wget https://cacu.tech/nahuatl/nahuatl-lista.txt`

* Opcion 2 . Usando `torsocks` para conectarse a un sitio cebolla:

`torsocks wget http://www.orhecoctbqfeuftzycwrgg6rbf2tmsexnh7okufstc67r6fpnagjorid.onion/nahuatl/nahuatl-lista.txt`

------

@ Imagenes tomadas de KeepassXC y Wikipedia: https://en.wikipedia.org/wiki/Nahuatl#/media/File:Historia_general_de_las_cosas_de_nueva_Espa%C3%B1a_page_406_2.png


Agradezco a Don Petrohs https://github.com/petrohs ayudarme a formatear la lista.

---

## Pendientes

- [x] Revisar incosistencia de la lista
- [x] Agregar tutoriales para Windows y OSX
- [ ] Agregar lista a repositorios de word lists

## Licencia
Licencia de Producción de pares: https://github.com/carlosm2/lista-nahuatl/blob/main/LICENSE
