---
title: "enum"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " enum. Code128 için kodlama modu. Code 128 C++'daki spesifikasyon."
type: docs
weight: 5900
url: /tr/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


Code128 barkodları için kodlama modu. Code 128

spesifikasyon.

```cpp
enum class Code128EncodeMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Otomatik | 0 | Kod metnini klasik ISO 15417 modunda kodlayın. Mod, tüm olağan durumlarda kullanılmalıdır. |
| CodeA | 1 | Kod metnini yalnızca 128A kod kümesinde kodlayın. |
| CodeB | 2 | Kod metnini yalnızca 128B kod kümesinde kodlayın. |
| CodeC | 4 | Kod metnini yalnızca 128C kod kümesinde kodlayın. |
| CodeAB | 3 | Kod metnini yalnızca 128A ve 128B kod kümelerinde kodlayın. |
| CodeAC | 5 | Kod metnini yalnızca 128A ve 128C kod kümelerinde kodlayın. |
| CodeBC | 6 | Kod metnini yalnızca 128B ve 128C kod kümelerinde kodlayın. |

## Açıklamalar


Bu kod, farklı kodlamalarla code 128 nasıl oluşturulacağını gösterir
```cpp
[C#]
//ISO 15417 kodlamasıyla code 128 oluşturun
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Yalnızca Kod Kümesi A kodlamasıyla code 128 oluşturun
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
