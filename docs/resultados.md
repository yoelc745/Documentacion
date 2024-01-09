# Informe Técnico y resultados
--------------------------

## Aspectos relevantes

### Mejoras identificadas

### Mejoras identificadas por equipo de HCI

#### Posibles mejoras aplicación APP Línea Llenado-Vaciado 

- Cuando se desea realizar un cambio de lotes es necesario vaciar la línea completa para
poder realizar el cambio de lote. Se podría buscar una alternativa que permita realizar
el cambio de lote sin necesidad de realizar el vaciado de la línea.
- Al realizar el vaciado de un lote el operador indica en la aplicación de la línea el lote que
será vaciado, sin embargo, en la línea no se realiza una verificación de que realmente el
pallet montado en la línea coincida con el lote que se desea vaciar. Se podría crear un
mecanismo que impida que un pallet con un número de lote que no coincida con el lote
que se indicó que sería vaciado se procese.
- En los logs de la aplicación debería incorporarse los resultados del registro que será
almacenado en la base de datos de forma tal que si por algún error fuera imposible
guardarlos en la base de datos y la línea continúa su labor esos valores puedan ser
consultados e insertados posteriormente en la base de datos.
- Actualmente en aras de agilizar el proceso de llenado o vaciado de los barriles en algunas
ocasiones algunos de los pallets son procesados por fuera de la línea. Estos pallets
procesados no son registrados en la base de datos.
- Es necesario realizar una revisión total del código y del flujo en busca de la posibilidad
de optimizar el mismo y de garantizar que puedan ser incorporadas mejoras y nuevas
funcionalidades.
- Cuando un pallet sale por cualquiera de las líneas de llenado o vaciado (zonas 2 o 4) sin
antes haberse registrado en las zonas de entrada de dichas líneas (zonas 1 o 3
respectivamente) debería emitirse alguna alerta que indique que esa información falta
por registrarse en la base de datos. Una posible solución a este problema podría ser una
funcionalidad en la aplicación del Tablet que permita de forma manual incorporar ese
registro a la base de datos.


#### Posibles mejoras aplicación HavanaTablet 

- En la opción “Regrabar Tag”, al leer la información del Tag, los campos: lote, fecha y
peso deben ser editables para poder introducir o modificar los valores de búsqueda del
Tag.
- Es necesario que el sistema muestre un mensaje indicando cuando no es posible
conectarse a la base de datos para procesar los valores leídos. Ej. en la opción “Historial
de Barriles” si se pierde la conexión con la base de datos al realizar la lectura del tag por
RFID no se muestra ningún registro o mensaje pudiendo confundir que el tag no tiene
registros.
- En la ventana “Historial de barriles”, si el lector de transponders no ha sido conectado y
se selecciona la opción “Escanear transponder” debería mostrar un mensaje similar a la
opción “Leer transponders” que informe que el lector no está conectado. De forma
similar sucede en la opción “Sustituir Tag/Escanear RFID”.
- La interfaz de usuario no es amigable, ya que no es posible diferenciar en ocasiones los
botones de los campos de texto. Se debería diferenciar los componentes de la pantalla
para que los mismos sean perfectamente identificables por el usuario.

### Sugerencias de mejoras para el proyecto Havana Club por Avangenio

- Centralización y reorganización de las dependencias del proyecto.

En su estado actual, el código del proyecto tiene un alto número de dependencias que se hallan dispersas en múltiples lugares, muchos de los cuales son referencias que dependen de una configuración específica de la estructura de directorios del proyecto. Centralizar estas dependencias en un repositorio específico cuya localización respecto al proyecto principal no varíe, constituye una potencial mejora.

- Eliminación de referencias y código no utilizado.

Actualmente, el código del proyecto está salpicado de características a medio hacer, que estaban siendo implementadas pero se tomó la decisión de no darles continuidad. Este código a medias ofusca y hace más engorrosa la comprensión y el mantenimiento del código del proyecto. En el futuro, una vez que el proyecto se halle en un estado satisfactorio, puede ser posible re-evaluar la implementación de esas características.

