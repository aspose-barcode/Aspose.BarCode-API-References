---
title: "Code128EncodeMode enumı"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.Code128EncodeMode enum. Code128 barkodları için kodlama modu. Code 128 spesifikasyonu"
type: docs
weight: 1120
url: /tr/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

Code128 barkodları için kodlama modu. [Code 128](https://en.wikipedia.org/wiki/Code_128) spesifikasyonu.

```csharp
public enum Code128EncodeMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Auto | `0` | Kod metnini klasik ISO 15417 modunda kodlayın. Bu mod tüm olağan durumlarda kullanılmalıdır. |
| CodeA | `1` | Kod metnini yalnızca 128A kod kümesinde kodlayın. |
| CodeB | `2` | Kod metnini yalnızca 128B kod kümesinde kodlayın. |
| CodeC | `4` | Kod metnini yalnızca 128C kod kümesinde kodlayın. |
| CodeAB | `3` | Kod metnini yalnızca 128A ve 128B kod kümelerinde kodlayın. |
| CodeAC | `5` | Kod metnini yalnızca 128A ve 128C kod kümelerinde kodlayın. |
| CodeBC | `6` | Kod metnini yalnızca 128B ve 128C kod kümelerinde kodlayın. |

## Örnekler

Bu kod, farklı kodlamalarla code 128 nasıl oluşturulacağını gösterir

```csharp
[C#]
//Code 128'i ISO 15417 kodlamasıyla oluşturun
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Code 128'i yalnızca Codeset A kodlamasıyla oluşturun
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


