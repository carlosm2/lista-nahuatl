# Lista de palabras en Nahuatl

Las listas de palabras pueden ser usadas para generar contraseñas aleatorias, el gestor de contraseñas [KeepassXC](https://keepassxc.org/) tiene una lista integrada que aplica para el idioma ingles: https://github.com/keepassxreboot/keepassxc/blob/develop/share/wordlists/eff_large.wordlist pero se pueden agregar listas de palabras en otros idiomas para que las contraseñas tengan un poco mas de sentido para personas de otras geografias no angloparlantes.

## Pasos para habilitar el idioma Nahuatl para KeepassXC en sistema GNU/Linux

### Descargar Lista

`wget https://raw.githubusercontent.com/carlosm2/lista-nahuatl/main/nahuatl-lista.txt`

### Copiar lista a wordlist de Keepassxc

`sudo cp nahuatl-lista.txt /usr/share/keepassxc/wordlists/`

### Seleccionar la lista

Si keepassXC estaba abierto cierralo y abrelo de nuevo

Selecciona de **Lista de Palabras**:

![](<https://cacu.tech/img/kipas1.png>)

en donde decia **eff_large.wordlist** se verá en este caso **nahuatl-lista.txt**

y seleccionas esa lista:

![](<https://cacu.tech/img/kipas2.png>)

será la unica vez que realices este cambio, la proxima vez que quieras crear una contraseña con frases estara seleccionado el idioma nahuatl.

Agradezco a Don Petrohs https://github.com/petrohs ayudarme a formatear la lista.

c.

### Pendientes

- [ ] Revisar incosistencia de la lista, posibles espacios en blanco
- [ ] Agregar tutoriales para Windows y OSX
- [ ] Comer frutas y verduras
- [ ] Tomar awa
