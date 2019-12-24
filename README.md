# Astropi comenzando con SenseHat
Documentación actualizada del siguiente tutorial: [Getting started with the Sense HAT]
(https://projects.raspberrypi.org/en/projects/getting-started-with-the-sense-hat)

<img src="https://github.com/profesoratecno/Astropi_comenzando_con_SenseHat/blob/master/Imagenes/2019-12-24_pantalla_inicio.jpg" width="750" align="center">

¿Dónde vamos a relizar nuestras prácticas? -> En [trinket] (https://trinket.io/) Podemos darnos de alta con nuestro correo de gmail y creamos nuestro primer archivo de Python pinchando sobre nuestra cuenta **>New Trinket>Python**.

Siempre comenzaremos nuestro proyectos con estas líneas:

        
        #librería
        from sense_hat import SenseHat
        
        #configuración inicial
        sense = SenseHat()
      
Nuestro primer código, como a cualquier informático cuando comienza una nueva sintaxis en un nuevo código de programación, y tan sólo para prácticar comenzaremos con nuestro : **"¡HOLA MUNDO!!"**

        #librería
        from sense_hat import SenseHat
        
        #configuración inicial
        sense = SenseHat()
        sense.show_message("¡HOLA MUNDO!!")
        
## Primer ejercicio
Vamos a ir entregando código a código. Primero entregamos nuestro nombre generado con colores aleatorios.
