# Circuito Tactil NTC UADY-CICY
Circuito para la detección de contacto en sensores nanoestructurados.

## Por hacer y revisar (de prioritario a no urgente)
- **Checar valores de _resistencias y capacitores_.**
<sub>(los del regulador deben ser 10uF en ambas salidas para evitar ruido, poner en paralelo uno de 100nf ceramico para reducir la Rint de ambos)</sub>
- Hacer tabla con características de mcu/mux/potdig/opamp para presentar a Francis y compararlo con equipo Keysight 32980A y 32923A
- ~~Añadir capacitores al lado de la entrada de 3.3v MCU ✓~~
- ~~Controlar la salida 2 del regulador para encender/apagar circuitos ✓~~ (checar consumo? aguanta el ic?)
- ~~Conectar MCU a pines ✓~~
- ~~Revisar mosfet Q1, se están usando como canal P y no N ✓~~
- ~~Validar secuencia en MUXes ✓~~(Checar que cable plano tenga los mismos pines en ambos extremos 1:1)
- ~~Editar footprint de nina para quitar todos los gpio no usados ✓~~
- ~~Validar conexión spi y componentes para micro SD ✓~~
- ~~Etiquetas en pines. ✓~~
- ~~tapar vias no importantes (reduciendo su tamaño <13 mils) ✓~~

## Extras a añadir
- ~~Añadir headers para sacar I2C y SPI ✓~~
- ~~Añadir testpoints en muxes ✓~~
- ~~Jumper para saltar de 3.3v a 5v ✓~~

### Si nos da tiempo 
- Añadir ic para carga y descarga de baterías (queda un espacio grande donde podemos añadir el cargador de pilas)
**(Si se añade, se debe aislar los 5v del usb y los 4.2 de la pila)**.
- Integrar ADC ADS1220 (FUTURO (puerto i2c disponible))
- ~~Añadir conector plano de +42 pines (básicamente se añadió en el punto de los testpoints en muxes)~~