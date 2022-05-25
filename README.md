# **Welcome to the META-IOT2050 Wiki**

## **List of working devices:**

The following tables show the support of different hardware at the different interfaces.

### **Support of mPCIe:**

| Devices in Chengdu         | PG1                       | PG2                       |
| -------------------------- | ------------------------- | ------------------------- |
| HuaWei\_3/4G\_ME909s\_821  | already tested, work fine | already tested, work fine |
| Telit\_3/4G\_he910-D       | already tested, work fine | already tested, work fine |
| Qualcomm\_4G\_mc7304       | already tested, work fine | already tested, work fine |
| WIFI\_BCM9432              | already tested, work fine | already tested, work fine |
| WIFI\_BCM43299             | already tested, work fine | already tested, work fine |
| WIFI\_Intel\_N135          | already tested, work fine | already tested, work fine |
| WIFI\_AR9462               | already tested, work fine | already tested, work fine |
| WIFI\_Intel\_6235          | already tested, work fine | already tested, work fine |
| 7260 Wifi                  | already tested, work fine | already tested, work fine |
| BT\_Intel\_6235            | already tested, work fine | already tested, work fine |
| SSD\_LEXIANGJIA            | already tested, work fine |  not test                 |
| Adapter\_mPCIeToUSB\_Wifi  | already tested, work fine | already tested, work fine |
| Adapter\_mPCIeToUSB\_Stick | already tested, work fine | already tested, work fine |
| huawei909s-120 v2          | already tested, work fine | already tested, work fine |
| 4G SIM7600CE               | already tested, work fine | already tested, work fine |
| WIFI\_Intel\_AC9260 NGW    |                           | already tested, work fine |
| WIFI\_m.2\_ax200ngw        |                           | already tested, work fine |
| WIFI\_m.2\_ax210ngw        |                           | failed                    |
| Qualcomm\_4G\_mc7403       |                           | failed, not supported     |
| ZTE TDD LET me3760v2       | failed                    |                           |
| Quectel EC20               | already tested, work fine |                           |

### **Support of USB:**

#### **Support of USB on PG1:**

### **Support of Arduino:**

#### **Support of Arduino on PG1:**

|List by Volker                                         |Devices in Chengdu                           |status                      |notes                                                                         |
|-------------------------------------------------------|---------------------------------------------|----------------------------|------------------------------------------------------------------------------|
|Input / Output Module                                  |RS232 Shield                                 |already tested, have issue. |because of Arduino UART function  have issue, will be retested after bug fixed|
|Input Module Sink / Source                             |LEDs Shield                                  |                            |from FL, but no such shield                                                   |
|Lora Shield FlexSensor-045AR™ LoRa end device          |Reset button Shield                          |                            |from FL, but no such shield                                                   |
|shield for Masterdrive connection                      |Input / Output Module                        |already tested, work fine   |                                                                              |
|shields for weighting                                  |Input Module Sink / Source                   |already tested, work fine   |                                                                              |
|IKHDS Powershield IOT2000                              |Lora Shield FlexSensor-045AR™ LoRa end device|will be test, wait equipment|volker will delivery to chengdu                                               |
|Velleman Shield VMA05 I/O Shield                       |shield for Masterdrive connection            |will be test, wait equipment|Zhao Hui will ask from NanJing                                                |
|Arduino Motor Shield Rev 3 (A000079)                   |shields for weighting                        |will be test, wait equipment|Zhao Hui will ask from DaLian                                                 |
|Arduino XBee Shield for Zigbee (A000021)               |IKHDS Powershield IOT2000                    |will be test, wait equipment|volker will delivery to chengdu                                               |
|Arduino Wireless Shield with SD socket (A000065)       |RS485 Shield                                 |                            |from FL, but no such shield                                                   |
|Arduino Wireless Shield (A000064)                      |Arduino GSM shield                           |                            |lack of Arduino IDE, can't use it.                                            |
|TinkerKit Sensor shield (T020010)                      |Arduino Ethernet shield                      |                            |lack of Arduino IDE, can't use it.                                            |
|Arduino Ethernet shield 2 without POE (A000024)        |Arduino wireless shield                      |                            |lack of Arduino IDE, can't use it.                                            |
|Annikken Andee U - uses ATMEL specific funcions for SPI|Arduino Camera shield                        |                            |lack of Arduino IDE, can't use it.                                            |
|Arduino Wi-Fi Shield (A000058)                         |Arduino YUN shield                           |                            |lack of Arduino IDE, can't use it.                                            |
|GSM one antenna (A000043)                              |Zigbee shield                                |                            |lack of Arduino IDE, can't use it.                                            |
|                                                       |base shield                                  |will be test                |                                                                              |

### **Support of Serial:**

#### **Support of Serial on PG1:**

|List by Volker                                                 |Devices in Chengdu                                             |status                   |
|---------------------------------------------------------------|---------------------------------------------------------------|-------------------------|
|direct communication to other IPC (e.g. IPC327) RS232 and RS485|printer                                                        |will be test             |
|Sensors with RS485 and most modbus input                       |barcode scanner                                                |will be test             |
|                                                               |direct communication to other IPC (e.g. IPC327) RS232 and RS485|already tested, work fine|
|                                                               |Temperature Sensors with RS485 (Modbus-RTU)                    |already tested, work fine|
|                                                               |RS232->RS485 Adapter                                           |already tested, work fine|
|                                                               |RS232->RS422 Adapter                                           |already tested, work fine|