- Actualización tecnológica.

El proyecto está implementado usando la versión 4.8 del .NET Framework. El estado del arte de la tecnología actual está muy por delante de esa versión, y una posible mejora del proyecto sería actualizar este proyecto a los estándares actuales. Nota: esto podría implicar una refactorización de gran envergadura de todo el proyecto.

- Resolución de no conformidades existentes.

El proyecto tiene definidas actualmente un grupo de no conformidades que atentan contra el buen funcionamiento del proceso de adquisición y almacenamiento de datos. La resolución puntual de éstas no conformidades constituye una mejora potencial. Dichas resoluciones pueden variar en complejidad, pudiendo requerir grandes modificaciones a la arquitectura del proyecto. La evaluación de dichas complejidades se escapa al ámbito de este documento, y deben ser valoradas puntalmente.

### Problemas identificados

#### Deficiencias aplicación HavanaTablet

Luego de la revisión y pruebas de la aplicación HavanaTablet se detectaron un conjunto de no conformidades que no fueron cubiertas por sus desarrolladores (EKINSA) y que en gran medida atentan contra el correcto funcionamiento de la misma. A continuación, se relacionan estas no conformidades:

- Cuando la aplicación una vez abierta pierde la conexión con la base de datos se vuelve inoperable.
- En la opción “Regrabar Tag”, al leer la información del Tag, los campos: lote, fecha y peso deben ser editables para poder introducir o modificar los valores de búsqueda del Tag.
- Cuando el lector de transponders se desconecta de la aplicación, esta deja de funcionar hasta que el dispositivo vuelve a estar en línea y enlazado.
- Cuando el sistema se encuentra procesando una lectura (por ejemplo, realizando una búsqueda en la base de datos) debe mostrar un mensaje indicativo (un loader) que indique que el sistema está procesando una solicitud y el usuario debe permanecer a la espera.
- Si el lector RFID se desconecta de forma reiterada de la aplicación o esta es reiniciada pueden ocurrir errores de sincronización entre los dispositivos, siendo necesario reiniciar el sistema del Tablet.

#### Deficiencias aplicación APP Línea Llenado-Vaciado

Luego de la revisión y pruebas de la aplicación App Línea de Llenado Vaciado se detectaron un conjunto de no conformidades que no fueron cubiertas por sus desarrolladores (EKINSA) y que en gran medida atentan contra el correcto funcionamiento del flujo y el almacenamiento de los datos. A continuación, se relacionan estas no conformidades:

- Cuando la aplicación luego de iniciada y en funcionamiento pierde la conexión con la base de datos, la línea continúa su funcionamiento y la aplicación no muestra un mensaje indicando lo sucedido. Actualmente solamente se guardan en los ficheros de logs un conjunto de excepciones correspondientes a los intentos de conexión con la base de datos. Los registros correspondientes a los pallets se pierden (no son registrados en la base de datos).
- Existe la posibilidad de duplicidad de registros. Aunque se ha definido un margen de 50 kg de diferencia entre los registros de un pallet para que este no se registre de forma duplicada se puede dar el caso de que un pallet se atraviese en la línea y que el sistema realice varias pesadas que superan los 50kg de diferencia entre ellas y por ende ese pallet se registra de forma reiterada en la base de datos.
- Cuando la electricidad en la planta de llenado / vaciado falla, ocurre una desincronización entre la línea (pesas y PLC) y la aplicación de la línea (App desarrollada por EKINSA). Luego de restablecida la electricidad se requiere de la acción manual de los operarios para reiniciar las pesas, el PLC y la aplicación de la línea. En ocasiones este procedimiento puede tardar algunos minutos, pues es necesario realizarlo varias veces si no se logra una sincronización correcta. Es necesario analizar este proceso de sincronización de los artefactos presentes en aras de conseguir una optimización del proceso y la posibilidad de simplificarlo.