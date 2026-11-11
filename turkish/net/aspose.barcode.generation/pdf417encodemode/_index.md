---
title: "Enum Pdf417EncodeMode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.Pdf417EncodeMode enum. Pdf417 barkod kodlama modu"
type: docs
weight: 1540
url: /tr/net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Pdf417 barkod kodlama modu

```csharp
public enum Pdf417EncodeMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Auto | `0` | Auto modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Unicode karakterleri, belirtilen ECIEncoding kodlamasında bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. |
| Binary | `1` | Binary modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Bir Unicode karakteri bulunursa, bir istisna fırlatılır. |
| ECI | `2` | ECI modunda, tüm mesaj belirtilen ECIEncoding kodlamasında bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. Lütfen bazı eski (2006 öncesi) tarayıcıların bu modu desteklemeyebileceğini unutmayın. |
| Extended | `3` | Çoklu ECI modlarını destekleyen genişletilmiş mod. |

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


