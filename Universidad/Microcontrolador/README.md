# **Diseño y simulación de un malacate ascensor con Arduino uno y pantalla OLED de 128X64.**

**Se trata de diseñar y simular un malacate ascensor, con Arduino UNO y pantalla OLED SSD1306:**

*
• Para censar el paso de la cabina por cada piso, se utilizará un sensor de efecto Hall.
• Se supone que en cada piso hay un imán y que el sensor Hall, se mueve con la cabina.
• La construcción donde estará el malacate, será solo de 10 pisos, (se considera que el malacate, está en el piso cero).
• Para elegir el piso donde se desea subir, se cuenta con nueve (9), pulsadores (ver figura de la página anterior).
• Una vez elegido el piso donde se quiere que llegue el ascensor, se deberá arrancar el motor (prender led motor), y esperar que el sensor Hall, cense el imán de cada piso.
Cuando se llegue al piso indicado, se deberá parar la cabina (apagar el led que representa el motor) y abrir la puerta: encendiendo el led que representa la puerta, esto durante un segundo.
• Cuando el ascensor llegue al piso cero, se debe apagar el motor que mueve la cabina y abrir la puerta.
• El sistema solo permite elegir un piso por cada viaje.
• Se supone que solo hay un imán por cada piso, por lo tanto, este se debe usar para censar tanto las subida como la bajada.*

## Sensores y Actuadores:
