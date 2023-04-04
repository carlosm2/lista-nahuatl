# Lista de palabras en Nahuatl

![](<https://cacu.tech/img/Historia_general_de_las_cosas_de_nueva_Espa%C3%B1a_page_406_md.jpg>)

Las listas de palabras pueden ser usadas para generar contraseñas aleatorias, el gestor de contraseñas [KeepassXC](https://keepassxc.org/) tiene una lista integrada que aplica para el idioma ingles: https://github.com/keepassxreboot/keepassxc/blob/develop/share/wordlists/eff_large.wordlist pero se pueden agregar listas de palabras en otros idiomas para que las contraseñas tengan un poco mas de sentido para personas de otras geografias no angloparlantes.


## Pasos para habilitar el idioma Nahuatl en KeepassXC en sistema GNU/Linux

### Descargar Lista

`wget https://raw.githubusercontent.com/carlosm2/lista-nahuatl/main/nahuatl-lista.txt`

### Copiar lista a wordlist de Keepassxc (para versiones menores 2.7.x)

`sudo cp nahuatl-lista.txt /usr/share/keepassxc/wordlists/`

### Seleccionar la lista:

Si keepassXC estaba abierto cierralo y abrelo de nuevo

Selecciona de **Lista de Palabras**:

![](<https://cacu.tech/img/kipas1.png>)

en donde decia **eff_large.wordlist** al seleccionar el menú desplegable se verá en este caso **nahuatl-lista.txt**

y seleccionas esa lista:

![](<https://cacu.tech/img/kipas2.png>)

será la unica vez que realices este cambio, la próxima vez que quieras crear una contraseña con frases estará seleccionado el idioma nahuatl.


---

### Descargar fuera de github

* Opcion 1:

`wget https://cacu.tech/nahuatl/nahuatl-lista.txt`

* Opcion 2: 

Usando `torsocks` para conectarse a un sitio cebolla

`torsocks wget http://www.orhecoctbqfeuftzycwrgg6rbf2tmsexnh7okufstc67r6fpnagjorid.onion/nahuatl/nahuatl-lista.txt`


--


## Pasos para habilitar el idioma Nahuatl en KeepassXC en sistema Windows


### Descargar la lista 

Accede a esta dirección:

https://raw.githubusercontent.com/carlosm2/lista-nahuatl/main/nahuatl-lista.txt

y desde tu navegador web elige "Guardar como" 

en este ejemplo lo pondremos en Escritorio:

![](<https://cacu.tech/img/guardalistaesc.png>)

Con el Explorador de Archivos localiza el archivo que acabas de descargar nahuatl-lista.txt para copiarlo a la dirección:

`C:/Archivos de Programa/KeePassXC/share/wordlist` y pegalo en esa dirección, te pedirá una usuaria con permisos de administración, si tu usuaria es unica o eres la administradora te dejara continuar con solo dar click en "Continuar"


![](<https://cacu.tech/img/permisopegar.png>)

Una vez realizado esto, cierra y vuelve a abrir KeePassXC

En donde dice "Lista de Palabras" cambia de `(SISTEMA)eff_large.wordlist` a `(SISTEMA)nahuatl-lista.txt`

y listo:


![](<https://cacu.tech/img/kipaswin.gif>)


---

### Pasos para agregar idioma Nahuatl en macOS


Puedes hacer estos pasos en cualquier versión actualizada de KeepassXC:

## Descargar la lista:

Accede a esta dirección:

https://raw.githubusercontent.com/carlosm2/lista-nahuatl/main/nahuatl-lista.txt

y desde tu navegador web elige "Guardar como" 

luego en el boton de **Generador de Contraseñas** selecciona **Frase de Contraseña** y **Lista de Palabras** 

ahi das click en el signo de **+** (Añadir lista de palabras personalizada)

![](<https://cacu.tech/img/kipasmacos2.png>)


---

@ Imagenes tomadas de KeepassXC y de wikipedia: https://en.wikipedia.org/wiki/Nahuatl#/media/File:Historia_general_de_las_cosas_de_nueva_Espa%C3%B1a_page_406_2.png


Agradezco a Don Petrohs https://github.com/petrohs ayudarme a formatear la lista.

---

### Pendientes

- [x] Revisar incosistencia de la lista
- [x] Agregar tutoriales para Windows y OSX
- [ ] Comer frutas y verduras
- [x] Tomar awa
