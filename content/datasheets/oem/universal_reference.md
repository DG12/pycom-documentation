---
title: "Universal OEM Baseboard Reference"
aliases:
    - datasheets/oem/universal_reference.html
    - datasheets/oem/universal_reference.md
    - product-info/oem/universal_reference
    - chapter/datasheets/oem/universal_reference
---

![](/gitbook/assets/universal_reference%20%281%29.png)

The universal OEM reference board is a reference design suitable for the W01, L01, L04 and G01 OEM modules, making it possible to have a single PCB design that can accommodate all of our OEM modules.

{{% hint style="info" %}}
If you require a reference board for the G01, this design is the only one that is suitable. The L01 reference board does not contain the necessary SIM slot.
{{% /hint %}}

## Features

* Suits all of the OEM modules \(L01, L04, W01, G01\)
* On-board 2.4GHz antenna for WiFi and Bluetooth, with the ability to switch to an external antenna via a U.FL connector.
* 3 U.FL connectors for all the outputs available on the OEM modules
* WS2812B RGB LED
* DC-DC regulator (3.5 - 5.5V) input with low current draw during Deep Sleep
* Reset button

## Layout

The layout of the OEM baseboard reference is available as a PDF File

<a href="/gitbook/assets/oem-universal-layout.pdf" target="_blank"> OEM Layout </a>

![](/gitbook/assets/oem-universal-layout-1.png)

## Schematic

The schematic of the OEM baseboard reference is available as a PDF File.

<a href="/gitbook/assets/oem-universal-schematic.pdf" target="_blank"> OEM Schematic </a>

## Altium Project and Gerber Files

The Altium Project and Gerber files are also available as a ZIP File.

[OEM Altium Project and Gerber Files](/gitbook/assets/oem-universal-baseboard-ref.zip)
