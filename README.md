# GLOWPAD

The glowiest macropad

![alt text](pictures/hackpad.PNG)

This macropad was designed as a sort of sidestep from a Hackpad. I didn't want to make another PCB as I just don't want to deal with the lead time, plus I think hand-wiring a keyboard would be fun, and a macropad is really just a small keyboard.

This will also act as a dongle for my split keyboard, which should increase the battery life of the left half almost 3 months. This is why it uses a nrf52840 based chip rather than the xiao rp2040, it needs the wireless features.

I don't know if I can actually call this a hackpad because its using acrylic side panels and handwire, but it pretty much is a hackpad.

# BOM

| PART                          | UNIT COST | QUANTITY | ROW COST | NEED BOUGHT | SUPPLIER                                    |
| ----------------------------- | --------- | -------- | -------- | ----------- | ------------------------------------------- |
| Choc Keyswitch                | $5.50     | 1        | $5.50    | FALSE       | [typeractive.xyz](https://typeractive.xyz/) |
| MBK Choc Keycap               | $3.50     | 1        | $3.50    | FALSE       | [typeractive.xyz](https://typeractive.xyz/) |
| THT Diodes                    | $0.98     | 10       | $9.80    | FALSE       | aliexpress                                  |
| Acrylic, 75mmx70mm            | $0.00     | 1        | $0.00    | FALSE       | [typeractive.xyz](https://typeractive.xyz/) |
| 1m 144led/m WS2812B LED Strip | $13.63    | 1        | $13.63   | TRUE        | [typeractive.xyz](https://typeractive.xyz/) |
| Promicro nrf52840             | $3.00     | 1        | $3.00    | FALSE       | aliexpress                                  |

# wiring

![alt text](https://github.com/user-attachments/assets/3715c39d-45d1-4c33-aac3-046417511000)

The wiring is just a standard matrix, it'll end up looking something like this.
