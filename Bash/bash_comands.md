# Main source:

https://www.sysadmit.com/2015/07/linux-reemplazar-texto-en-archivos-con-sed.html

# Para sustituir contenido de los archivos de una carpeta por otra, desde el terminal:

find /test/ -name "*.txt" -print | xargs sed -i "s/SYSADMIT/--SYSADMIT--/g"


# Para sustituir el contenido de un archivo en concreto, desde el terminal:

sed -i 's/texto-a-buscar/texto-a-reemplazar/g' "Fichero o directorio"



# Para buscar donde se encuentra una determinada palabra en un directorio:

grep -r "palabra"



# Para consultar el directorio en el que nos encontramos:

pwd



# Para renombrar archivos:
# Renombrar extensiones:

rename ‘s/.txt/.php/’ *.txt

# Renombrar nombre archivos:

rename 'y/ /_/' *

# Pasar de mayus a minus e viceversa:

rename 'y/A-Z/a-z/' *
rename 'y/a-z/A-Z/' *



