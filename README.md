# SlimeVR Hyperion Multi-IMU BMI BNO Case and PCB

## Purchasing Guide

### Required Components (PCB)
| Component | Variant | Link |
| -------------------- | --------------- | -------------------------------------------------------------------------------- |
| WeMos D1 Mini | Micro or Type-C | <https://www.aliexpress.us/item/2251832465432818.html> |
| TP4056 | 18650 Micro or Type-C | <https://www.aliexpress.us/item/2251832290307200.html> |
| BMI160 | Breakout Board | <https://www.aliexpress.us/item/2255799866368692.html> |
| BNO085 | Breakout Board | <https://shop.slimevr.dev/products/slimevr-imu-module-bno085> |
| 1/4W Metal Film Resistor | 180**K** | <https://www.aliexpress.us/item/3256803737288214.html> |
| Schottky Rectifier Diode | 1N5817 | <https://www.aliexpress.us/item/2255800018624086.html> |
| Header Pins | 2.54mm | <https://www.aliexpress.us/item/3256805804439042.html> |
| JST PH 2.0mm Connector | Right Angle/Side Entry & 2P | <https://shop.slimevr.dev/products/slimevr-imu-module-bno085> |
| Lithium Polymer Ion Battery | 503759 with Connector (PH) | <https://www.aliexpress.us/item/3256805125875396.html> |

> [!IMPORTANT]
> Purchase 30% more boards (WeMos D1 Mini, TP4056, and BMI160/BNO085 than what is needed. There is the possibility that components are dead on arrival or gets damaged during assembly/soldering.


> [!NOTE]
> One Order of Resistors, Diodes, Header Pins, and PH 2.0mm Connectors are enough for the entire project.

> [!NOTE]
> These are my recommended sellers/stores and recommended components just for the main tracker unit. You can always purchase components from elsewhere and that you may need Additional components are needed for extensions. Other stores/sellers may have a higher rate of dead on arrival. The linked stores for WeMos D1 Mini, TP4056, and BMI160/BNO085 are recommended by the SlineVR DIY Community.

> [!NOTE]
> Type-C Ports are more durable. As for charging, USB-C to USB-C Power Delivery doesn't work. Use USB-A to USB-C cables to charge trackers.

> [!TIP]
> In your AliExpress Cart, you can verify that you selected the correct variant of the component here.
<img src="Resources/Images/Purchasing/Cart.png">

### Optional Components (PCB)
| Component | Variant | Link |
| -------------------- | --------------- | -------------------------------------------------------------------------------- |
| JST XH 2.54mm Connector | Right ANgle/Side Entry & 4P(BMI160)/5P(BNO085) | <https://www.aliexpress.us/item/2251832822174658.html> |
| JST XH 2.54mm Connector with Female Cable | Right ANgle/Side Entry & 4P(BMI160)/5P(BNO085)| <https://www.aliexpress.us/item/2255799934230488.html> |
| Sheathed Wire Cable | 28AWG & 4Cores(BMI160)/5Cores(BNO085) | <https://www.aliexpress.us/item/2255800384086289.html> |

> [!NOTE]
> I recommend using Sheathed Wire Cable and soldering it directly onto the PCB. (JST XH Connector is not needed for this method) Usually, less connection issues than using connectors.

### Recommended Components (Case)
| Component | Variant | Link |
| -------------------- | --------------- | -------------------------------------------------------------------------------- |
| Trilancer Elastic Cinch Straps | See note below | <https://www.amazon.com/dp/B099RNRT7Z> |
| GoPro Chest Mount Harness | See note below | <https://www.aliexpress.us/item/3256805774922789.html> |

> [!NOTE]
> 12in works for ankles. 18in for thinner thighs and 24in for thicker thighs. Chest (if not using GoPro Chest Harness) and Hips can be done by doubling up on 18in/24in straps. Choose what you need for your body and how many trackers you are planning to make. 3 Size Combo and either 18in/24in package would be a start.

> [!NOTE]
> There are 2 types of GoPro Chest Mount Harness. One that clips in and the other one fasten by a bolt. Be sure to purchase one one for the case you are 3D Printing. 

### Ordering PCBs from JLCPCB
> [!IMPORTANT]
> JLCPCB option notes.

## Soldering/Assembly Guide

### Written Guide

> [!WARNING]
> Safety warning.

> [!TIP]
> Using external flux (preferably Rosin) will allow solder to flow to automatically flow into the correct area

> [!TIP]
> A wooden clothespin can be used to hold the boards together while soldering

> [!NOTE]
> Resistor and Diodes

### Video Guide (No Audio)
<a href="https://www.youtube.com/watch?v=Jj9A87dSZgY" target="_blank"><img src="http://i3.ytimg.com/vi/Jj9A87dSZgY/hqdefault.jpg" alt="Video Tutorial (No Audio)" width="360" height="270" border="0" /></a>

## Case Guide

## Troubleshooting

Join [SlimeVR Discord](https://discord.gg/SlimeVR) and ask in either the #techical-support or #DIY channels. It would be helpful for you to provide a description of your issue, photos of your soldering (front & back), and a log output from Settings > Serial Console with your tracker plugged into your computer via data USB cable into your WeMos D1 Port (non-charging). You will need to press the **Reboot** button to get the complete log.

### Using a Multimeter


## Contribute
Feel free to create a pull request to this repository or mention me in SlimeVR's Discord #DIY channel (Do not DM me, it will go to my Message Request and I will not reply to you there)  for improvement ideas or your modifications of the source files below. 

### Source Files
| Component | Link |
| -------------------- | -------------------------------------------------------------------------------- |
| PCB | <https://oshwlab.com/Newbie2620/slimevr-multi-imu-bmi-bno> |
| Case | [Fusion 360 Files](../blob/master/LICENSE) |

## Credit
| Contributor | Description | Link |
| -------------------- | ---------------------------------------- | -------------------------------------------------------------------------------- |
| Smeltie | Original Concept of the Hyperion Case | <https://github.com/Smeltie/Hyperion> |
| Lupinixx | Original BMI160 PCB Design and SS12D00G3 Tray used in this repository | <https://github.com/Lupinixx/SlimeVR-Hyperion-BMI160-PCB> |
| Tmandel | BNO085 modifications to the original PCB | <https://oshwlab.com/tmandel/slimevr-hyperion-503759-bno085> |
| Astrocast123 | Improvement on Tmandel's BNO08X PCB revision | <https://oshwlab.com/astrocast123/SlimeVR-Hyperion-BNO08X> |
| Shine Bright | Improvements to PCB, new case design, and this guide write-up in this repository | <https://oshwlab.com/astrocast123/SlimeVR-Hyperion-BNO08X> |

## License
This project is licensed under the MIT license.
