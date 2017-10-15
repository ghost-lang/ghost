![Ghost](./assets/banner-animated-gif)

# GHOST
#### ¿QUÉ ES GHOST?

Ghost Lang (o simplemente Ghost), es un lenguaje de programación para microcontroladores, cuyo nombre está inspirado en la franquicia de ciencia ficción "Ghost In The Shell". Inspirado en la capadidad de C para el trabajo con hardware, y la simplicidad de Python para el desarrollo ágil. Se trata de un lenguaje para microcontroladores, compilado, con tipo de datos estático, débilmente tipado, de nivel medio y multiparadigma. 

La implementación oficial de Ghost está hecha en JavaScript, pues se busca la posibilidad de ejecución en entornos de escritorio, web, servidores y dispositivos móviles.

Es importante destacar que Ghost debe ser considerado como un lenguaje de programación experimental, puesto que no es soportado por una fuerte base científica que asegure sus capacidades de optimización u otras características técnicamente medibles que normalmente se usan en el desarrollo de lenguajes de programación profesionales, ghost, en este sentido es un lenguaje creado de un modo más artesanal, y por encontrarse en una fase de desarrollo temprana, tampoco es posible asegurar que estará libre de fallos ni que todas las características documentadas han sido implementadas o si funcionan correctamente.

##### ¿Porqué crear Ghost?

Existen varios motivos por los cuales surge ghost, algunos de ellos son técnicos, otros personales.

###### Motivaciones personales

- Porque crear un lenguaje de programación es uno de los sueños de todo programador
- Porque es un experimento que me traerá mucho conocimiento y experiencia
- Porque es algo que me será útil para otros proyectos, y probablemente le será útil a mucha gente

###### Motivaciones técnicas

- Porque los lenguajes de programación para microcontroladores actualmente disponibles se basan en viejos estándares. 
Los lenguajes de programación en su teoría y práctica han evolucionado mucho en los últimos años y hay muchas cosas nuevas que se pueden aplicar a la programación de microcontroladores para mejorar el desarrollo.

- Porque el lenguaje C es muy bueno, pero es dificil de aprender y complicado de mantener.

- Porque los otros lenguajes disponibles para microcontroladores no son tan buenos para programación a bajo nivel.

- Porque los compiladores más populares para microcontroladores son privativos, hacen falta alternativas de código abierto.

- Porque los compiladores no oficiales más populares no cumplen con muchos de los estándares de C, provocando incompatibilidades entre plataformas e inconsistencias en sus API's.

- Porque hace falta un lenguaje de programación pensado específicamente para microcontroladores. 
Todos los lenguajes de programación disponibles para microcontroladores actualmente fueron pensados para microprocesadores y computadoras de uso general, pero no para el resto de hardware embebido común en un microcontrolador.

##### Proyectos relacionados

###### Ghost Lang

El compilador oficial de Ghost, programado en JavaScript, pensado para su ejecución en multiples entornos (web, desktop, server y mobile).


###### Logicoma

El interprete de línea de comandos de ghost (implementado con JavaScript como paquete en NPM).


###### MicroASM

El ensamblador usado por Ghost, programado en JavaScript, pensado para su ejecución en multiples entornos (web, desktop, server y mobile).


###### Intel X

El traductor de MicroASM que genera los ficheros Intel HEX para microcontroladres.


###### Shell

El framework oficial de Ghost para facilitar el desarrollo de grandes proyectos.


###### Shellino

Una implementación de Shell inspirada en arduino.


###### Puppet Master

La implementación de FreeRTOS hecha con Ghost.


###### SAC

El IDE de escritorio para desarrollo de aplicaciones con Ghost.


###### ARIS

El IDE Web para desarrollo de aplicaciones con Ghost en la nube.


##### Licencia

La especificación de Ghost es un documento bajo licencia Apache 2.0, que permite uso comercial, redistribución y modificación del documento original, siempre y cuando se haga la mención al autor original y esta o sus obras derivadas sean publicadas bajo la misma licencia.