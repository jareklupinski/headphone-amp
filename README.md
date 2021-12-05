# headphone-amp
A simple headphone amp / signal buffer for balanced audio sources.

This design uses a TPS65131 to generate +-15V from a USB-C 5V input.

Originally, I wanted to use the INA1620, as its datasheet basically spells out that its intended use is as a headphone driver.

The opamp OPA1612 was chosen instead, as it seems to be basically the same chip, but without the integrated resistors, and was available from my assembly house at the time of production.

![schem](https://user-images.githubusercontent.com/2049284/144734981-38804f18-891c-490a-8813-8d35508e5607.png)

![board](https://user-images.githubusercontent.com/2049284/144734980-270bd3b6-a6fa-45b6-b08d-af1fa995f0a9.png)
