---
layout: post
author: Nate
tags: hardware
---

I'm on a bit of a bargain-basement kick, and wanted to see how cheap I could get a pocket node. After a lot of shopping around, here's what I've managed to cobble together. It's definitely a lot more Janky DIY than other solutions but the price tag isn't bad, and the battery life looks to be about 36 hours.

[![Picture of front of JankPocket node](../../../images/2025-10-26-jankpocket-front.jpg)](../../../images/2025-10-26-jankpocket-front.jpg)

[![Picture of side of JankPocket node](../../../images/2025-10-26-jankpocket-side.jpg)](../../../images/2025-10-26-jankpocket-side.jpg)

[![Picture of innards of JankPocket node](../../../images/2025-10-26-jankpocket-internals.jpg)](../../../images/2025-10-26-jankpocket-internals.jpg)

Parts (easily available on AliExpress and/or Amazon):
- ProMicro NRF52840 board: $5
- Ebyte E22-900M30S radio: $10
- 44x24x9mm Li-poly battery: $5
- 17cm 915MHz antenna: $10

It also uses some basic parts like hookup wire and a slide switch, and a printed case with a lasered-on logo.

I followed the [ProMicro DIY wiring scheme](https://github.com/meshtastic/firmware/blob/develop/variants/nrf52840/diy/nrf52_promicro_diy_tcxo/Schematic_Pro-Micro_Pinouts%202024-12-14.pdf), with a 3D printed carrier board designed to optimize the wiring process. 

If you're interested in trying to put one together, I've published the 3D print files on Thangs: [JankPocket Meshtastic node carrier board and case](https://thangs.com/designer/natetrue/3d-model/JankPocket%20Meshtastic%20radio%20node%20carrier%20board%20and%20case-1456375?source=All+Files)

Happy meshing! 🍁
