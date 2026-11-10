---
title: "Klasse FontUnit"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.FontUnit Klasse. Definiert ein bestimmtes Format für Text, einschließlich Schriftartgröße und Stil‑Attribute, wobei die Größe in der Unit‑Wert‑Eigenschaft angegeben wird."
type: docs
weight: 1320
url: /de/net/aspose.barcode.generation/fontunit/
---
## FontUnit class

Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stil‑Attribute, wobei die Größe in Unit value property angegeben wird.

```csharp
public sealed class FontUnit
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FamilyName](../../aspose.barcode.generation/fontunit/familyname/) { get; set; } | Liest oder setzt den Schriftartnamen dieses Font. |
| [Size](../../aspose.barcode.generation/fontunit/size/) { get; } | Liest oder setzt die Größe dieses FontUnit im Unit‑Wert. |
| [Style](../../aspose.barcode.generation/fontunit/style/) { get; set; } | Liest oder setzt Stilinformationen für dieses FontUnit. |

## Beispiele

Dieses Beispiel zeigt, wie man ein BarCode‑Bild erstellt und speichert.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


