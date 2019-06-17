---
title: "FiPy"
aliases:
    - datasheets/development/fipy.html
    - datasheets/development/fipy.md
    - product-info/development/fipy
    - chapter/datasheets/development/fipy
---
![](/gitbook/assets/fipy-1.png)

**Store**: [Buy Here](http://www.pycom.io/fipy)

**Getting Started:** [Click Here](/../gettingstarted/connection/fipy)

## Pinout

The pinout of the FiPy is available as a PDF File

{% file src="/gitbook/assets/fipy-pinout.pdf" caption="FiPy Pinout" %}

![](/gitbook/assets/fipy-pinout.png)

{{% hint style="info" %}}
Please note that the PIN assignments for UART1 (TX1/RX1), SPI (CLK, MOSI, MISO) and I2C (SDA, SCL) are defaults and can be changed in Software.
{{< /hint >}}

## Datasheet

The datasheet of the FiPy is available as a PDF File.

{% file src="/gitbook/assets/fipy-specsheet-1.pdf" caption="FiPy Datasheet" %}

The drawing of the LTE-M antenna is available as a PDF File.

{% file src="/gitbook/assets/lte-m-antenna-drawing.pdf" caption="LTE-M Antenna Drawing" %}

## Notes

### WiFi

By default, upon boot the FiPy will create a WiFi access point with the SSID `fipy-wlan-XXXX`, where `XXXX` is a random 4-digit number, and the password `www.pycom.io`.

The RF switch that selects between the on-board and external antenna is connected to `P12`, for this reason using `P12` should be avoided unless WiFi is disabled in your application.

### Power

The `Vin` pin on the FiPy can be supplied with a voltage ranging from `3.5v` to `5.5v`. The `3.3v` pin on the other hand is output **only**, and must not be used to feed power into the FiPy, otherwise the on-board regulator will be damaged.

### AT Commands

The AT commands for the Sequans Monarch modem on the FiPy are available in a PDF file.

{% file src="/gitbook/assets/monarch\_4g-ez\_lr5110\_atcommands\_referencemanual\_rev3\_noconfidential-2.pdf" caption="AT Commands for Sequans" %}

## Tutorials

Tutorials on how to the FiPy module can be found in the [examples](/../tutorials/introduction) section of this documentation. The following tutorials might be of specific interest for the FiPy:

* [WiFi connection](/../tutorials/all/wlan)
* [LoRaWAN node](/../tutorials/lora/lorawan-abp)
* [LoRaWAN nano gateway](/../tutorials/lora/lorawan-nano-gateway)
* [Sigfox](/../tutorials/sigfox)
* [LTE CAT-M1](/../tutorials/lte/cat-m1)
* [NB-IoT](/../tutorials/lte/nb-iot)
* [BLE](/../tutorials/all/ble)

