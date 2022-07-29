# Lista de palabras en Nahuatl

![](<https://cacu.tech/img/Historia_general_de_las_cosas_de_nueva_Espa%C3%B1a_page_406_md.jpg>)

Las listas de palabras pueden ser usadas para generar contraseñas aleatorias, el gestor de contraseñas [KeepassXC](https://keepassxc.org/) tiene una lista integrada que aplica para el idioma ingles: https://github.com/keepassxreboot/keepassxc/blob/develop/share/wordlists/eff_large.wordlist pero se pueden agregar listas de palabras en otros idiomas para que las contraseñas tengan un poco mas de sentido para personas de otras geografias no angloparlantes.

## Pasos para habilitar el idioma Nahuatl para KeepassXC en sistema GNU/Linux

### Descargar Lista

`wget https://raw.githubusercontent.com/carlosm2/lista-nahuatl/main/nahuatl-lista.txt`

### Copiar lista a wordlist de Keepassxc

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

## Descargar fuera de github

Opcion 1:

`wget https://cacu.tech/nahuatl/nahuatl-lista.txt`

Opcion 2:





---

@ Imagenes tomadas de KeepassXC y de wikipedia: https://en.wikipedia.org/wiki/Nahuatl#/media/File:Historia_general_de_las_cosas_de_nueva_Espa%C3%B1a_page_406_2.png


Agradezco a Don Petrohs https://github.com/petrohs ayudarme a formatear la lista.

---

### Pendientes

- [x] Revisar incosistencia de la lista
- [ ] Agregar tutoriales para Windows y OSX
- [ ] Comer frutas y verduras
- [x] Tomar awa
