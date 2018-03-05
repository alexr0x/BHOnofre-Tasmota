##BH OnOfre -Tasmota


Provide ESP8266 based Sonoff by [iTead Studio](https://www.itead.cc/) and ElectroDragon IoT Relay with Serial, Web and MQTT control allowing 'Over the Air' or OTA firmware updates using Arduino IDE.

### Atenção BH OnOfre

Flashar com o Arduino IDE com as Seguintes opções:
<img src="https://lh3.googleusercontent.com/1D4MX6Chg6HYpotD4_P3lpTCpwNwIEr1wtMsXeFZC7-QQwHTO_8-kngoJAhQjW7amcUG9b91o3M3pWhHpFQoDIid5NMMuPQ5cXthHs5SGvrf553h8I27NSjw5anjMmWEkty7r9zEuko8rjJe8Cupzv1WZh9vbGTlJHlC0U3lpT72eBDFS3S85yVn7WYmL_tTz-PJCOJEyFP5KxnXuOvLKq_byC5dA_JwCsxkg7ytcHZ1VLgf7Z_ESC1ghGWYUEx3AS6AdQP5745ctidPmVPnbIzIUaFP2w2DGDCLXUlQ-7y8G1jotMThUSEDZXm6pPpaXIO2EvkLvLk2Fmf8X29Hm4DmstECL8MLAUNdfdP4HXCVLnY_RsRUk1kGQ1HuhIakj07KD-tySJZDthLg6_4YlLA3Ct-SNva8UM3O9Y42dXK6wBauqHsCld8j3RnPYcfNvj3zTj0PZcbo8xOnNchum2PnuVktSrTlkFGH2pXEp2X8v5gHXPuDQkdX4V6hvCdGz7hXO5Nf_5IDgZeaicNJyo6z0_FV32VPG076hyjQ4DS0yiYk3QmEs4q0wIKSQsQAxA9jVR4pubM7pkVs-FirDPagAEOger4PaFTtaQo=w666-h526-no" width="250" align="right" />

Provide ESP8266 based Sonoff by [iTead Studio](https://www.itead.cc/) and ElectroDragon IoT Relay with Serial, Web and MQTT control allowing 'Over the Air' or OTA firmware updates using Arduino IDE.

### ATTENTION Version 5 and up

These versions use a new linker script to free flash memory for future code additions. It moves the settings from Spiffs to Eeprom. If you compile your own firmware download the new linker to your IDE or Platformio base folder. See [Wiki > Prerequisite](https://github.com/arendst/Sonoff-Tasmota/wiki/Prerequisite).

Best practice to implement is:
- Open the webpage to your device
- Perform option ``Backup Configuration``
- Upgrade new firmware using ``Firmware upgrade``
- If configuration conversion fails keep the webpage open and perform ``Restore Configuration``

You should now have a device with 32k more code memory to play with.

### Informação de Verses

- Sonoff-Tasmota provides all (Sonoff) modules in one file and starts with module Sonoff Basic.
- Once uploaded select module using the configuration webpage or the commands ```Modules``` and ```Module```.
- After reboot select config menu again or use commands ```GPIOs``` and ```GPIO``` to change GPIO with desired sensor.

<img src="http://www.bhonofre.pt/javax.faces.resource/images/onofre.png.xhtml?ln=apollo-layout" width="250" align="right" />

See [Wiki](https://github.com/arendst/Sonoff-Tasmota/wiki) for more information.<br />
See [Community](https://groups.google.com/d/forum/sonoffusers) for forum and more user experience.

Os Seguintes dispositivos são Suportados:
- [BH OnOfre](http://www.bhonofre.pt)
- Para SonOff consultar o Git Original

### Licença

Este programa está licenciado sob GPL-3.0
