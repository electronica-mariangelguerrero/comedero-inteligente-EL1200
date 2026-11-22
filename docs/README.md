# Documentación técnica 

El sistema utiliza un microcontrolador ESP32 para leer un sensor PIR (GPIO 2), controlar un servomotor (GPIO 13) que abre la compuerta durante 1,5 s y luego la cierra, e iluminar un LED con resistencia de 220 Ω (GPIO 5) mientras dispensa[cite: 15, 19]. Una variable booleana (`dispensado`) evita servir comida nuevamente mientras el gato permanece frente al plato[cite: 19].
