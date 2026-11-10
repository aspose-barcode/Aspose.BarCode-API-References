---
title: "Klasse Metered"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Metered‑Klasse. Stellt Methoden zum Festlegen des gemessenen Schlüssels bereit."
type: docs
weight: 1770
url: /de/net/aspose.barcode/metered/
---
## Metered class

Stellt Methoden zum Festlegen des Metered‑Schlüssels bereit.

```csharp
public class Metered
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Metered](metered/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetProductName](../../aspose.barcode/metered/getproductname/)() | Ermittelt den Namen des lizenzierten Produkts |
| [SetMeteredKey](../../aspose.barcode/metered/setmeteredkey/)(string, string) | Setzt den gemessenen öffentlichen und privaten Schlüssel. Wenn Sie eine gemessene Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Wenn jedoch ständig das Hochladen von Verbrauchsdaten fehlschlägt und 24 Stunden überschritten werden, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf. |
| static [GetConsumptionCredit](../../aspose.barcode/metered/getconsumptioncredit/)() | Ermittelt das Verbrauchsguthaben |
| static [GetConsumptionQuantity](../../aspose.barcode/metered/getconsumptionquantity/)() | Ermittelt die Größe der Verbrauchsdatei |
| static [IsMeteredLicensed](../../aspose.barcode/metered/ismeteredlicensed/)() | Überprüft, ob die gemessene Lizenz lizenziert ist |

## Beispiele

In diesem Beispiel wird versucht, den gemessenen öffentlichen und privaten Schlüssel zu setzen.

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Siehe auch

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


