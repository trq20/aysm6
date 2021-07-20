## Especificaciones

Hacer un programa en `micropython` que haga una lectura en un pin analógico cada segundo y muestre el valor de tensión correspondiente por la terminal. El simulador donde van a hacerlo es [Wokwi](https://wokwi.com/arduino/new?template=micropython-pi-pico).
Luego, hacer un `README.md` con lo siguiente:

```markdown
# Micropython - ADC

Alumno: Nombre y apellido
Curso: Curso
Materia: Computadoras y Sistemas de Control

[Screenshot del circuito]
```

## Consideraciones

- Documentación de [micropython](http://docs.micropython.org/en/latest/). Van a tener que usar la clase `ADC` del modulo `machine`. Particularmente, hay un apartado para la `Raspberry Pi Pico` en [Quick reference for the RP2](http://docs.micropython.org/en/latest/rp2/quickref.html#pins-and-gpio).
- Documentación del [simulador](https://docs.wokwi.com/micropython) que van a usar.
- Para el delay, pueden usar el módulo [time](https://docs.python.org/3/library/time.html).
- Pinout de la `Raspberry Pi Pico`:

![](https://cdn-shop.adafruit.com/1200x900/4883-06.png)

## Como entregar

- Archivos para subir: `main.py`, `diagram.json`, `README.md`, la imagen del circuito.
- Nombre de la rama: `aysm6/2021/upython/adc`.
