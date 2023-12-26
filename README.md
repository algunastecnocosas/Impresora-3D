# Impresora-3D
Para hacer diseños 3D se pueden usar diversos programas:
- https://www.tinkercad.com/
- https://www.blockscad3d.com/editor/
El diseño se baja en formato .STL

También se pueden descargar diseños hechos por otra gente de repositorios como https://www.thingiverse.com/

Una vez que se tiene el diseño deseado (.STL), hay que pasarlo por un programa que lo prepare para la impresora concreta que se utilice, ne nuestro caso la FlashForge Adventure 3. Los más habituales son:
- Ultimaker Cura: https://ultimaker.com/software/ultimaker-cura/ -> Es el que yo utilizo.
- Repetier: https://www.repetier.com/

En este programa de impresión hay que instalar un plugin con la configuración específica de la impresora 3D que se use, o bien configurarlo manualmente. Se adjunta el fichero con los parámetros que se deben poner.
Este programa lo que hace es calcular las capas en las que va a ir imprimiento el diseño y genera un fichero en formato .GCODE, que es el que se introduce con un Pen Drive en la impresora. Se pueden combinar varios diseños STL en un solo proyecto GCODE, siempre que quepan en la cama de la impresora.
