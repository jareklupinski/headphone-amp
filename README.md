# headphone-amp
A simple headphone amp / signal buffer for balanced audio sources.

This design uses a TPS65131 to generate +-15V from a USB-C 5V input.

Originally, I wanted to use the INA1620, as its datasheet basically spells out that its intended use is as a headphone driver.

The opamp OPA1612 was chosen instead, as it seems to be basically the same chip, but without the integrated resistors, and was available from my assembly house at the time of production.

The PCB and face/backplates are sized for https://www.digikey.com/en/products/detail/bud-industries/EXN-23350-RDP/5886285, but any color should work ;)

![photo](https://user-images.githubusercontent.com/2049284/146654836-e6241553-b79b-4735-8bd5-b0add7f25c5d.jpeg)

![schem](https://user-images.githubusercontent.com/2049284/144735200-33f08565-4944-460a-a572-a2ad4e9e27c3.png)

![board](https://user-images.githubusercontent.com/2049284/144735203-5e2ff470-4a39-44e0-9362-899f8e8d235c.png)
