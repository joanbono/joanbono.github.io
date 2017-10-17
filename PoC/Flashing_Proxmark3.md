# Reflashing Proxmark3 RV3.0 using a Bus Pirate

Experimenting with my **Proxmark3 RV3.0**, I broke the bootloader.

Taking advantage of that I have two [**Bus Pirate**](http://dangerousprototypes.com/docs/Bus_Pirate), I used it to reflash the device.

First of all, the connection.

The **Proxmark3** has `JTAG` pinout, so, let use them!

![](images/flas_pm3_001.png)

The connections with the **Bus Pirate**:

| Proxmark3 | Bus Pirate | Cable Color |
|:---------:|:----------:|:-----------:|
| `TMS`     |   `CS`     |  Purple     |
| `TDI`     |   `MISO`   |  Blue       |
| `TDO`     |   `MOSI`   |  Green      |
| `TCK`     |   `CLK`    |  Yellow     |
| `GND`     |   `GND`    |  Black      |
| `3.3`     |   `+3.3`   |  White      |

As seen in the picture:

![](images/flas_pm3_002.png)

