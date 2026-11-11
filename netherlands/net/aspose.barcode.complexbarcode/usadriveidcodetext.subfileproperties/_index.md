---
title: "Klasse USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextSubfileProperties klasse. USA DL subfile-eigenschappen offset en lengte worden automatisch ingesteld"
type: docs
weight: 840
url: /nl/net/aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
## USADriveIdCodetext.SubfileProperties class

USA DL subfile-eigenschappen, offset en lengte worden automatisch ingesteld.

```csharp
public class SubfileProperties
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/.ctor)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Length](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/length) { get; set; } | 4 Deze bytes bevatten een 4-cijferige numerieke waarde die de lengte van het Subfile in bytes specificeert. De segmentterminator moet worden meegenomen bij het berekenen van de lengte van het subfile. Een segmentterminator = 1. Elk subfile moet beginnen met het twee‑karakter Subfile Type en deze twee tekens moeten ook worden meegenomen in de lengte. |
| [Offset](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/offset) { get; set; } | 4-cijferige numerieke waarde die het aantal bytes aangeeft vanaf het begin van het bestand tot de locatie waar de gegevens die betrekking hebben op het betreffende sub‑file zich bevinden. Het eerste byte in het bestand bevindt zich op offset 0. |
| [Type](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/type) { get; set; } | 2‑byte type van subfile, bijvoorbeeld "DL" |

### Zie ook

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


