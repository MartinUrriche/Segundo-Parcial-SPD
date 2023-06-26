# Segundo-Parcial-SPD
## Autor: Urriche Martin

Consigna: 
El objetivo de este proyecto es diseñar un sistema de incendio utilizando Arduino que pueda
detectar cambios de temperatura y activar un servo motor en caso de detectar un incendio.
Además, se mostrará la temperatura actual y la estación del año en un display LCD.
segmentos.

## 1)Componentes necesarios:

    •Arduino UNO
    •Sensor de temperatura
    •Control remoto IR (Infrarrojo)
    •Display LCD (16x2 caracteres)
    •Servo motor
    •Cables y resistencias según sea necesario
    •Protoboard para realizar las conexiones
    •Dos leds.

## 2)Funcionalidad requerida:

    Conexiones:

        • Conecta el sensor de temperatura al pin analógico A0 de Arduino.
        • Conecta el control remoto IR al pin digital 11 de Arduino.
        • Conecta el display LCD utilizando los pines correspondientes de Arduino.
        • Conecta el servo motor a uno de los pines PWM de Arduino 

     Control remoto:

        • Configura el control remoto IR para recibir señales.
        • Define los comandos necesarios para activar y desactivar el sistema de incendio.
        • Utiliza un algoritmo para determinar la estación del año (por ejemplo, rangos de temperatura para cada estación).

    Detección de temperatura:
        • Configura el sensor de temperatura y realiza la lectura de la temperatura ambiente.
        • Muestra la temperatura actual en el display LCD.

    Sistema de alarma:
        • Define un umbral de temperatura a partir del cual se considera que hay un incendio (por ejemplo, temperatura superior a 60 grados Celsius).
        • Cuando se detecta un incendio (temperatura por encima del umbral), se activa el servo motor para simular una respuesta del sistema de incendio.

    Mensajes en el display LCD:
        • Muestra la temperatura actual y la estación del año en el display LCD.
        • Cuando se detecta un incendio, muestra un mensaje de alarma en el display LCD.

    Punto libre:
        • Se deberá agregar dos leds y darle una funcionalidad de su elección, acorde al proyecto previamente detallado.

## Arduino:

![Tinkercad](Arduino.png)
