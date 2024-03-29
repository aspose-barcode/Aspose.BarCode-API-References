---
title: Metered
second_title: Aspose.BarCode für .NET-API-Referenz
description: Bietet Methoden zum Festlegen von gemessenen Schlüsseln.
type: docs
weight: 1020
url: /de/net/aspose.barcode/metered/
---
## Metered class

Bietet Methoden zum Festlegen von gemessenen Schlüsseln.

```csharp
public class Metered
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Metered](metered)() | Default_Constructor |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetMeteredKey](../../aspose.barcode/metered/setmeteredkey)(string, string) | Legt gemessene öffentliche und private Schlüssel fest |
| static [GetConsumptionCredit](../../aspose.barcode/metered/getconsumptioncredit)() | erhält Verbrauchsguthaben |
| static [GetConsumptionQuantity](../../aspose.barcode/metered/getconsumptionquantity)() | Ruft die Verbrauchsdateigröße ab |

### Beispiele

In diesem Beispiel wird versucht, einen getakteten öffentlichen und privaten Schlüssel zu setzen

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Siehe auch

* namensraum [Aspose.BarCode](../../aspose.barcode)
* Montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
