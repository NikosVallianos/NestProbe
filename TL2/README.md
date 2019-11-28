# NestProbe TL2

The NestProbe TL2 is a low cost, high accuracy, long-life temperature logger
developed at Wildlife Sense for sea turtle egg incubation research.

Some aspects and decisions during development of the TL2 and its predecessor,
the TL1, have been documented at
[hackaday.io/project/27560-low-costpowersize-temperature-logger](https://hackaday.io/project/27560-low-costpowersize-temperature-logger).

The main components in the TL2 are:

| Component          | Model       |
|:-------------------|:------------|
| Microcontroller    | [ATtiny816](https://www.microchip.com/wwwproducts/en/ATTINY816) |
| Temperature sensor | [Si7051](https://www.silabs.com/products/sensors/temperature/si705x/device.si7051) |
| Flash memory      | [AT25DN512C](https://www.adestotech.com/products/dual-quad-spi-memory/) |
| RTC crystal | [ECS-.327-7-34B-C-TR](https://ecsxtal.com/ecx-31b) (32.768kHz) |
| Battery type       | CR2032/CR1632      |

Plus one SMD 0402 LED and a small number of pull-up resistors and decoupling capacitors.

The TL2 firmware and Eagle files are released under the GNU General Public
License version 3 (see [LICENSE](https://github.com/NikosVallianos/NestProbe/LICENSE) for details). This means that you can use these files and designs,
manufacture the TL2 or derivatives and even sell them but you always have to
make the original source code or derivatives available under the same license.

