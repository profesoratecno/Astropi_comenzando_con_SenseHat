# Astropi comenzando con SenseHat
Documentación actualizada del siguiente tutorial: [Getting started with the Sense HAT]
(https://projects.raspberrypi.org/en/projects/getting-started-with-the-sense-hat)

<img src="https://github.com/profesoratecno/Astropi_comenzando_con_SenseHat/blob/master/Imagenes/2019-12-24_pantalla_inicio.jpg" width="750" align="center">

¿Dónde vamos a relizar nuestras prácticas? -> En [trinket] (https://trinket.io/) 

<img src="https://github.com/profesoratecno/Astropi_comenzando_con_SenseHat/blob/master/Imagenes/2019-12-24_trinket.jpg" width="750" align="center">

Podemos darnos de alta con nuestro correo de gmail y creamos nuestro primer archivo de Python pinchando sobre nuestra cuenta **>New Trinket>Python**.

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
        
        #variables
        
        #órdenes
        sense.show_message("¡HOLA MUNDO!!")
        
También es divertido ir introduciendo colores a nuestras creaciones, podemos **[Representar colores con tres números: código RGB](https://github.com/raspberrypilearning/generic-theory-colours/blob/master/es-ES/step_1.md)**.

Para ello vamos a crear dos variables -> azul y amarillo

Además vamos a introducir nuestro código en un *"por siempre"*, con el comando **while**, ahora nuestro código es muy corto, pero cuando comience a ser más largo no querremos tener siembre apareciendo un mensaje, solamente cuando se cumpla alguna condición. 
Fíjate que nuestro **show_message** ahora lo tenemos que escribir *"sangrado"* para introducirlo en el bucle **while**.

Aquí el ejemplo:
        #librería
        from sense_hat import SenseHat
        
        #configuración inicial
        sense = SenseHat()
        
        #variables
        azul = (0, 0, 255)
        amarillo = (255, 255, 0)
        
        #órdenes
        while True:
          sense.show_message("¡ESTO ES MUY CHULO!!", text_colour=amarillo, back_colour=azul)
        

## Primer ejercicio
Vamos a ir entregando código a código. Primero entregamos nuestro nombre generado con colores aleatorios.
