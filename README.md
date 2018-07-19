# ADF4351
Fork of Universal driver for ADF4351 to be controlled using an arduino!
### The ADF4351 board is rated for 3.3V! Make sure to add current divider between arduino digital pins and ADF4351

|Arduino|ADF4351|
|---|---|
|3.3V|3V3|
|GND|GND|
|D11|DAT|
|D12|LE|
|D13|CLK|

### For some of the china boards, a CE: ChipEnable pin is available. In order to use the chip, a 10k resistor needs to be added between CE and 3.3V!
