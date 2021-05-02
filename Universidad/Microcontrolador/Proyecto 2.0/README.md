# **Conversión A/D, PWM, y Protocolo de comunicaciones One Wire con Sensor de temperatura DS18B20**

**Se trata de diseñar y simular un malacate ascensor, con Arduino UNO y pantalla OLED SSD1306:**

* Para censar el paso de la cabina por cada piso, se utilizará un sensor de efecto Hall 3144.
* Se supone que en cada piso hay un imán y que el sensor Hall, se mueve con la cabina.
* La construcción donde estará el malacate, será solo de 10 pisos, (se considera que el malacate, está en el piso cero).
* Para elegir el piso donde se desea subir, se cuenta con nueve (9), pulsadores (ver figura de la página anterior).
* Una vez elegido el piso donde se quiere que llegue el ascensor, se deberá arrancar el motor (prender led motor), y esperar que el sensor Hall, cense el imán de cada piso.
Cuando se llegue al piso indicado, se deberá parar la cabina (apagar el led que representa el motor) y abrir la puerta: encendiendo el led que representa la puerta, esto durante un segundo.
* Cuando el ascensor llegue al piso cero, se debe apagar el motor que mueve la cabina y abrir la puerta.
* El sistema solo permite elegir un piso por cada viaje.
* Se supone que solo hay un imán por cada piso, por lo tanto, este se debe usar para censar tanto las subida como la bajada.*

## Sensores y Actuadores:

### Oled 1306
![](https://ph0en1x.net/uploads/Image/news/raspberry-pi/oled-display-ssd1306-128x64px-i2c.jpg)

![](https://i.stack.imgur.com/scay0.jpg)


### Efecto Hall 3144

![](https://www.compelelectronica.com/wp-content/uploads/Sensores-magn%C3%A9ticos-de-efecto-hall-3144-SENHALL-copia.jpg)

![](https://www.sunrom.com/media/content/157/a3144-pinout.jpg)
