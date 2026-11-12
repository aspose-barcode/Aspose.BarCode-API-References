---
title: "AutoSizeMode"
linktitle: "AutoSizeMode"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Gibt die verschiedenen Typen automatischer Größeneinstellungsmodi an."
type: docs
weight: 20
url: /de/nodejs/global/autosizemode/
---

## AutoSizeMode

Gibt die verschiedenen Typen automatischer Größeneinstellungsmodi an. Der Standardwert ist AutoSizeMode.NONE.

## Werte

| Name | Beschreibung |
| --- | --- |
| NONE | Automatisches Ändern der Größe ist deaktiviert. Standardwert. |
| NEAREST | Der Barcode wird auf die nächstkleinere mögliche Größe verkleinert, die durch die Eigenschaften BarCodeWidth und BarCodeHeight angegeben ist. |
| INTERPOLATION | Skaliert den Barcode auf die angegebene Größe mit geringer Skalierung, kann jedoch in einigen Fällen leicht beschädigt werden, da Interpolation zur Skalierung verwendet wird. Die Größe kann über die Eigenschaften BarcodeGenerator.BarCodeWidth und BarcodeGenerator.BarCodeHeight festgelegt werden. |
