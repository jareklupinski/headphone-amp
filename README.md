# headphone-amp
A simple headphone amp / signal buffer for balanced audio sources.

This design uses a TPS65131 to generate +-15V from a USB-C 5V input.

Originally, I wanted to use the INA1620, as its datasheet basically spells out that its intended use is as a headphone driver.

The opamp OPA1612 was chosen instead, as it seems to be basically the same chip, but without the integrated resistors, and was available from my assembly house at the time of production.

![schem](https://user-images.githubusercontent.com/2049284/144360011-46b35cbd-3e20-4135-a995-c424c02883cb.png)

![board](https://user-images.githubusercontent.com/2049284/144360014-c44d1cac-1954-4a67-a146-cbc0ac1fe9c6.png)
