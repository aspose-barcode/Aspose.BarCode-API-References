---
title: "Klasse USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextSubfileProperties Klasse. USA DL Subdateieigenschaften Offset und Länge werden automatisch gesetzt"
type: docs
weight: 840
url: /de/net/aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
## USADriveIdCodetext.SubfileProperties class

USA DL Subdateieigenschaften, Offset und Länge werden automatisch gesetzt.

```csharp
public class SubfileProperties
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/.ctor)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Length](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/length) { get; set; } | 4 Diese Bytes enthalten einen 4‑stelligen numerischen Wert, der die Länge der Subdatei in Bytes angibt. Der Segmentterminator muss bei der Berechnung der Subdateilänge berücksichtigt werden. Ein Segmentterminator = 1. Jede Subdatei muss mit dem zweistelligen Subfile‑Typ beginnen, und diese beiden Zeichen müssen ebenfalls in die Länge einbezogen werden. |
| [Offset](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/offset) { get; set; } | 4‑stelliger numerischer Wert, der die Anzahl der Bytes vom Anfang der Datei bis zu dem Ort angibt, an dem die Daten der jeweiligen Subdatei gespeichert sind. Das erste Byte in der Datei befindet sich bei Offset 0. |
| [Type](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/type) { get; set; } | 2‑Byte‑Typ der Subdatei, z. B. \"DL\" |

### Siehe auch

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


