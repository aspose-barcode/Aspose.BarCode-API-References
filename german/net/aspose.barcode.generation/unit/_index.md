---
title: "Klasse Unit"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.Unit‑Klasse. Gibt den Größenwert in verschiedenen Einheiten wie Pixel, Zoll usw. an."
type: docs
weight: 1740
url: /de/net/aspose.barcode.generation/unit/
---
## Unit class

Gibt den Größenwert in verschiedenen Einheiten (Pixel, Zoll usw.) an.

```csharp
public sealed class Unit
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.barcode.generation/unit/document/) { get; set; } | Liest oder setzt den Größenwert in Dokumenteinheiten. |
| [Inches](../../aspose.barcode.generation/unit/inches/) { get; set; } | Liest oder setzt den Größenwert in Zoll. |
| [Millimeters](../../aspose.barcode.generation/unit/millimeters/) { get; set; } | Liest oder setzt den Größenwert in Millimetern. |
| [Pixels](../../aspose.barcode.generation/unit/pixels/) { get; set; } | Liest oder setzt den Größenwert in Pixeln. |
| [Point](../../aspose.barcode.generation/unit/point/) { get; set; } | Liest oder setzt den Größenwert in Punkten. |
| [Resolution](../../aspose.barcode.generation/unit/resolution/) { get; } | Auflösung |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.generation/unit/equals/)(object) | Bestimmt, ob diese Instanz und ein angegebenes Objekt, das ebenfalls ein `Unit`‑Objekt sein muss, denselben Wert haben. |
| override [GetHashCode](../../aspose.barcode.generation/unit/gethashcode/)() | Gibt den Hash‑Code für dieses Objekt zurück. |
| override [ToString](../../aspose.barcode.generation/unit/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `Unit` zurück. |

## Beispiele

Dieses Beispiel zeigt, wie man ein BarCode‑Bild erstellt und speichert.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


